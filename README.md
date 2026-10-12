
# Pertemuan 07 Fungsi Python

Nama: [Nama Lengkap]
NIM: [NIM]
Kelas: [Kelas]

## Tujuan

Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular.

## Cara Menjalankan

Pastikan Python sudah terpasang dan terminal VS Code berada di folder utama proyek.

Untuk menjalankan setiap latihan, gunakan perintah berikut:

```bash
python latihan/01_salam.py
python latihan/02_luas_persegi_panjang.py
python latihan/03_jumlah_n.py
python latihan/04_statistik_sederhana.py
python latihan/05_scope.py
```

Untuk menjalankan program praktik utilitas matematika:

```bash
python praktik/utilitas_matematika.py
```

## Struktur Fungsi

1. **salam(nama)**  
   Menampilkan salam berdasarkan nama yang diberikan melalui parameter.

2. **luas_persegi_panjang(p, l)**  
   Menghitung luas persegi panjang dan mengembalikan hasil perkalian panjang dan lebar melalui `return`.

3. **jumlah_n(n)**  
   Menghitung jumlah bilangan dari 1 sampai n menggunakan perulangan dan mengembalikan hasilnya.

4. **statistik(data)**  
   Menghitung nilai minimum, maksimum, dan rata-rata dari kumpulan data, kemudian mengembalikan ketiga nilai tersebut.

5. **demo(x)**  
   Menunjukkan penggunaan parameter dan variabel lokal serta mengembalikan hasil penjumlahan x dengan 5.

6. **luas_segitiga(a, t)**  
   Menghitung luas segitiga berdasarkan alas dan tinggi, lalu mengembalikan hasilnya.

7. **faktorial(n)**  
   Menghitung faktorial bilangan nonnegatif menggunakan perulangan dan mengembalikan hasilnya.

8. **tampilkan_menu()**  
   Menampilkan pilihan operasi matematika yang tersedia pada program praktik.

## Hasil Pengujian

| Program/Fungsi | Input | Hasil yang Diharapkan | Status |
|---|---|---|---|
| salam | Alya | Halo, Alya. Selamat belajar Python! | Berhasil |
| luas_persegi_panjang | p=8, l=5 | 40 | Berhasil |
| jumlah_n | n=10 | 55 | Berhasil |
| statistik | [70, 80, 65, 90, 75] | Min=65, Maks=90, Rata-rata=76.0 | Berhasil |
| demo | x=20, x global=10 | Di dalam fungsi: 20, 25; di luar fungsi: 10, 25 | Berhasil |
| luas_segitiga | a=10, t=6 | 30.0 | Berhasil |
| faktorial | n=5 | 120 | Berhasil |
| faktorial | n=0 | 1 | Berhasil |

## Refleksi

Setelah mengerjakan latihan Pertemuan 07, saya memahami bahwa fungsi dapat membuat program lebih terstruktur dan mengurangi pengulangan kode. Parameter digunakan untuk menerima data, sedangkan `return` digunakan untuk mengembalikan hasil agar dapat dipakai dalam proses berikutnya. Saya juga memahami perbedaan variabel lokal dan global serta pentingnya melakukan pengujian untuk memastikan program berjalan dengan benar.
