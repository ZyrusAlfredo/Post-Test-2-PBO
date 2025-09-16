# Post Test 2 PBO - Sistem Jadwal Kegiatan (To-Do List)

# Deskripsi Program
Program Manajemen Jadwal Kegiatan (To-do-list) dibuat untuk membantu pengguna dalam mengatur daftar kegiatan sehari-hari.\
Terdapat beberapa pilihan menu dalam program ini sebagai berikut:\
· Dapat menampilkan jadwal yang sudah dibuat.\
· Dapat menambahkan jadwal baru.\
· Dapat mengedit jadwal berdasarkan ID.\
· Dapat mencari jadwal (fitur searching).\
· Dapat menghapus jadwal berdasarkan ID.\
Dengan program ini, diharapkan pengguna dapat lebih mudah mengorganisir aktivitas harian secara terstruktur.

-----------------------------------------------------------------------------------------------------------

**1. Fitur**\
· Program mampu melakukan operasi lihat jadwal, tambah jadwal, edit jadwal, hapus jadwal, dan cari jadwal.
· Program dapat mengelola dan menyimpan informasi seperti, kegiatan, hari, tanggal, dan skala prioritas.

**2. MVC (Model, View, Control)**\
· Model: Class storage yang akan merepresentasikan struktur data dengan properti dan constructor.\
· View: Class main sebagai tampilan awal antarmuka pengguna beserta input & output.\
· Controller: Class CRUD sebagai logika dan operasi CRUD.\
<img width="395" height="320" alt="image" src="https://github.com/user-attachments/assets/93cd753c-b5cf-4c0f-a024-f22915a3655b" />


**3. Struktur Package**\
· package main: Berisi class main sebagai menu/antarmuka dengan pengguna.\
· package service: Berisi class CRUD sebagai logika dan operasi CRUD.\
· package model: Berisi class storage sebagai tempat menyimpan dan representasi struktur data dengan properti dan constructor.

**4. Access Modifier & Properties**\
· Menggunakan access modifier private untuk properti class beserta getter dan setter.\
· Terdapat 5 properties yaitu: ID, kegiatan, hari, tanggal, dan skala prioritas.

**5. Validasi input**\
Pada program ini terdapat validasi input (Error Handling) seperti akan muncul keterangan, jika tidak sesuai.\
<img width="1229" height="742" alt="Screenshot 2025-09-16 201350" src="https://github.com/user-attachments/assets/c0a556ae-a0bd-47d8-b496-fcacecd715f1" />\
<img width="1209" height="402" alt="Screenshot 2025-09-16 201506" src="https://github.com/user-attachments/assets/0b060685-86ba-48cd-99bb-2b4714280504" />

-----------------------------------------------------------------------------------------------------------

# Alur Program
Terdapat 6 pilihan menu, yaitu:
1. Lihat Jadwal
2. Tambah Jadwal
3. Edit Jadwal
4. Hapus Jadwal
5. Cari Jadwal
6. Keluar
<img width="1299" height="372" alt="image" src="https://github.com/user-attachments/assets/e10823f8-10e6-4f53-89c7-b142f8e79ae7" />

# Penjelasan Menu
**1. Lihat Jadwal**

<img width="1224" height="548" alt="Screenshot 2025-09-16 200933" src="https://github.com/user-attachments/assets/96dbf2c8-7583-44bd-bc47-fd58420307dc" />

Pada menu "Lihat Jadwal", pengguna dapat melihat jadwal kegiatan yang telah pengguna tambahkan.

**2. Tambah Jadwal**

<img width="1216" height="317" alt="Screenshot 2025-09-16 200732" src="https://github.com/user-attachments/assets/3f9248d2-dde4-4537-8cda-593a961405b7" />

Pada menu "Tambah Jadwal", pengguna dapat menambahkan kegiatan kedalam program. Pengguna diminta untuk memasukkan kegiatan, hari, tanggal, dan skala prioritas.

**3. Edit Jadwal**

<img width="1205" height="228" alt="Screenshot 2025-09-16 201021" src="https://github.com/user-attachments/assets/1939993b-4bc4-43df-b905-e422ae897847" />

Pada menu "Edit Jadwal", pengguna dapat mengedit jadwal kegiatan yang sudah ada dengan cara: menginput ID jadwal yang ingin diedit, dengan memasukkan kembali nama kegiatan, hari, tanggal, dan skala prioritas kegiatan tersebut.

**4. Hapus Jadwal**

<img width="1201" height="148" alt="Screenshot 2025-09-16 201048" src="https://github.com/user-attachments/assets/329ccf2e-99b7-4e5d-ad47-d3b397012dcc" />

Pada menu "Hapus Jadwal", pengguna dapat menghapus jadwal kegiatan yang sudah ada dengan cara menginput ID jadwal yang ingin dihapus.

**5. Cari Jadwal (Searching)**

<img width="1187" height="258" alt="Screenshot 2025-09-16 201117" src="https://github.com/user-attachments/assets/286653a6-06fe-4ecc-97e0-233d8f35a087" />

Pada menu "Cari Jadwal" atau biasa disebut dengan searching. Pengguna dapat mencari jadwal kegiatan yang telah ada dengan cara cukup memasukkan keyword yang ingin dicari. Sebagai contoh saya memasukkan keyword "Post Test" lalu muncul kegiatan yang memiliki keyword atau kalimat tersebut.

**6. Keluar**

<img width="1183" height="286" alt="Screenshot 2025-09-16 201135" src="https://github.com/user-attachments/assets/6ab991e2-d053-4dd7-97f5-022768ec7303" />

Pada menu "keluar", pengguna akan keluar dari program.
