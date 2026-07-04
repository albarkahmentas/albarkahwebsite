<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pemesanan - Masjid Al Barkah</title>
  <link rel="stylesheet" href="../css/style.css" />
  <link rel="stylesheet" href="../css/responsive.css" />
  <link rel="stylesheet" href="../css/animation.css" />
</head>
<body>
  <main class="container section">
    <h1>Form Pemesanan</h1>
    <p class="form-intro">Silakan isi formulir berikut untuk memesan layanan, kebutuhan barang, atau dukungan acara dari masjid.</p>
    <form>
      <label>Nama Lengkap<input type="text" placeholder="Nama lengkap" required /></label>
      <label>Nomor WhatsApp<input type="tel" placeholder="08xxxxxxxxxx" required /></label>
      <label>Jenis Layanan<select required>
        <option value="">Pilih jenis layanan</option>
        <option>Pengadaan Barang</option>
        <option>Jasa Acara</option>
        <option>Peralatan</option>
        <option>Kebutuhan Sosial</option>
      </select></label>
      <label>Untuk Keperluan<input type="text" placeholder="Contoh: acara pengajian, kegiatan sosial" required /></label>
      <label>Jumlah/Volume<input type="text" placeholder="Contoh: 50 pax atau 2 unit" /></label>
      <label>Tanggal Dibutuhkan<input type="date" /></label>
      <label>Alamat Lengkap<textarea rows="4" placeholder="Tuliskan alamat lengkap"></textarea></label>
      <label>Detail Kebutuhan<textarea rows="5" placeholder="Jelaskan kebutuhan secara rinci"></textarea></label>
      <label>Catatan Tambahan<textarea rows="3" placeholder="Opsional"></textarea></label>
      <button type="submit">Kirim Pemesanan</button>
      <p class="form-note">Permintaan Anda akan kami tindaklanjuti sesegera mungkin melalui kontak yang telah diberikan.</p>
    </form>
  </main>
  <script src="../js/form.js"></script>
</body>
</html>
