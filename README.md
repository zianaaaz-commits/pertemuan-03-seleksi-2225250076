# Pertemuan 03 Seleksi Python

Nama: Ziana Alfia Zahra
NIM: 2225250076
Kelas: 3A

## Tujuan

Menulis program seleksi `if`, `if-else`, kondisi majemuk, dan `nested if`.

## Cara Menjalankan

Jalankan program dari terminal menggunakan perintah:

```bash
python3 latihan/01_genap_ganjil.py
python3 latihan/02_bandingkan_dua_bilangan.py
python3 latihan/03_kelulusan_bersyarat.py
python3 latihan/04_jenis_segitiga.py
python3 tugas/analisis_persamaan_kuadrat.py
```

## Algoritma Tugas

1. Baca nilai koefisien `a`, `b`, dan `c` sebagai `float`.
2. Periksa apakah `a == 0`.
3. Jika `a == 0`, tampilkan bahwa input bukan persamaan kuadrat.
4. Jika `a` tidak sama dengan 0, hitung diskriminan:
   `D = b ** 2 - 4 * a * c`.
5. Jika `D > 0`, hitung dan tampilkan dua akar real berbeda.
6. Jika `D == 0`, hitung dan tampilkan satu akar real kembar.
7. Jika `D < 0`, tampilkan bahwa tidak ada akar real.
8. Nilai akar ditampilkan dengan dua angka di belakang koma.

## Hasil Pengujian

### Latihan 1 — Genap Ganjil

| Input | Hasil Aktual               | Status   |
| ----- | -------------------------- | -------- |
| 8     | 8 adalah bilangan genap.   | Berhasil |
| 13    | 13 adalah bilangan ganjil. | Berhasil |
| 0     | 0 adalah bilangan genap.   | Berhasil |
| -7    | -7 adalah bilangan ganjil. | Berhasil |

### Latihan 2 — Bandingkan Dua Bilangan

| Input  | Hasil Aktual                  | Status   |
| ------ | ----------------------------- | -------- |
| 7, 4   | Bilangan pertama lebih besar. | Berhasil |
| 2, 9   | Bilangan pertama lebih kecil. | Berhasil |
| 5, 5   | Kedua bilangan sama.          | Berhasil |
| -3, -8 | Bilangan pertama lebih besar. | Berhasil |

### Latihan 3 — Kelulusan Bersyarat

| Nilai | Kehadiran | Hasil Aktual | Status   |
| ----: | --------: | ------------ | -------- |
|    75 |        90 | Lulus        | Berhasil |
|    59 |        90 | Belum lulus  | Berhasil |
|    75 |        79 | Belum lulus  | Berhasil |
|    60 |        80 | Lulus        | Berhasil |

### Latihan 4 — Jenis Segitiga

| Sisi a | Sisi b | Sisi c | Hasil Aktual                         | Status   |
| -----: | -----: | -----: | ------------------------------------ | -------- |
|      3 |      3 |      3 | Segitiga sama sisi                   | Berhasil |
|      5 |      5 |      8 | Segitiga sama kaki                   | Berhasil |
|      3 |      4 |      5 | Segitiga sembarang                   | Berhasil |
|      1 |      2 |      3 | Ketiga sisi tidak membentuk segitiga | Berhasil |

### Tugas 2 — Analisis Persamaan Kuadrat

|  a |  b |  c | Diskriminan | Hasil Aktual                        | Status   |
| -: | -: | -: | ----------: | ----------------------------------- | -------- |
|  1 | -5 |  6 |        1.00 | Dua akar real: x1 = 3.00, x2 = 2.00 | Berhasil |
|  1 |  2 |  1 |        0.00 | Akar real kembar: x = -1.00         | Berhasil |
|  1 |  0 |  1 |       -4.00 | Tidak ada akar real.                | Berhasil |
|  0 |  2 |  3 |           - | Bukan persamaan kuadrat.            | Berhasil |

## Refleksi

Kesalahan logika yang ditemukan adalah kurang memperhatikan kondisi batas, terutama ketika nilai sama dengan batas yang ditentukan. Kesalahan diperbaiki dengan menggunakan operator perbandingan yang sesuai dan menguji nilai batas agar setiap cabang menghasilkan keluaran yang benar.

## Sumber

* RPS Algoritma dan Pemrograman OBE Untirta. Dokumen program studi, Tahun Ajaran 2026/2027 Ganjil.
* Python Tutorial Control Flow Tools
* Visual Studio Code Python Tutorial
* GitHub Docs Creating a New Repository
* GitHub Docs Adding Locally Hosted Code