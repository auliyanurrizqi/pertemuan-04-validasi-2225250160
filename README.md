# Pertemuan 03 Seleksi Python

**Nama:** Aulia Nurrizqi
**NIM:** 2225250160
**Kelas:** 3A

## Tujuan

Pada pertemuan ini, saya mempelajari dan menerapkan struktur seleksi dalam Python, yaitu:

* `if`
* `if-else`
* kondisi majemuk menggunakan `and`, `or`, dan `not`
* `nested if`
* pengujian program menggunakan beberapa test case
* penggunaan Git dan GitHub untuk menyimpan serta mengelola program

## Struktur Folder

```text
pertemuan-03-seleksi-NIM/
├── .gitignore
├── README.md
├── latihan/
│   ├── 01_genap_ganjil.py
│   ├── 02_bandingkan_dua_bilangan.py
│   ├── 03_kelulusan_bersyarat.py
│   └── 04_jenis_segitiga.py
└── tugas/
    └── analisis_persamaan_kuadrat.py
```

## Daftar Program

| File                            | Keterangan                                                         |
| ------------------------------- | ------------------------------------------------------------------ |
| `01_genap_ganjil.py`            | Menentukan apakah suatu bilangan termasuk genap atau ganjil.       |
| `02_bandingkan_dua_bilangan.py` | Membandingkan dua bilangan menggunakan nested if.                  |
| `03_kelulusan_bersyarat.py`     | Menentukan status kelulusan berdasarkan nilai dan kehadiran.       |
| `04_jenis_segitiga.py`          | Menentukan jenis segitiga berdasarkan panjang ketiga sisinya.      |
| `analisis_persamaan_kuadrat.py` | Menganalisis jenis akar persamaan kuadrat berdasarkan diskriminan. |

## Cara Menjalankan

Program dijalankan melalui Terminal VS Code.

Untuk menjalankan latihan:

```bash
python latihan/01_genap_ganjil.py
python latihan/02_bandingkan_dua_bilangan.py
python latihan/03_kelulusan_bersyarat.py
python latihan/04_jenis_segitiga.py
```

Untuk menjalankan tugas utama:

```bash
python tugas/analisis_persamaan_kuadrat.py
```

Jika komputer menggunakan `python3`, perintah dapat diganti menjadi:

```bash
python3 tugas/analisis_persamaan_kuadrat.py
```

## Algoritma Tugas Utama

Program `analisis_persamaan_kuadrat.py` digunakan untuk menganalisis persamaan:

```text
ax² + bx + c = 0
```

Langkah algoritmanya:

1. Memasukkan nilai koefisien `a`, `b`, dan `c`.
2. Memeriksa apakah `a = 0`.
3. Jika `a = 0`, program menampilkan bahwa input bukan persamaan kuadrat.
4. Jika `a ≠ 0`, program menghitung diskriminan dengan rumus:

```text
D = b² - 4ac
```

5. Jika `D > 0`, program menghitung dan menampilkan dua akar real yang berbeda.
6. Jika `D = 0`, program menghitung dan menampilkan satu akar real kembar.
7. Jika `D < 0`, program menampilkan bahwa persamaan tidak memiliki akar real.

## Rumus

Untuk `D > 0`:

```text
x1 = (-b + √D) / (2a)
x2 = (-b - √D) / (2a)
```

Untuk `D = 0`:

```text
x = -b / (2a)
```

## Hasil Pengujian Tugas

| No |  a |  b |  c | Diskriminan | Hasil yang Diharapkan   | Status   |
| -- | -: | -: | -: | ----------: | ----------------------- | -------- |
| 1  |  1 | -5 |  6 |           1 | Dua akar real: 3 dan 2  | Berhasil |
| 2  |  1 |  2 |  1 |           0 | Akar kembar: -1         | Berhasil |
| 3  |  1 |  0 |  1 |          -4 | Tidak ada akar real     | Berhasil |
| 4  |  0 |  2 |  3 |           - | Bukan persamaan kuadrat | Berhasil |

## Konsep yang Dipelajari

Dari pertemuan ini saya mempelajari bahwa struktur seleksi digunakan agar program dapat mengambil keputusan berdasarkan kondisi tertentu. Saya juga belajar menggunakan operator perbandingan dan operator logika untuk membuat kondisi yang lebih kompleks.

Selain itu, saya belajar bahwa test case penting untuk memastikan setiap cabang kondisi program dapat berjalan dengan benar, terutama pada nilai batas dan kondisi yang berbeda.

## Refleksi

Konsep yang paling saya pahami adalah penggunaan `if-else` karena struktur tersebut digunakan untuk memilih salah satu dari dua kondisi.

Kesalahan yang perlu diperhatikan dalam membuat program seleksi adalah penggunaan operator perbandingan, tanda titik dua, dan indentasi. Kesalahan tersebut dapat menyebabkan program menghasilkan keluaran yang tidak sesuai atau mengalami error.

Pada pertemuan berikutnya, saya ingin lebih memahami cara membuat kondisi yang lebih kompleks dan melakukan debugging pada program Python.

## Sumber

Materi Pertemuan 03 Algoritma dan Pemrograman: Seleksi Python, VS Code, dan GitHub.
