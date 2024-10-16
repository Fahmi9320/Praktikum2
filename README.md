# Praktikum2!
[Cuplikan layar 2024-10-16 172347](https://github.com/user-attachments/assets/d5fd5a42-78d8-452c-bb35-3b374cca6256)
Tujuan Program: Program ini bertujuan untuk menunjukkan bagaimana mendefinisikan class dalam Java, serta menggunakan konsep encapsulation melalui penggunaan setter dan getter untuk mengelola atribut objek.

Class Person:

Program ini mendefinisikan sebuah class bernama Person, yang mewakili seseorang dengan atribut tertentu.
Class ini memiliki tiga atribut:
nama: Menyimpan nama orang.
jenisKelamin: Menyimpan informasi tentang jenis kelamin, misalnya "Laki-laki" atau "Perempuan".
umur: Menyimpan usia orang dalam angka (tipe integer).
Semua atribut ini dideklarasikan dengan modifier akses private, yang berarti atribut tersebut tidak dapat diakses langsung dari luar class. Ini adalah bagian dari prinsip encapsulation, yang bertujuan untuk melindungi data.
Setter dan Getter:

Program ini menyediakan metode setter dan getter untuk masing-masing atribut:
Setter: Metode ini digunakan untuk menetapkan nilai atribut. Dengan menggunakan setter, kita dapat mengubah nilai nama, jenisKelamin, dan umur dari objek Person.
Getter: Metode ini digunakan untuk mengambil atau mengakses nilai atribut. Melalui getter, kita dapat mendapatkan informasi tentang nama, jenis kelamin, dan umur tanpa mengubah nilainya.
Dengan cara ini, akses ke atribut dikelola dengan baik, memungkinkan validasi atau pengolahan tambahan saat data diubah atau diambil.
Method main:

Method ini adalah titik awal eksekusi program. Dalam method ini, kita membuat dua objek dari class Person, yaitu anton dan riko.
Objek anton dan riko digunakan untuk menyimpan informasi yang berbeda, masing-masing dengan nilai yang ditetapkan melalui metode setter.
Setelah nilai-nilai tersebut diatur, program menggunakan metode getter untuk mencetak informasi tentang kedua objek ke konsol. Dengan ini, pengguna dapat melihat bagaimana data disimpan dan diakses dalam objek Person.
Output Program:

Ketika program dijalankan, informasi tentang objek anton dan riko, termasuk nama, jenis kelamin, dan umur, akan ditampilkan di konsol. Ini memberikan gambaran yang jelas tentang bagaimana class Person bekerja dan bagaimana objek dari class tersebut dapat digunakan untuk menyimpan dan mengambil data.
