# Key Rafi Kaendre — Portfolio Website

Website portofolio statis menggunakan HTML, CSS, dan JavaScript. Siap dipublikasikan melalui GitHub Pages.

## File
- `index.html` — konten dan struktur website
- `style.css` — tampilan responsif
- `script.js` — navigasi mobile, animasi scroll, dan tahun footer
- `assets/` — tempat menyimpan foto, CV, dan gambar proyek

## Cara menjalankan secara lokal
Buka `index.html` di browser, atau gunakan ekstensi Live Server di VS Code.

## Cara deploy ke GitHub Pages
1. Buat repository bernama `USERNAME.github.io` (Public).
2. Upload seluruh isi folder ini ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
6. Tunggu proses publikasi. Website akan tersedia di `https://USERNAME.github.io/`.

## Personalisasi sebelum dipublikasikan
Cari dan ganti:
- `emailkamu@example.com` dengan email aktif.
- Link GitHub dan LinkedIn di bagian Contact dengan profil pribadi.
- Tambahkan foto profil dan screenshot proyek asli ke folder `assets/`, lalu sesuaikan markup di `index.html`.
- Periksa kembali deskripsi pengalaman dan proyek agar sesuai dengan kontribusi yang benar-benar dilakukan.
- Jika sudah memiliki CV PDF, simpan di `assets/CV-Key-Rafi.pdf` dan tambahkan tautan unduhan di bagian hero atau kontak.

## Catatan
GitHub Pages hanya meng-host website statis. Backend PHP/Laravel dan database tidak berjalan langsung di GitHub Pages. Untuk proyek Laravel, gunakan screenshot, deskripsi, repository kode, atau tautan demo yang di-host di layanan backend terpisah.
