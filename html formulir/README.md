# Contoh Formulir HTML

## Penjelasan Kode
1. `<h1>Formulir Pendaftaran</h1>`:

   - Elemen heading utama untuk judul halaman formulir.

2. `<form action="/submit-form" method="post">`:

    - Elemen `<form>` digunakan untuk membungkus semua elemen input dan menentukan URL tujuan dengan atribut `action` serta metode pengiriman data dengan atribut `method`.

3. `<label for="nama">Nama:</label>` dan `<input type="text" id="nama" name="nama">`:

    - Elemen label digunakan untuk memberikan keterangan pada input, sementara elemen input dengan tipe `text` digunakan untuk menerima teks singkat dari pengguna.

4. `<label for="email">Email:</label>` dan `<input type="email" id="email" name="email">`:

    - Elemen input dengan tipe `email` digunakan untuk menerima alamat email pengguna.

5. `<label for="password">Kata Sandi:</label>` dan `<input type="password" id="password" name="password">`:

    - Elemen input dengan tipe `password` digunakan untuk menerima kata sandi yang tidak akan terlihat saat diketik.

6. `<label for="pesan">Pesan:</label>` dan `<textarea id="pesan" name="pesan"></textarea>`:

    - Elemen textarea digunakan untuk menerima teks panjang seperti pesan atau deskripsi.

7. `<p>Jenis Kelamin:</p>`, `<label for="male">Laki-Laki</label>`, `<input type="radio" id="male" name="gender" value="male">`, dll.:

    - Elemen radio button digunakan untuk memungkinkan pengguna memilih satu opsi dari beberapa pilihan.

8. `<p>Hobi:</p>`, `<label for="hobi1">Olahraga</label>`, `<input type="checkbox" id="hobi1" name="hobi" value="olahraga">`, dll.:

    - Elemen checkbox digunakan untuk memungkinkan pengguna memilih satu atau lebih opsi dari beberapa pilihan.

9. `<label for="kota">Pilih Kota:</label>` dan `<select id="kota" name="kota">`, `<option value="jakarta">Kota Jakarta</option>`:

    - Elemen dropdown (select) digunakan untuk memungkinkan pengguna memilih satu opsi dari daftar pilihan yang tersedia.

10. `<button type="submit">Kirim</button>`:
    - Tombol yang digunakan untuk mengirim data yang telah diisi dalam formulir ke URL yang ditentukan dalam atribut `action` dari elemen `<form>`.

## Kesimpulan

Formulir HTML merupakan bagian penting dalam pengembangan web, memungkinkan pengumpulan data dari pengguna dengan berbagai jenis input. Memahami penggunaan setiap elemen form adalah langkah awal dalam menciptakan aplikasi web yang interaktif dan user-friendly.
