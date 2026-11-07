# DEMO — Masjid Digital Enterprise

Versi demo yang berjalan **100% di browser** (tanpa server). Publikasikan di repo GitHub **terpisah** dari aplikasi asli.

## Isi (5 berkas)
`index.html` (aplikasi + mesin demo + data contoh), `manifest.webmanifest`, `sw.js`, `icon.svg`, `README.md`.

## Deploy
Repo baru → unggah 5 berkas → Settings → Pages → main / root. Buka `https://<user>.github.io/<repo>/`.
Portal publik demo: `?portal`.

## Batasan (tidak mengganggu & tidak dapat dipakai mengakali versi asli)
- Tidak berisi kode server Apps Script, kunci, atau logika lisensi; tidak menghubungi Google Sheets/Drive/License Server.
- Penyimpanan memakai namespace `mdedemo.*` dan cache service worker `mde-demo-*` — terpisah dari aplikasi asli walau satu domain.
- Data contoh fiktif, reset otomatis 14 hari; batas 40 transaksi baru, 30 data/modul, 6 lampiran ≤ 260 KB, impor 15 baris.
- Ekspor CSV/JSON, backup, lisensi, kelola pengguna/peran, sandi/MFA, bagan akun, tutup buku, WA, jadwal online, Gemini AI dinonaktifkan.
- Cetak/PDF bertanda air DEMO.
