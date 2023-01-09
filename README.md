# PROJEK-UAS
# NAMA : MOHAMAD HEGAR SUKMANA WIBOWO
#  NIM : 312210332
# KELAS : TI.22.A3
# **Buat paket dan modul dengan struktur**

![SS22](https://user-images.githubusercontent.com/115518483/211165403-865e59e0-1a87-4b64-a65d-9477f670cbdf.png)


- Untuk membuat Package Modul kita buka aplikasi **PyCharm** :

![SS1](https://user-images.githubusercontent.com/115518483/211165441-226f273b-77c6-48e6-a911-e17545b51e6d.png)


- Pilih `New Project` Lalu simpan project sesuai Location Directory dan beri nama folder :

![SS2](https://user-images.githubusercontent.com/115518483/211165498-8101d5f6-9411-434e-99d9-bf3874107a2d.png)


- Kemudian Pilih New > Python Package :

       " -> Kita buat Nama Model dan View "

![SS3](https://user-images.githubusercontent.com/115518483/211165518-f79cfc90-4063-45a0-bf0a-7bf542428272.png)


- Tampilan folder Package Model dan View yang terdapat file_init_.py

![SS4](https://user-images.githubusercontent.com/115518483/211165532-d08f2f3f-edb8-4a94-8d10-f220569c33ec.png)


- Kemudian kita buat nama program Python dengan Klik Folder Model > pilih New >Python File dengan nama : daftar_nilai.py

![SS5](https://user-images.githubusercontent.com/115518483/211165547-85b91563-6cc8-4c1e-8043-e3f9834c8919.png)


- Lalu kita buat nama program Python dengan Klik Folder view > pilih New >Python File dengan nama : input_nilai.py dan view_nilai.py

![SS6](https://user-images.githubusercontent.com/115518483/211165559-5054340b-b426-4c64-a757-05653bd956e4.png)


- Nama program python sudah kita buat :

![SS7](https://user-images.githubusercontent.com/115518483/211165591-ef1c9b80-f1b7-463a-9d46-e7b59345760a.png)


# **Buat sintaks program python** 

**Membuat kode program : `daftar_nilai.py` **

![SS8](https://user-images.githubusercontent.com/115518483/211165605-22efedeb-fb34-4ecb-bf7e-b8b3067c63a3.png)
![SS8,1](https://user-images.githubusercontent.com/115518483/211165616-d377ced9-89bd-46ae-98d3-ef5c60cc300c.png)


**Penjelasan :**
- Disini kita menggunakan kamus ya untuk menyimpan inputan data mahasiswa<br>
- Def tambahkan : Dibagian ini kita gunakan print untuk penulisan bagian input data mahasiswa nanti agar terlihat rapih<br>
- Def hapus : <br>
- Disini kita buat inputan yang menginput nama<br>
    - Gunanya untuk menghapus data mahasiswa dari nama mahasiswa itu sendiri<br>
    - Kita gunakan del untuk fungsi menghapus datanya<br>
    - (Jika)Jika mahasiswa tersebut ada maka data mahasiswa tersebut akan terhapus<br>
    - (Else)Jika nama mahasiswa tersebut tidak ada maka datanya tidak akan ditemukan<br>
- Def ubah<br>
Penjelasan:<br>
    - Disini kita hampir sama dengan yang hapus, kita gunakan inputan nama untuk mengubah NIM, Nilai Tugas, Ujian Tengah Semester(UTS), ataupun Ujian Akhir Semester(UAS)<br>
    - Lalu setelah kita memasukkan nama maka dictionary akan mengeksekusi program menggunakan keys untuk mencari data dari nama mahasiswa tersebut<br>
    - (Jika)Jika nama mahasiswa tersebut ketemu atau ada didalam data maka program akan masuk ke inputan NIM, Nilai Tugas, Nilai UTS, dan Nilai UAS yang baru<br>
    - (Else)Jika nama mahasiswa tersebut tidak ada didalam data maka program akan memunculkan tulisan atau perintah bahwa data mahasiswa tidak ada<br>
- Def cari<br>
Penjelasan:<br>
    - Fungsinya sama dengan tambahkan Def<br>    

**Membuat kode program `input_nilai.py` **

![SS9](https://user-images.githubusercontent.com/115518483/211165626-d4b0a357-d2a0-4adb-bdb6-e3a548901bba.png)


Penjelasan:<br>
- Dari dan impor<br>
Penjelasan:<br>
    - From digunakan untuk memanggil package temporary import untuk tujuan yang kita pilih yaitu modul daftar_nilai<br>
    - Lalu kita gunakan import data_mahasiswa itu gunanya agar saat kita menginputkan data atau setiap kali kita menambah data maka data mahasiswa secara otomatis akan masuk ke dalam dictionary meskipun berbeda atau paket terpisah dan juga modulnya<br>

  - Def tambah data<br>
Penjelasan:<br>
    - Disini kita buat inputan karena tadi kita sudah membuat kata - kata outputnya kali ini kita cukup membuat inputan data mahasiswanya saja<br>
    - Jangan lupa gunakan penambahan untuk menghitunghasil total atau rata- ratanya<br>

**Membuat kode program `view_nilai.py` **

![SS10](https://user-images.githubusercontent.com/115518483/211165640-5deee0d4-3718-4cdc-9ba2-4f0e3cd38edd.png)
![SS10,1](https://user-images.githubusercontent.com/115518483/211165653-2c495de5-8d5b-4ae6-9d84-390befbdfbab.png)


Penjelasan:<br>
- Dari dan impor<br>
Penjelasan:<br>
    - Fungsinya sama saja dengan yang ada dibagian Input_Nilai<br>

  - Def tampil<br>
Penjelasan:<br>
    - Disini kita buat sebuah tabel untuk menampilkan data - data dan nama - nama mahasiswa didalam kamus<br>
    - (Jika)Jika terdapat data maka data dan nama mahasiswa tersebut akan muncul<br>
    - Disini kita menggunakan for untuk melakukan perulangan nomor urut<br>
    - (Else)Jika kita belum menginputkan data sama sekali maka akan muncul tulisan "tidak ada data"<br>

  - Def mencari data<br>
Penjelasan:<br>
    - Tadi kita sudah buat print sama seperti dibagian Input_Nilai<br>
    - Kita akan langsung membuat inputan dengan format nama untuk mencari data dari mahasiswa yang sedang kita cari<br>
    - (If)Jika data mahasiswa yang dicari ada didalam kamus maka data baik Nama, NIM, Nilai Tugas, Nilai UTS, dan Nilai UAS akan muncul<br>
    - (Else)Jika data mahasiswa yang dicari tidak ada didalam kamus maka akan muncul tulisan "datanya tidak ada"<br>

**Membuat kode program :   `main.py` **
![SS11](https://user-images.githubusercontent.com/115518483/211165676-8d516ff2-85e8-43cc-af1c-9d2b85021e55.png)


- Dari dan impor<br>
Penjelasan:<br>
    - Sama seperti sebelumnya hanya disini saja sedikit berbeda<br>
    - Dari sini kita tulis package.modulnya lalu import fungsi(def) tadi<br>
    - Karena dibagian utama ini kita akan menggunakan atau membuat menu pilihan sintaks<br>

  - Sementara Benar<br>
Penjelasan:<br>
    - Kita gunakan print untuk membuat pilihan menunya<br>
    - Lalu kita buat inputan untuk memilih menu nanti ketika program dijalankan<br>
    - (If dan Elif)Kita gunakan karena kita akan membuat cabang pilihan yang banyak<br>
    - Lalu dibawahnya kita tambahkan juga fungsi - fungsi yang sudah kita buat tadi<br>
    - Pada perintah ke 6 kita gunakan break untuk keluar dari program yang kita jalankan<br>
    - (Else)Jika kita tidak memilih salah satu menu tersebut maka akan muncul peringatan "pilih menu yang tersedia diatas"<br>

# **Menjalankan program python** 

- Untuk menjalankan program kita klik : Run > `main.py`

* Pilih Menu Nomor : 1. Tambah

![SS12](https://user-images.githubusercontent.com/115518483/211165724-2a69efc1-73fd-4fbd-b445-a140b574b893.png)


* Pilih Menu Nomor : 2. Tampil

![SS13](https://user-images.githubusercontent.com/115518483/211165734-e9fbb2b8-9b7d-41a1-a249-4d6c1c9e58ab.png)


* Untuk menambah data lagi, pilih Menu Nomor : 1. Tambah

![SS14](https://user-images.githubusercontent.com/115518483/211165752-1228f95c-305d-4621-9536-5b0eac61e127.png)


* Untuk menampilkan data yang kita tambah,Pilih Menu Nomor : 2. Tampil

![SS15](https://user-images.githubusercontent.com/115518483/211165767-6a7e1e87-cf2c-44d1-9747-602cc6044ddf.png)


* Pilih Menu Nomor : 3. Hapus

![SS16](https://user-images.githubusercontent.com/115518483/211165801-48bdffd4-add2-46a8-aa92-5035073468c6.png)


* Untuk menampilkan data yang kami hapus,Pilih Menu Nomor : 2. Tampil

![SS17](https://user-images.githubusercontent.com/115518483/211165827-ed65ffe3-bb05-49c1-aff0-a4e2dd4811b0.png)


* Pilih Menu Nomor : 4.Ubah

![SS18](https://user-images.githubusercontent.com/115518483/211165839-38565cc3-fb0a-4205-8b7c-b7181c418c2c.png)


* Untuk menampilkan data yang kami ubah,Pilih Menu Nomor : 2. Tampil

![SS19](https://user-images.githubusercontent.com/115518483/211165856-92cdecb5-635f-440e-8837-0aba701ac954.png)


* Pilih Menu Nomor : 5. Cari
* > Kemudian ketik Nama Mahasiswa

![SS20](https://user-images.githubusercontent.com/115518483/211165876-ea43a429-0dee-4db5-a0a5-86341d35d2f1.png)


* Pilih Menu Nomor : 6. Keluar dari program

![SS21](https://user-images.githubusercontent.com/115518483/211165907-ba86c62c-3b69-4f85-afb2-6b5ef2d46b98.png)


- Untuk melihat pembahasan silahkan klik link di bawah ini:

1. https://youtu.be/niAi-TKiKug

Cukup sekian Penjelasan dari saya.

   **TERIMA KASIH**
