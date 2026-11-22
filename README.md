# Dashboard KPI — NBI

Dashboard KPI manajemen CV Nano's Berkah Indonesia: angka agregat Bolphis,
Risolna, dan Nano's dari Central Hub CRM NBI.

**Live:** https://bolphis-id.github.io/nbi-kpi-dashboard/

## Isinya

- Total prospek, closing, closing rate, perlu follow up, masuk hari ini, dan
  transaksi bulan ini — per brand dan gabungan.
- Funnel **Leads dari Form** (masuk / Super Leads / closing yang cocok dengan
  transaksi Olsera / conversion rate) dan rekapan leads per minggu.
- Closing per outlet, termasuk "Tanpa outlet" (pelanggan lama yang outletnya
  belum terisi dari transaksi).

## Data

- Sumber: spreadsheet **Central Hub CRM NBI** (Google Sheets).
- File `data.json` dibuat ulang otomatis setiap pagi (setelah sync jam 03.00
  dan 04.00 WITA) oleh skrip `refresh_kpi_data.py` — bukan dari halaman ini.
- **Privasi:** halaman ini hanya menampilkan angka agregat. Tidak ada nama,
  nomor HP, atau data pelanggan per orang di repo ini.

## File

- `index.html` — halaman dashboard (mengambil `data.json`).
- `data.json` — angka agregat terakhir (dibuat oleh skrip refresh).
- `refresh_kpi_data.py` tidak ada di repo ini; tersimpan di workspace Muse
  (`workspace/bolphis/integrasi-sistem-nbi/`).
