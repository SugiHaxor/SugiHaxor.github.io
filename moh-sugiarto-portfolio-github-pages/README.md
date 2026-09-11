# Moh. Sugiarto — Portfolio Website

Website portofolio statis, siap dipasang gratis di **GitHub Pages**.

## Isi folder
- `index.html` — halaman utama
- `style.css` — desain/responsive styling
- `script.js` — menu mobile, animasi, active navigation
- `assets/moh-sugiarto.png` — foto dari CV
- `assets/favicon.svg` — favicon

## Cara publish di GitHub Pages
1. Login ke GitHub.
2. Klik **New repository**.
3. Nama repository bisa `portfolio` atau `sugihaxor.github.io`.
4. Upload semua file **di dalam folder ini** ke root repository.
5. Masuk **Settings → Pages**.
6. Pada **Build and deployment**, pilih **Deploy from a branch**.
7. Branch: `main`, folder: `/ (root)`, lalu **Save**.
8. Tunggu 1–5 menit. GitHub akan menampilkan URL website.

Jika repository bernama `SugiHaxor.github.io`, alamat utamanya menjadi:
`https://sugihaxor.github.io/`

Jika repository bernama `portfolio`, biasanya menjadi:
`https://sugihaxor.github.io/portfolio/`

## Edit cepat
Data utama ada di `index.html`. Warna tema ada di bagian paling atas `style.css` pada variabel `:root`.

## Catatan
GitHub Pages hanya untuk website statis. Project Mini HRIS yang memakai Node.js/Express/MySQL perlu hosting backend/database terpisah jika ingin demo full-stack online.
