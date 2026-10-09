# Nalarakit

**Solusi Digital yang Dibangun dengan Nalar.**

IDEA • SYSTEM • REAL IMPACT

[Buka website Nalarakit](https://sukmanlife.github.io/nalarakit/) · [Layanan dan kontak](https://lynk.id/nalarakit)

Nalarakit adalah website profil layanan digital untuk individu dan bisnis. Website ini memperkenalkan layanan pembuatan website, sistem informasi, analisis data, dan otomatisasi proses, disertai konsep portofolio serta jalur kontak untuk membahas kebutuhan proyek.

Tujuannya sederhana: membantu calon pelanggan memahami layanan Nalarakit dan memulai percakapan tentang solusi yang mereka butuhkan.

## Fitur

- **Navigasi responsif:** menu Beranda, Layanan, Portofolio, Tentang, dan Kontak, dengan tombol menu khusus layar kecil.
- **Hero dan CTA:** pesan utama merek serta tombol Mulai Proyek dan Lihat Portofolio.
- **Ilustrasi dashboard/laptop:** dibuat langsung dengan HTML, CSS, dan SVG tanpa ketergantungan gambar eksternal.
- **Empat layanan:** Website Development, Sistem Informasi, Analisis Data, dan Otomatisasi Proses.
- **Tiga konsep portofolio:** Website Company Profile, Sistem Informasi, dan Aplikasi Web, dengan dialog detail yang dapat dibuka dan ditutup.
- **Kontak bisnis:** tombol email dan tautan menuju Lynk.id Nalarakit.
- **Aksesibilitas dasar:** struktur HTML semantik, tautan lewati ke konten, fokus keyboard, status menu, dan dukungan preferensi pengurangan animasi.
- **Tampilan desktop dan ponsel:** susunan kolom, tombol, serta kartu menyesuaikan ukuran layar.

Portofolio pada halaman ini merupakan ilustrasi konsep. Angka pada mockup adalah contoh visual. Halaman profil ini belum menyediakan login pelanggan, database, checkout, atau aplikasi pengelolaan usaha; layanan pengembangan dibahas sesuai kebutuhan proyek.

## Tech stack

| Bagian | Teknologi |
| --- | --- |
| Struktur halaman | HTML5 |
| Tampilan | Tailwind CSS 4 melalui CDN dan CSS khusus |
| Interaksi | JavaScript murni |
| Font | Poppins melalui Google Fonts |
| Ikon dan ilustrasi | SVG inline dan CSS |
| Hosting | Kompatibel dengan hosting statis, termasuk GitHub Pages |

Kode halaman disimpan dalam satu `index.html`. Tidak diperlukan PHP, database, Node.js, atau instalasi paket untuk membuka halaman ini. Koneksi internet diperlukan untuk memuat Tailwind CDN dan Google Fonts.

## Quick Start

### 1. Unduh proyek

```bash
git clone https://github.com/sukmanlife/nalarakit.git
cd nalarakit
```

Alternatif tanpa Git: gunakan **Code → Download ZIP** di GitHub, lalu ekstrak file.

### 2. Buka di VS Code

Pilih **File → Open Folder**, lalu buka folder `nalarakit`.

Jika ekstensi Live Server sudah tersedia:

1. Buka `index.html`.
2. Klik kanan dan pilih **Open with Live Server**, atau klik **Go Live**.
3. Browser akan membuka alamat lokal yang disediakan ekstensi.

### Alternatif: browser langsung

Buka file `index.html` melalui browser. Ini cukup untuk melihat halaman dan mencoba menu serta dialog portofolio.

### Alternatif: server lokal Python

Jika Python 3 terpasang, jalankan perintah berikut dari folder proyek:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Buka [http://127.0.0.1:8000](http://127.0.0.1:8000). Biarkan terminal berjalan selama pratinjau digunakan; tekan **Ctrl+C** untuk menghentikannya.

## Struktur proyek

```text
nalarakit/
├── index.html   # Seluruh struktur, gaya, ikon, dan interaksi halaman
├── README.md    # Dokumentasi proyek
├── .gitignore   # Mengabaikan file lokal dan konfigurasi pribadi
└── .nojekyll    # Menyajikan file statis langsung pada GitHub Pages
```

## Identitas visual

| Elemen | Nilai |
| --- | --- |
| Biru utama | `#2553EB` |
| Biru sekunder | `#3B82F6` |
| Aksen biru muda | `#93C5FD` |
| Teks gelap / footer | `#0F172A` |
| Elemen gelap sekunder | `#1E293B` |
| Latar lembut | `#E2E8F0`, `#F8FAFC` |
| Tipografi | Poppins |

## Mengubah konten

- Edit teks layanan pada bagian `layanan` di `index.html`.
- Edit kartu pada bagian `portofolio`; isi dialognya tersimpan pada objek JavaScript `projects`.
- Perbarui tujuan tombol pada bagian `kontak` dan tautan di footer saat kanal bisnis berubah.
- Sesuaikan warna merek pada blok `@theme` dan CSS khusus.

## Publikasi melalui GitHub Pages

Website aktif di [sukmanlife.github.io/nalarakit](https://sukmanlife.github.io/nalarakit/) dan dipublikasikan dari branch `main`, folder `/(root)`. Perubahan yang dikirim ke branch ini akan memicu publikasi ulang.

Untuk menyiapkan deployment yang sama pada salinan repository:

1. Buka **Settings → Pages** pada repository.
2. Pilih **Deploy from a branch**.
3. Pilih branch **main** dan folder **/(root)**, lalu simpan.
4. Tunggu proses publikasi selesai dan buka alamat website yang ditampilkan GitHub.

Tidak ada proses build lokal untuk versi ini. Tailwind dimuat dan diproses di browser melalui CDN.

## Kontak Nalarakit

- [Lynk.id](https://lynk.id/nalarakit)
- [Instagram @nalarakit_](https://www.instagram.com/nalarakit_/)
- [Threads @nalarakit_](https://www.threads.com/@nalarakit_)
- [Email bisnis](mailto:nalarakit3@gmail.com)

Untuk usulan perbaikan atau laporan masalah pada website, buka [issue](https://github.com/sukmanlife/nalarakit/issues) dan sertakan langkah untuk mengulangi masalah.
