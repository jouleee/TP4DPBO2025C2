# TP4DPBO2025C2

## Janji
Saya Julian Dwi Satrio dengan NIM 2300484 mengerjakan Tugas Praktikum 5 dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahan-Nya maka saya tidak melakukan kecurangan seperti yang telah di spesifikasikan. Aamiin

## Desain Program  
Aplikasi ini dibuat menggunakan Java Swing untuk mengelola data mahasiswa. Fitur utama meliputi:  
- **Create**: Menambahkan data mahasiswa baru.  
- **Read**: Menampilkan daftar mahasiswa.  
- **Update**: Mengedit data mahasiswa yang sudah ada.  
- **Delete**: Menghapus data mahasiswa.  

## Struktur utama:  
- **`Mahasiswa`**: Kelas model untuk menyimpan informasi mahasiswa (NIM, Nama, Jenis Kelamin, Jalur Masuk).  
- **`MainFrame`**: GUI utama yang menampilkan tabel mahasiswa dan tombol aksi.  
- **`FormMahasiswa`**: Dialog untuk menambah/mengedit data mahasiswa.  

## Desain GUI

![image](https://github.com/user-attachments/assets/1552f013-7795-4f5f-a0db-b200863ebae7)

## Alur Program

1. **Memulai Aplikasi**  
   - Pengguna menjalankan aplikasi.  
   - Jendela utama ditampilkan dengan tabel berisi daftar mahasiswa yang telah dimuat sebelumnya.  
2. **Menambahkan Mahasiswa**  
   - Form input muncul, pengguna mengisi **NIM, Nama, Jenis Kelamin, Jalur Masuk**.
   - Pengguna menekan tombol "Add".  
   - Setelah menekan tombol "Add", data ditambahkan ke dalam list dan ditampilkan di tabel.  
3. **Mengedit Data Mahasiswa**  
   - Pengguna memilih mahasiswa dari tabel dan menekan tombol "Update".  
   - Form edit muncul dengan data yang sudah ada.  
   - Pengguna mengubah informasi yang diperlukan dan menyimpan perubahan.  
   - Data diperbarui dalam list dan tabel direfresh.  
4. **Menghapus Mahasiswa**  
   - Pengguna memilih mahasiswa dari tabel dan menekan tombol "Hapus".  
   - Konfirmasi muncul, jika pengguna menyetujui, data dihapus dari list.  
   - Tabel diperbarui untuk mencerminkan perubahan.  
5. **Menampilkan Data Mahasiswa**  
   - Setiap kali aplikasi dijalankan atau setelah CRUD dilakukan, tabel selalu diperbarui untuk menampilkan data terbaru.
  
## Dokumentasi Program

https://github.com/user-attachments/assets/aff5abe5-0784-459f-903e-cb896afd4f28



