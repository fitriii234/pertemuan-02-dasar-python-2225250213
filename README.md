# Pertemuan 02 - Dasar Python

## Identitas
- Nama: [Siti Fitriani]
- NIM: [2225250213]
- Kelas: [3B]

## Tujuan
Mempelajari variabel, konstanta, tipe data, input-output, operator, serta menjalankan dan menguji program Python melalui VS Code.

## Daftar Berkas
- `latihan/01_biodata.py` — menerima biodata dan menghitung perkiraan umur.
- `latihan/02_persegi_panjang.py` — menghitung luas dan keliling persegi panjang.
- `latihan/03_konversi_suhu.py` — mengubah Celsius menjadi Fahrenheit dan Kelvin.
- `latihan/04_nilai_akhir.py` — menghitung nilai akhir berbobot.
- `tugas/kalkulator_koordinat.py` — menghitung dx, dy, jarak Euclidean, dan titik tengah dua titik.

## Cara Menjalankan
Dari terminal pada folder utama:
```bash
python latihan/01_biodata.py
python latihan/02_persegi_panjang.py
python latihan/03_konversi_suhu.py
python latihan/04_nilai_akhir.py
python tugas/kalkulator_koordinat.py
```
Jika sistem menggunakan `python3`, gunakan `python3` sebagai pengganti `python`.

## Hasil Pengujian Tugas Utama

| Kasus | Titik A | Titik B | Jarak | Titik Tengah |
|---|---|---|---:|---|
| 1 | (0, 0) | (3, 4) | 5.00 | (1.50, 2.00) |
| 2 | (-2, 1) | (4, 1) | 6.00 | (1.00, 1.00) |
| 3 | (2.5, -1) | (2.5, 3) | 4.00 | (2.50, 1.00) |

## Refleksi
Konsep yang paling saya pahami adalah penggunaan variabel, input, konversi tipe data, dan operator karena semuanya digunakan langsung dalam program.

Kesalahan yang saya temukan adalah input angka masih bertipe `str`, sehingga harus dikonversi menggunakan `int()` atau `float()` sebelum digunakan dalam perhitungan.

Pada pertemuan berikutnya saya ingin lebih memahami penggunaan percabangan dan validasi data.

## Sumber
- Bahan Ajar Algoritma dan Pemrograman Pertemuan 02, Dr. Aan Hendrayana, S.Si., M.Pd.
- Python Software Foundation — Python Tutorial.
- Visual Studio Code — Getting Started with Python in VS Code.
- GitHub Docs — Creating a New Repository dan Adding Locally Hosted Code to GitHub.
