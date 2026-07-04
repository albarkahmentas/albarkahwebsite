Panduan membuat 2 Google Form (template fields)

1) Form Pesanan (Order)
Fields (semua required jika perlu):
- Nama Pemesan (Short answer)
- No. HP / WhatsApp (Short answer)
- Email (Optional)
- Jenis Pesanan (Multiple choice / dropdown) -> Nasi kotak / Sewa Aula / Oleh-oleh
- Tanggal Acara (Date)
- Jumlah (Short answer / Number)
- Alamat Pengiriman / Lokasi (Paragraph)
- Catatan Tambahan (Paragraph)
- Metode Pembayaran (Dropdown) -> Transfer / COD / Lainnya
- Kesepakatan (Checkbox) -> "Saya setuju dengan syarat & ketentuan pemesanan"

2) Form Konfirmasi Pembayaran
Fields:
- Nama Donatur / Pemesan
- Nominal Transfer (Number)
- Tanggal Transfer (Date)
- Bank Pengirim (Short answer)
- Rekening Tujuan (pre-fill dengan rekening masjid atau dropdown)
- Upload Bukti Transfer (File upload - Images only)
- Metode Transfer (Dropdown) - Transfer Bank / E-Wallet / QRIS
- Pesan untuk Bendahara (Optional)

Cara embed:
- Di Google Form → Send → Embed (< >) → Salin iframe.
- Paste iframe ke index.html (lihat komentar di bagian "Form Pembayaran").

Notifikasi:
- Tambahkan setting agar respons dikirim ke Google Sheets (Responses → Create spreadsheet).
- Aktifkan notifikasi email (Add-on: Form Notifications) untuk bendahara.

Keamanan:
- Batasi akses upload file agar hanya menerima file (default Google Form akan menyimpan ke Google Drive pemilik form).
