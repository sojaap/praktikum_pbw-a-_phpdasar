# Praktikum 1: Aplikasi PHP Dasar - Form Pendaftaran Event

Aplikasi ini dibuat untuk memenuhi tugas praktikum dasar PHP. Aplikasi ini merupakan form pendaftaran sederhana untuk sebuah event fiktif.

## Deskripsi & Fitur
Aplikasi ini mencakup implementasi dari beberapa konsep dasar PHP, yaitu:
- **Variabel, Global Variabel, dan Konstanta**: Untuk menyimpan data dan konfigurasi.
- **Fungsi**: Digunakan untuk modularisasi kode, khususnya untuk validasi.
- **Penanganan Form (POST)**: Menerima dan memproses data yang dikirim dari form HTML.
- **Validasi dengan Regex**: Memastikan format input email dan tanggal lahir (DD-MM-YYYY) sudah benar.
- **Operasi File**: Menyimpan setiap pendaftar yang valid ke dalam file `pendaftar.txt`.
- **Menampilkan Data**: Membaca data dari `pendaftar.txt` dan menampilkannya dalam bentuk tabel.

## Tampilan Aplikasi

**Tampilan Awal Form**
- *Tampilan awal form dimana form belum diisi dengan data pendaftar*
<img width="1280" height="800" alt="tampilan awal form" src="https://github.com/user-attachments/assets/954286b0-bfad-44a1-9607-aafc5341d3ec" />


**Tampilan Setelah Pendaftaran Berhasil**
- *Tampilan form berhasil mendaftarkan Soja Purnamasari*
<img width="1280" height="800" alt="tampilan insert form" src="https://github.com/user-attachments/assets/5920dd0f-19e9-492f-acc7-ea988e74d0ee" />


 **Contoh Pesan Error Validasi**
- *Error saat validasi tanggal lahir yang tidak sesuai dengan format*
<img width="1280" height="800" alt="tampilan error form1" src="https://github.com/user-attachments/assets/d434bdb2-ea11-46d6-93fb-34b659d59159" />


