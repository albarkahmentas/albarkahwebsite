Masjid Al Barkah - Website Sederhana
====================================

Isi folder:
- index.html
- styles.css
- logo.png (REPLACE: pakai logo yang Anda unggah)
- TEMPLATE_GOOGLE_FORMS.md (panduan & field untuk Google Forms)

Langkah cepat untuk ZIP & upload:
1. Buat folder bernama: masjid-al-barkah-website
2. Simpan semua file (index.html, styles.css, logo.png, TEMPLATE_GOOGLE_FORMS.md) di folder tersebut.
3. Di Windows: klik kanan folder -> Send to -> Compressed (zipped) folder.
   Di macOS / Linux: jalankan `zip -r masjid-al-barkah-website.zip masjid-al-barkah-website/`

Mengganti placeholder penting sebelum upload:
- Ganti [Nama Ketua] dan struktur pengurus di index.html.
- Ganti informasi rekening di bagian Donasi.
- Jika pakai Formspree: daftar di https://formspree.io, dapatkan `your_form_id` lalu ganti atribut action pada form.
- Jika pakai Google Form untuk konfirmasi pembayaran: buat Form → klik Send → Embed → salin iframe dan masukkan ke iframe di bagian "Form Pembayaran".

Cara deploy gratis (opsi):
A) GitHub Pages:
   - Buat repo public di GitHub, upload semua file ke branch main.
   - Settings → Pages → pilih branch main → Save. Situs akan tersedia di https://username.github.io/repo

B) Netlify (drag & drop):
   - Buka netlify.com → Sites → New site from Git → atau cukup drag & drop ZIP/folder pada dashboard.
   - Ikuti petunjuk.

C) Google Sites (tanpa coding):
   - Jika pengurus non-teknis, buat Google Sites baru, tambahkan gambar & teks, embed Google Form langsung. (Paling mudah)

Form & pembayaran:
- Rekomendasi cepat: buat 2 Google Form (Pesanan & Konfirmasi Pembayaran). Upload bukti transfer via Google Form untuk mempermudah verifikasi.

Butuh saya bantu lagi?
- Saya bisa membuat template Google Form (isi pertanyaan) agar Anda copy-paste.
- Jika mau deploy langsung ke GitHub Pages, saya bisa pandu langkah-langkahnya.
