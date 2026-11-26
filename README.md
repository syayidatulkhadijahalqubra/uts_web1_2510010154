# HOUSE DREAM — Website Profil Perumahan Eksklusif

Proyek Ujian Tengah Semester (UTS) Pemrograman Web 1: website statis multi-halaman bertema perumahan eksklusif bergaya **Modern & Villa** dengan palet warna **Pastel Pink & Ivory** (tanpa JavaScript).

## Identitas Mahasiswa
- **Nama:** Syayidatul Khadijah Al Qubra
- **NPM:** 2510010154
- **Kelas:** 3A TI Non Reguler Banjarbaru
- **Mata Kuliah:** Pemrograman Web 1

## Struktur File
```text
uts_web1_2510010154/
├── index.html       # Halaman beranda (Hero, 6 kartu unit eksklusif, keunggulan, testimoni)
├── kontak.html      # Halaman kontak (Form konsultasi, tabel layanan, peta Google Maps)
├── css/
│   └── style.css    # Stylesheet eksternal (mobile-first, grid, flexbox, dark mode)
└── README.md        # Dokumentasi proyek
```

## Fitur Utama
- Struktur HTML5 semantik (`header`, `nav`, `main`, `section`, `article`, `figure`, `figcaption`, `time`, `footer`).
- Navbar `position: fixed` dengan menu hamburger CSS-only (checkbox) di layar mobile.
- Layout responsif mobile-first (teruji pada `360px` dan desktop `1280px`) tanpa overflow horizontal.
- Subheader `position: sticky`, efek hover halus pada kartu/tombol, serta dukungan `prefers-color-scheme: dark`.
- Halaman kontak lengkap dengan `fieldset`, `legend`, `required`, tabel `colspan`, dan embed Google Maps (`iframe`).

## Cara Menjalankan
Buka [index.html](index.html) langsung di browser atau jalankan melalui Live Server / HTTP server lokal:
```bash
python -m http.server 5500
```
Lalu akses `http://localhost:5500/`.
