# Aplikasi Pengelolaan Kontak

## Deskripsi
Aplikasi Pengelolaan Kontak adalah aplikasi berbasis GUI yang memungkinkan pengguna untuk mengelola informasi kontak. Pengguna dapat menambahkan, mengedit, menghapus, dan mencari kontak, serta mengekspor dan mengimpor data kontak dalam format CSV. Aplikasi ini menggunakan database untuk menyimpan data kontak dan memberikan antarmuka yang intuitif untuk interaksi pengguna.

## Komponen GUI
Aplikasi ini terdiri dari beberapa komponen GUI yang memudahkan pengguna dalam mengelola kontak:

1. **Input Fields**:
   - **JLabel**:
     - `Nama`: Label untuk memasukkan nama kontak.
     - `No. HP`: Label untuk memasukkan nomor telepon kontak.
     - `Alamat`: Label untuk memasukkan alamat kontak.
     - `Gender`: Label untuk memilih jenis kelamin (Laki-Laki/Perempuan).
     - `Kategori`: Label untuk memilih kategori kontak (Keluarga, Teman, Kerja).
     - `CARI`: Label untuk mencari kontak.
   - **JTextField**:
     - `nameInput`: Untuk memasukkan nama kontak.
     - `handphoneInput`: Untuk memasukkan nomor telepon kontak.
     - `alamatInput`: Untuk memasukkan alamat kontak.
     - `cariInput`: Untuk memasukkan nama atau nomor telepon yang ingin dicari.

2. **ComboBox**:
   - **genderPilih**: Dropdown untuk memilih jenis kelamin (Laki-Laki/Perempuan).
   - **kategoriPilih**: Dropdown untuk memilih kategori kontak (Keluarga, Teman, Kerja).

3. **Tombol Aksi**:
   - **JButton**:
     - `TAMBAH`: Untuk menambahkan kontak baru.
     - `EDIT`: Untuk mengedit kontak yang dipilih.
     - `SIMPAN`: Untuk menyimpan perubahan yang dilakukan pada kontak.
     - `HAPUS`: Untuk menghapus kontak yang dipilih.
     - `EKSPOR`: Untuk mengekspor data kontak ke file CSV.
     - `IMPOR`: Untuk mengimpor data kontak dari file CSV.
     - `CARI`: Untuk mencari kontak berdasarkan nama atau nomor telepon.
     - `Keluar`: Untuk menutup aplikasi.

4. **Tabel Kontak**:
   - **JTable**:
     - `tblKontak`: Menampilkan daftar kontak yang telah disimpan dalam database dengan kolom untuk Nama, No. HP, Alamat, Gender, dan Kategori.

5. **Daftar Kontak**:
   - **JList**:
     - `kontakList`: Menampilkan nama-nama kontak yang dapat dipilih untuk melakukan aksi edit atau hapus.

## Cara Menjalankan Aplikasi

1. **Prasyarat**:
   - Pastikan Anda memiliki Java Development Kit (JDK) terinstal di sistem Anda.
   - Pastikan Anda memiliki database (seperti MySQL) yang sudah dikonfigurasi dengan tabel `kontak`.

2. **Koneksi Database**:
   - Sesuaikan kredensial koneksi database di dalam metode `connect()` pada kelas `PengelolaanKontakHelper`.

3. **Kompilasi dan Jalankan**:
   - Buka terminal atau command prompt.
   - Navigasi ke direktori tempat file Java disimpan.
   - Kompilasi aplikasi dengan perintah:
     ```bash
     javac AplikasiPengelolaanKontak.java
     ```
   - Jalankan aplikasi dengan perintah:
     ```bash
     java AplikasiPengelolaanKontak
     ```

4. **Menggunakan Aplikasi**:
   - Setelah aplikasi berjalan, Anda dapat mulai menambahkan, mengedit, dan menghapus kontak menggunakan antarmuka yang disediakan.
   - Gunakan fitur pencarian untuk menemukan kontak dengan cepat.
   - Ekspor dan impor data kontak sesuai kebutuhan.

## Pembuat Aplikasi
   Willy Rahman

## Demo

