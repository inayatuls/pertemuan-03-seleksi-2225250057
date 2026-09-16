# Pertemuan 03 Seleksi Python

**Nama :** Inayatul Sholihah  
**NIM :** 2225250057  
**Kelas :** 3A  

## Tujuan

Menulis program menggunakan seleksi if, if-else, kondisi majemuk, dan nested if.

## Cara Menjalankan

Jalankan program dengan perintah:

    python3 tugas/analisis_persamaan_kuadrat.py

## Algoritma Tugas

1. Meminta pengguna memasukkan nilai koefisien a, b, dan c.
2. Memeriksa apakah nilainya sama dengan 0.
3. Jika sama dengan 0, program menampilkan bahwa input bukan persamaan kuadrat.
4. Jika a tidak sama dengan 0, program menghitung nilai diskriminan.
5. Jika diskriminan lebih besar dari 0, program menghitung dan menampilkan dua akar real yang berbeda.
6. Jika diskriminan sama dengan 0, program menghitung dan menampilkan satu akar kembar nyata.
7. Jika diskriminan kurang dari 0, program menampilkan bahwa tidak ada akar nyata.

## Hasil Pengujian

| No. | Masukan (a, b, c) | Keluaran yang Diharapkan | Keluaran Aktual | Status |
|---|---|---|---|---|
| 1 | 1, -5, 6 | Dua akar real: 3 dan 2 | Diskriminan = 1,00, x1 = 3,00 dan x2 = 2,00 | Berhasil |
| 2 | 1, 2, 1 | Akar kembar: -1 | Diskriminan = 0,00, x = -1,00 | Berhasil |
| 3 | 1, 0, 1 | Tidak ada akar asli | Diskriminan = -4,00, tidak ada akar real | Berhasil |
| 4 | 0, 2, 3 | Bukan persamaan | Bukan persamaan kuadrat. | Berhasil |

## Refleksi

Kesalahan logika yang ditemukan adalah tidak memeriksa nilai a terlebih dahulu sebelum menghitung diskriminan dan akar. Jika a bernilai 0, input tersebut bukan persamaan kuadrat dan dapat menyebabkan kesalahan saat menghitung akar.

Kesalahan tersebut diperbaiki dengan memeriksa kondisi a == 0 terlebih dahulu sebelum menghitung diskriminan dan akar.

## Tiket Keluar

**Satu perbedaan penting antara if dan if-else adalah:**

if hanya menjalankan blok kode ketika kondisi bernilai benar, sedangkan if-else menyediakan blok alternatif ketika kondisi bernilai salah.

**Kesalahan logika yang paling mudah saya lakukan adalah:**

Salah menentukan perbandingan operator, terutama pada kondisi nilai batas seperti minimal dan maksimal.

**Test case yang membantu saya menemukan kesalahan adalah:**

Input yang tepat pada nilai batas, seperti nilai 60 pada syarat izin, karena dapat memastikan operator yang digunakan sudah benar.

## Kuis Formatif

1. Apa tipe hasil ekspresi 7 >= 5?

   **Jawaban:** Boolean (True).

2. Operator apa yang digunakan untuk menguji kesamaan dua nilai?

   **Jawaban:** ==.

3. Apa perbedaan utama = dan ==?

   **Jawaban:** = digunakan untuk memberikan nilai, sedangkan == digunakan untuk membandingkan dua nilai.

4. Jika aturan berbunyi minimal 75, apakah operator > 75 sudah tepat? Jelaskan.

   **Jawaban:** Tidak tepat. Jika aturan minimal 75, nilai 75 juga harus memenuhi syarat. Operator yang tepat adalah >= 75.

5. Kapan blok else dijalankan?

   **Jawaban:** Ketika kondisi if bernilai salah.

6. Berapa sisa 14 % 2 dan keputusan apa yang dapat dibuat dari hasil itu?

   **Jawaban:** Sisanya adalah 0. Karena sisanya 0, bilangan 14 merupakan bilangan genap.

7. Untuk syarat nilai minimal 60 dan hadir minimal 80, operator logika apa yang digunakan?

   **Jawaban:** and.

8. Mengapa nested if sesuai ketika pertanyaan kedua hanya relevan setelah syarat pertama terpenuhi?

   **Jawaban:** Karena kondisi kedua hanya diperiksa setelah kondisi pertama terpenuhi.

9. Sebutkan tiga input untuk menguji batas kelulusan 60.

   **Jawaban:** 59, 60, dan 61.

10. Perintah apa yang mengirim commit lokal ke remote setelah push pertama berhasil?

    **Jawaban:** git push.

## Penilaian Diri

Saya sudah memahami penggunaan if, if-else, kondisi majemuk, dan nested if dalam Python. Saya juga sudah melakukan pengujian pada beberapa kondisi untuk memastikan program berjalan sesuai dengan yang diharapkan.
