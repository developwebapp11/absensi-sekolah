# Absensi Digital Multi-Cabang — Frontend

Frontend statis (HTML/CSS/JS) untuk aplikasi absensi berbasis GPS + selfie.
Backend: Google Apps Script (REST API JSON). Hosting frontend: GitHub Pages.

## Struktur
```
index.html        ← harus di root repository
css/style.css
js/config.js      ← isi GAS_URL di sini
js/api.js
js/app.js
```

## Konfigurasi
Edit `js/config.js`, isi `GAS_URL` dengan URL Web App Apps Script (`.../exec`).

## Deploy
Lihat `PANDUAN-INSTALASI.md`. Setelah mengubah file apa pun:
```
git add .
git commit -m "Deskripsi perubahan"
git push
```
