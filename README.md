# Praktikum-pertemuan-12
Buat program sederhana dengan mengaplikasikan penggunaan class. Buatlah class untuk menampilkan daftar nilai mahasiswan dengan ketentuan : 
method tambah() untuk menambah data 
method tampilkan() untuk menampilkan data 
method hapus(nama) untuk menghapus data berdasarkan nama
method ubah(nama) untuk mengubah data berdasarkan nama

Buat diagram class, flowchart,dan penjelasan programnya pada READMe.md. 
Commit dan push repository ke github

#PROGRAM PRAKTIKUM 
![Program 1](https://github.com/user-attachments/assets/d0e502e4-fc65-49cc-a253-a077a4b172b3)

![Program 2](https://github.com/user-attachments/assets/3f0415c2-5444-46bd-83ea-0484b37f6787)

#HASIL PROGRAM PRAKTIKUM
![Hasil program](https://github.com/user-attachments/assets/291f3f30-481c-4433-869a-1bd9be7d6c58)

#PENJELASAN PROGRAM


    Class DaftarNilaiMahasiswa:
        Class ini berfungsi sebagai wadah untuk menyimpan dan mengelola data mahasiswa. Di dalam class ini, terdapat beberapa method yang memungkinkan kita untuk melakukan operasi pada daftar nilai mahasiswa.

    Atribut daftar_nilai:
        Atribut ini adalah list yang menyimpan data mahasiswa dalam bentuk dictionary. Setiap dictionary berisi dua kunci: nama dan nilai, yang masing-masing menyimpan nama mahasiswa dan nilai mereka.

Method dalam Class

    __init__(self):
        Ini adalah constructor yang dipanggil saat kita membuat instance dari class DaftarNilaiMahasiswa. Di sini, kita menginisialisasi atribut daftar_nilai sebagai list kosong.

    tambah(self, nama, nilai):
        Method ini digunakan untuk menambahkan data mahasiswa ke dalam daftar.
        Parameter:
            nama: Nama mahasiswa yang akan ditambahkan.
            nilai: Nilai mahasiswa yang akan ditambahkan.
        Proses:
            Data mahasiswa ditambahkan ke dalam list daftar_nilai sebagai dictionary.
            Pesan konfirmasi ditampilkan setelah data berhasil ditambahkan.

    tampilkan(self):
        Method ini digunakan untuk menampilkan semua data mahasiswa yang ada dalam daftar.
        Proses:
            Jika daftar kosong, program akan menampilkan pesan bahwa daftar kosong.
            Jika ada data, program akan mencetak setiap mahasiswa beserta nilainya dengan format yang teratur.

    hapus(self, nama):
        Method ini digunakan untuk menghapus data mahasiswa berdasarkan nama yang diberikan.
        Parameter:
            nama: Nama mahasiswa yang ingin dihapus.
        Proses:
            Program mencari mahasiswa dengan nama yang sesuai dalam daftar.
            Jika ditemukan, data mahasiswa dihapus dari list dan pesan konfirmasi ditampilkan.
            Jika tidak ditemukan, program akan menampilkan pesan bahwa data tidak ditemukan.

    ubah(self, nama, nilai_baru):
        Method ini digunakan untuk mengubah nilai mahasiswa berdasarkan nama yang diberikan.
        Parameter:
            nama: Nama mahasiswa yang nilainya ingin diubah.
            nilai_baru: Nilai baru yang akan diberikan kepada mahasiswa.
        Proses:
            Program mencari mahasiswa dengan nama yang sesuai dalam daftar.
            Jika ditemukan, nilai mahasiswa diubah menjadi nilai_baru dan pesan konfirmasi ditampilkan.
            Jika tidak ditemukan, program akan menampilkan pesan bahwa data tidak ditemukan.
            
#DIAGRAM CLASS

![image](https://github.com/user-attachments/assets/0db2bf86-7fb1-4181-b8c6-b8c9eab5f36b)




#FLOWCHART

![image](https://github.com/user-attachments/assets/b0cd7eb4-e48c-49b7-89a8-f74c01d17666)


