# AplikasiPertambahanDuaAngka
 
### Identitas: 
Nama: AYU ATUT KHOFIFAH

NPM: 2210010553

### Penjelasan Program:
*Aplikasi Pertambahan Dua Angka* adalah sebuah program berbasis GUI (Graphical User Interface) yang memungkinkan pengguna untuk memasukkan dua angka, lalu melakukan operasi penambahan dan menampilkan hasilnya. Program ini juga dilengkapi dengan beberapa fitur lain seperti menghapus input, validasi input numerik, serta menutup aplikasi. Berikut adalah penjelasan lebih rinci:

### 1. *Deskripsi Program:*
   - *Input Pengguna:* Pengguna memasukkan dua angka di dua buah JTextField.
   - *Fungsi Tombol Tambah:* Saat tombol "Tambah" diklik, program akan menjumlahkan angka yang dimasukkan dan menampilkan hasilnya.
   - *Fungsi Tombol Hapus:* Saat tombol "Hapus" diklik, program akan menghapus angka yang ada di JTextField dan memfokuskan kembali kursor ke JTextField pertama.
   - *Fungsi Tombol Keluar:* Saat tombol "Keluar" diklik, aplikasi akan menutup.

### 2. *Komponen GUI:*
   Aplikasi ini menggunakan beberapa komponen GUI dari Java Swing, yaitu:
   - *JFrame:* Sebagai frame utama dari aplikasi.
   - *JPanel:* Sebagai panel tempat komponen lain diletakkan.
   - *JLabel:* Untuk label yang menandai setiap input.
   - *JTextField:* Sebagai tempat pengguna memasukkan angka.
   - *JButton:* Tombol untuk mengoperasikan penambahan, penghapusan, dan keluar.

### 3. *Logika Program:*
   - Program akan membaca input dari dua JTextField dan memastikan input tersebut adalah angka. Jika input valid, program akan menjumlahkan dua angka tersebut dan menampilkan hasilnya di JLabel atau JOptionPane.
   - Program juga melakukan *validasi input numerik*, memastikan bahwa pengguna hanya memasukkan angka, tidak karakter lain.

### 4. *Events:*
   - *ActionListener:* Digunakan untuk menangani aksi dari tombol "Tambah", "Hapus", dan "Keluar". Saat tombol ditekan, listener ini akan menjalankan aksi yang sesuai (menambah, menghapus, atau keluar).

### 5. *Variasi Tambahan:*
   - *KeyAdapter:* Digunakan pada JTextField untuk membatasi input hanya pada angka. Hal ini mencegah pengguna memasukkan karakter selain angka.
   - *JOptionPane:* Digunakan untuk menampilkan pesan error jika input yang dimasukkan bukan angka.
   - *FocusListener:* Diimplementasikan untuk membersihkan JTextField ketika mendapatkan fokus, memberikan pengalaman pengguna yang lebih baik.

### Keunggulan Program:
### 1. *Super Gampang Dipakai:*
   - Tampilan programnya simpel banget, gak bikin bingung. Tinggal masukin dua angka, pencet tombol, dan hasilnya langsung keluar. Siapa aja bisa langsung paham cara pakainya.

### 2. *Anti Salah Input:*
   - Programnya udah canggih, jadi cuma bisa masukin angka aja. Kalau iseng masukin huruf atau simbol lain, gak bakal diterima. Biar hasilnya akurat terus.

### 3. *Cepat Hapus Input:*
   - Ada tombol "Hapus" buat langsung bersihin angka yang udah dimasukin. Plus, habis dihapus, kursor langsung pindah ke tempat pertama buat input lagi, biar lebih cepat kerjanya.

### 4. *Bersihin Otomatis:*
   - Waktu mau masukin angka baru, kolom inputnya otomatis kehapus kalau diklik. Jadi gak perlu repot-repot hapus manual dulu, tinggal langsung ketik aja.

### 5. *Error Ketahuan Langsung:*
   - Kalau salah masukin, kayak ngetik huruf bukannya angka, bakal muncul pesan error. Jadi langsung tahu dan bisa cepat diperbaiki.

### 6. *Keluar Program Gak Ribet:*
   - Ada tombol "Keluar" buat nutup programnya dengan sekali klik. Gak perlu repot cari cara nutupnya, tinggal pencet aja.

### 7. *Manfaatin Komponen Java yang Efisien:*
   - Program ini udah pake komponen Java Swing yang simpel dan efisien, kayak JFrame, JPanel, JTextField, dll. Ini bikin programnya ringan dan gampang dikembangin lagi kalau mau ditambah fitur.

### 8. *Ringan dan Cepat:*
   - Programnya gak makan banyak sumber daya, jadi jalan cepat dan lancar. Cocok banget buat dipake di komputer spek rendah sekalipun.


### Ini dia Screenshot-nya 

### 1. ![ss an run(2) lat 1 pbo2](https://github.com/user-attachments/assets/6cff0898-ae91-4521-a5c7-2c677c7e1ec5)



### 2. ![ss an run lat 1 pbo2](https://github.com/user-attachments/assets/7aeebc93-9aff-47b8-afa9-91da32548170)
