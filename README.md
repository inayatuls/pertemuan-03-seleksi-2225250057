Pertemuan 03 Seleksi Python

Nama : Inayatul Sholihah
NIM : 2225250057
Kelas : 3A

Tujuan
Menulis program menggunakan seleksi if, if-else, kondisi majemuk, dan nested if.

Cara Menjalankan
Jalankan program dengan perintah:

python3 tugas/analisis_persamaan_kuadrat.py

Algoritma Tugas
Meminta pengguna memasukkan nilai koefisien a, b, dan c.
Memeriksa apakah nilainya sama dengan 0.
Jika sama dengan 0, program menampilkan bahwa input bukan persamaan kuadrat.
Jika a tidak sama dengan 0, program menghitung nilai diskriminan.
Jika diskriminan lebih besar dari 0, program menghitung dan menampilkan dua akar real yang berbeda.
Jika diskriminan sama dengan 0, program menghitung dan menampilkan satu akar kembar nyata.
Jika diskriminan kurang dari 0, program menampilkan bahwa tidak ada akar nyata.

Hasil Pengujian

TIDAK	Masukan (a, b, c)	Keluaran yang Diharapkan	Keluaran Aktual	Status
1	1, -5, 6	Dua akar real: 3 dan 2	Diskriminan = 1,00, x1 = 3,00 dan x2 = 2,00	Berhasil
2	1, 2, 1	Akar kembar: -1	Diskriminan = 0,00, x = -1,00	Berhasil
3	1, 0, 1	Tidak ada akar asli	Diskriminan = -4.00, tidak ada akar real	Berhasil
4	0, 2, 3	Bukan persamaan	Bukan persamaan kurifikasi.	Berhasil

Refleksi
Kesalahan logika yang ditemukan adalah tidak memeriksa nilai a terlebih dahulu sebelum menghitung diskriminan dan akar. Jika a bernilai 0, input tersebut bukan persamaan kuadrat dan dapat menyebabkan kesalahan saat menghitung akar. Kesalahan tersebut diperbaiki dengan memeriksa kondisi a == 0 terlebih dahulu sebelum menghitung diskriminan dan akar.

Tiket Keluar
Satu perbedaan penting antara if dan if-else adalah:
if hanya menjalankan blok kode ketika kondisi bernilai benar, sedangkan if-elsemenyediakan blok alternatif ketika kondisi bernilai salah.

Kesalahan logika yang paling mudah saya lakukan adalah:
Salah menentukan perbandingan operator, terutama pada kondisi nilai batas seperti minimal dan maksimal.

Test case yang membantu saya menemukan kesalahan adalah:
Input yang tepat pada nilai batas, seperti nilai 60 pada syarat izin, karena dapat memastikan operator yang digunakan sudah benar.

Kuis Formatif
Apa tipe hasil ekspresi 7 >= 5?
Jawaban: Boolean ( True).

Operator apa yang digunakan untuk menguji kesamaan dua nilai?
Jawaban: ==.

Apa perbedaan utama =dan ==?
Jawaban: =digunakan untuk memberikan nilai, sedangkan ==digunakan untuk membandingkan dua nilai.

Jika syarat kelulusan adalah nilai minimal 75, kondisi yang benar adalah?
Jawaban: nilai >= 75.

Kapan blok elsedijalankan?
Jawaban: Ketika kondisi ifbernilai salah.

Jika 14 % 2 = 0, bilangan 14 termasuk?
Jawaban: Bilangan genap.

Untuk kondisi nilai minimal 60 dan kehadiran minimal 80%, operator yang digunakan adalah?
Jawaban: and.

Mengapa bersarang jika digunakan?
Jawaban: Karena kondisi kedua hanya diperiksa setelah kondisi pertama terpenuhi.

Test case yang tepat untuk menguji batas kelulusan 60 adalah?
Jawaban: 59, 60, dan 61.

Perintah Git untuk mengirim commit lokal ke repositori GitHub adalah?
Jawaban: git push.

Penilaian Diri
Saya sudah memahami penggunaan if, if-else, kondisi majemuk, dan nested if dalam Python. Saya juga sudah melakukan pengujian pada beberapa kondisi untuk memastikan program berjalan sesuai dengan yang diharapkan.