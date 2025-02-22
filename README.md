Pembuatan html
dalam body, harus ada div dengan id tertentu
dan dalam button, harus ada fungsia() dalam onclick

Pembuatan javascript (yaaaaaaaaaaaaaay)
Pertama, buat sebuah const berupa array
dalam array ini adalah banyak pertanyaan yang kita akan buat beserta jawabannya. Setiap tanya-jawab adalah object berbeda dengan kunci yang sama

Kedua, buat sebuah fungsib()
ini adalah fungsi yang langsung dijalankan agar semua pertanyaan bisa ditulis. untuk melakukan ini, kita mencari elemen div yang akan menjadi lembar pertanyaan, div ini adalah div yang mempunyai id tadi.
Setelah itu, kita melakukan sebuah kode terhadap setiap item dalam array, ini menggunakan fungsi forEach() yang ditulis setelah array pertanyaan, disambung dengan titik.
Kode yang dibuat merupakan kode HTML yang menulis pertanyaan dalam p dengan memanggil Index untuk nomor soal, dan item.kunci untuk pertanyaan. Jawaban akan sekaligus ditulis didalam p dengan id tertentu2 dan class yang menyembunyikannya, id tertentu ini adalah gabungan dari suatu id serta variabel index agar setiap id unik.

Terakhir, kita buat fungsia()
Fungsi ini adalah fungsi yang ada didalam button, menggunakan forEach, akan mencari semua id tertentu2 dan menghapus class yang menyembunyikan jawabannya.

Jangan lupa untuk menulis fungsi untuk menuliskan pertanyaan guys





