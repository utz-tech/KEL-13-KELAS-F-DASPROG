KALKULATOR SEDERHANA ELEKTRO & KONVERSI BILANGAN

Bahasa Pemrograman: C

---

1. Pendahuluan

Perkembangan teknologi di bidang elektro dan sistem digital menuntut kemampuan dalam melakukan perhitungan dasar secara cepat dan akurat. Oleh karena itu, diperlukan suatu program sederhana yang mampu membantu proses perhitungan kelistrikan serta konversi bilangan digital.

Proyek ini dibuat dalam bentuk program berbasis bahasa C yang menyediakan beberapa fitur perhitungan dasar elektro dan konversi bilangan. Program dirancang dengan tampilan menu interaktif berbasis teks (console) sehingga mudah digunakan dan dipahami.



 2. Tujuan Program

Tujuan dari pembuatan program ini adalah sebagai berikut:

1. Membantu melakukan perhitungan dasar kelistrikan.
2. Memahami penerapan bahasa C dalam program berbasis menu.
3. Melatih penggunaan fungsi, perulangan, dan percabangan.
4. Membantu proses pembelajaran sistem bilangan digital.

---

 3. Ruang Lingkup Program

Ruang lingkup dari program ini meliputi:

1. Perhitungan Hukum Ohm.
2. Perhitungan daya listrik.
3. Perhitungan hambatan resistor seri dan paralel.
4. Konversi bilangan desimal, biner, oktal, dan heksadesimal.
5. Antarmuka berbasis teks (console).

---

 4. Dasar Teori

4.1 Hukum Ohm

Hukum Ohm menyatakan hubungan antara tegangan (V), arus (I), dan hambatan (R) yang dirumuskan sebagai:

[ V = I \times R ]
 4.2 Daya Listrik

Daya listrik merupakan besarnya energi listrik yang digunakan per satuan waktu dan dapat dihitung dengan rumus:

[ P = V \times I ]

 4.3 Resistor Seri

Hambatan total pada rangkaian resistor seri merupakan penjumlahan dari seluruh hambatan penyusunnya, yaitu:

[ R_{total} = R_1 + R_2 + \cdots + R_n ]

4.4 Resistor Paralel

Hambatan total pada rangkaian resistor paralel diperoleh dari jumlah kebalikan hambatan masing-masing resistor, yaitu:

[ \frac{1}{R_{total}} = \frac{1}{R_1} + \frac{1}{R_2} + \cdots + \frac{1}{R_n} ]

 4.5 Sistem Bilangan

Program ini mendukung konversi antar sistem bilangan yang umum digunakan dalam sistem digital, yaitu:

* Desimal
* Biner
* Oktal
* Heksadesimal

---

 5. Perancangan Program

 5.1 Struktur Program

Program dirancang menggunakan beberapa fungsi agar struktur kode lebih rapi dan mudah dipahami. Seluruh fungsi yang dijelaskan pada laporan ini 100% disesuaikan dengan implementasi pada source code**. Fungsi-fungsi utama yang digunakan antara lain:

* `tekanEnter()` : Memberikan jeda agar pengguna dapat membaca hasil sebelum kembali ke menu.
* `hukumOhm()` : Menghitung tegangan, arus, atau hambatan berdasarkan Hukum Ohm.
* `daya()` : Menghitung daya listrik berdasarkan tegangan dan arus.
* `resistorSeri()` : Menghitung total hambatan resistor yang disusun secara seri.
* `resistorParalel()` : Menghitung total hambatan resistor yang disusun secara paralel.
* `desimalKonversi()` : Mengonversi bilangan desimal ke biner, oktal, dan heksadesimal.
* `binerKeDesimal()` : Mengonversi bilangan biner ke desimal.
* `oktalKeDesimal()` : Mengonversi bilangan oktal ke desimal.
* `heksaKeDesimal()` : Mengonversi bilangan heksadesimal ke desimal.
* `main()` : Mengatur alur utama program dan navigasi menu menggunakan struktur perulangan `do-while`.

---

6. Implementasi Program

Program diimplementasikan menggunakan bahasa C dan dijalankan melalui terminal atau console. Menu utama ditampilkan secara berulang menggunakan struktur perulangan `do-while`, sehingga menu akan terus muncul sampai pengguna memilih menu keluar. Pemilihan menu diatur menggunakan struktur percabangan `switch-case`.

---

7. Cara Menjalankan Program

 7.1 Kompilasi Program

```
gcc program.c -o program
```

7.2 Menjalankan Program

```
./program
```

---

8. Hasil dan Pembahasan

Berdasarkan hasil pengujian, program berhasil:

1. Menghitung nilai tegangan, daya, dan hambatan dengan benar.
2. Melakukan konversi sistem bilangan secara akurat.
3. Menampilkan menu interaktif yang mudah digunakan.

Program ini dapat dimanfaatkan sebagai alat bantu praktikum elektro serta media pembelajaran dasar bahasa C.

---

9. Kelebihan dan Kekurangan

 9.1 Kelebihan

1. Menu sederhana dan mudah digunakan.
2. Struktur program rapi dengan penggunaan fungsi.
3. Cocok untuk pembelajaran dasar elektro dan pemrograman.

 9.2 Kekurangan

1. Antarmuka masih berbasis teks.
2. Program belum mendukung validasi input secara menyeluruh.
3. Tampilan masih terbatas pada terminal/console.

---

 10. Kesimpulan

Berdasarkan hasil pengujian dan pembahasan, dapat disimpulkan bahwa program kalkulator elektro dan konversi bilangan ini telah berjalan dengan baik dan sesuai dengan tujuan yang diharapkan. Program ini membantu pemahaman konsep dasar kelistrikan serta penerapan bahasa C dalam pemrograman terstruktur.

---

 11. Saran Pengembangan

Adapun saran untuk pengembangan program selanjutnya antara lain:

1. Menambahkan validasi input agar lebih aman digunakan.
2. Mengembangkan antarmuka berbasis GUI.
3. Menambahkan fitur perhitungan kelistrikan lainnya.

---

 12. Penutup

Demikian laporan proyek ini disusun sebagai dokumentasi program dan bahan pembelajaran. Diharapkan program ini dapat memberikan manfaat bagi pengguna maupun pengembang selanjutnya.
