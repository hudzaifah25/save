Jawaban Soal Teori

1. Perbedaan "display: none" dan "visibility: hidden"

- "display: none" elemen hilang dan tidak mengambil ruang.
- "visibility: hidden" elemen tidak terlihat tetapi ruangnya tetap ada.

Contoh:

.menu {
display: none;
}

Menyembunyikan menu yang belum digunakan.

.logo {
visibility: hidden;
}

Menyembunyikan logo sementara tanpa mengubah tata letak.

2. Perbedaan "position: relative" dan "position: absolute"

- Referensi posisi:
  - "relative" berdasarkan posisi aslinya.
  - "absolute" berdasarkan parent terdekat yang memiliki position selain "static".
- Keluar dari alur dokumen:
  - "relative" tidak.
  - "absolute" ya.
- Ruang asli dipertahankan:
  - "relative" ya.
  - "absolute" tidak.

3. Kenapa "position: sticky" disebut gabungan "relative" dan "fixed"?
   Karena awalnya elemen berperilaku seperti "relative", tetapi saat mencapai batas scroll tertentu akan menempel seperti "fixed".

4. Mengapa "z-index: 5" tidak berpengaruh?
   Karena "z-index" hanya bekerja pada elemen yang memiliki "position" selain "static" (misalnya "relative", "absolute", "fixed", atau "sticky").

5. Perbedaan "overflow"

- "hidden" konten yang keluar disembunyikan.
- "scroll" scrollbar selalu muncul.
- "auto" scrollbar muncul hanya jika diperlukan.

Penggunaan:

- "hidden" menyembunyikan bagian yang berlebih.
- "scroll" area yang harus selalu bisa digulir.
- "auto" kotak konten dengan ukuran yang bisa berubah.
