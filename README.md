# QA API Testing Practice

Latihan API testing dengan Postman menggunakan API publik [JSONPlaceholder](https://jsonplaceholder.typicode.com). Repository ini berisi collection Postman beserta assertion untuk tiap request.

## Cakupan

- **Method**: GET, POST, PUT, PATCH, DELETE, HEAD, OPTIONS
- **Skenario**: kasus positif (data ada, data berhasil dibuat atau diubah) dan kasus negatif (data tidak ada, respons 404)
- **Yang diverifikasi**: status code, isi body, header respons, jumlah data pada array, dan waktu respons
- **Struktur**: request dikelompokkan dalam folder `Baca` dan `Tulis`

## Hasil terakhir (17 Oktober 2026)

| Item | Hasil |
| --- | --- |
| Total test | 23 |
| Passed | 23 |
| Failed | 0 |
| Errors | 0 |
| Durasi | 5,2 detik |

## Cara menjalankan

1. Unduh file `latihan.postman_collection.json` dari repository ini.
2. Di Postman, klik **Import** lalu pilih file tersebut.
3. Klik collection, pilih **Run**, lalu **Run** lagi di halaman Collection Runner.

## Catatan

JSONPlaceholder adalah API simulasi, jadi data yang dibuat, diubah, atau dihapus tidak benar-benar tersimpan di server.

## Rencana berikutnya

- Memakai variable dan environment untuk alamat dasar API
- Menambah skenario yang sengaja gagal untuk melatih membaca laporan
- Belajar otomasi dengan Playwright

Dibuat oleh Akhdan sebagai bagian dari belajar QA tester.
