TAKWIM PINTAR 2027 - SEKOLAH KEBANGSAAN PARIT MARKOM
VERSI PWA UNTUK GITHUB PAGES

KONFIGURASI
- Negeri: Johor
- Tahun: 2027
- Nama sekolah: SEKOLAH KEBANGSAAN PARIT MARKOM
- Moto 1: SKPM the best
- Moto 2: Melangkah dengan bergaya
- Lencana/PWA icon: https://iili.io/nUnqzG4.md.png
- Sheet ID: 19SMyRdakiLAZbewodljiWMGmLgkxlyxTlnhqeFcKY3M
- CSV Cuti gid: 457971484
- CSV Program gid: 679655066
- Web App Apps Script: telah dimasukkan dalam app.js

ADMIN
- Username: admin
- Password: JBA6051
- Password disahkan pada Apps Script dan tidak disimpan sebagai teks biasa dalam frontend GitHub.

FAIL UNTUK GITHUB
- index.html
- style.css
- app.js
- manifest.webmanifest
- sw.js
- README_PWA.txt

CARA PASANG APPS SCRIPT
1. Buka Google Sheet > Extensions > Apps Script.
2. Gantikan Code.gs dengan AppsScript_Takwim_Pintar_2027_SK_Parit_Markom.gs.
3. Save.
4. Run setupTakwimSystem2027().
5. Run resetAdminCredentials2027().
6. Run testConnection2027().
7. Deploy > Manage deployments > Edit > New version > Deploy.
8. Execute as: Me. Who has access: Anyone.
9. Jika mengemas kini deployment yang sama, URL /exec tidak perlu berubah.

PWA
- Upload semua fail GitHub ke root repository.
- Aktifkan GitHub Pages.
- Selepas halaman dibuka sekurang-kurangnya sekali secara online, fail aplikasi asas boleh dicache oleh Service Worker.
- Lencana sekolah digunakan sebagai logo, favicon, Apple Touch Icon dan ikon PWA melalui URL lencana yang dibekalkan.
