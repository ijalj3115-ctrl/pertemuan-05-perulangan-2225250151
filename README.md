# Pertemuan 05 Perulangan Python

Nama: Rijal Munawarudin
NIM: 2225250151
Kelas: 3F

## Tujuan

Menggunakan `for` dan `while` untuk menyelesaikan masalah iteratif.

## Cara Menjalankan

```bash
python latihan/01_tabel_perkalian.py
python latihan/02_jumlah_bilangan.py
python latihan/03_validasi_input.py
python latihan/04_hitung_genap.py
python kuis/kuis2_deret_aritmetika.py
```

## Algoritma Kuis 2

1. Meminta pengguna memasukkan suku pertama `a`.
2. Meminta pengguna memasukkan beda `d`.
3. Meminta pengguna memasukkan banyak suku `n`.
4. Melakukan perulangan sebanyak `n` kali.
5. Menghitung setiap suku deret aritmetika menggunakan suku pertama dan beda.
6. Menampilkan setiap suku yang diperoleh.
7. Menjumlahkan semua suku selama proses perulangan.
8. Menampilkan jumlah seluruh suku setelah perulangan selesai.

Rumus suku ke-n:

`Un = a + (n - 1) × d`

## Hasil Pengujian

### Kuis 2 - Deret Aritmetika

| No | Input                   | Keluaran yang Diharapkan           | Keluaran Aktual                    | Status   |
| -- | ----------------------- | ---------------------------------- | ---------------------------------- | -------- |
| 1  | a = 2, d = 3, n = 5     | 2, 5, 8, 11, 14 dan jumlah = 40.00 | 2, 5, 8, 11, 14 dan jumlah = 40.00 | Berhasil |
| 2  | a = 10, d = -2, n = 4   | 10, 8, 6, 4 dan jumlah = 28.00     | 10, 8, 6, 4 dan jumlah = 28.00     | Berhasil |
| 3  | a = 1.5, d = 0.5, n = 3 | 1.5, 2, 2.5 dan jumlah = 6.00      | 1.5, 2, 2.5 dan jumlah = 6.00      | Berhasil |