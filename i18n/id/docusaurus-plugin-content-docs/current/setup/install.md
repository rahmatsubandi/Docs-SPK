---
sidebar_position: 1
---

# Installasi

Ada beberapa langkah untuk menginstal aplikasi ini, yaitu:

1. Unduh file kode sumber [Dropbox](https://www.dropbox.com/sh/su7xfzsxlz8n5bk/AABADj1qZhCfRuKlQ0H1oYIpa?dl=0) (Pastikan email Anda telah mengkonfirmasi undangan)
2. Ekstrak file ZIP ke `htdocs/folder`
3. Buka file di `application/config/database.php` di bagian bawah sesuaikan dengan lingkungan komputer kamu
   ```php
   'username' => 'root', // secara default adalah root
   'password' => '', // secara default kosong
   'database' => 'sistemkeputusan', // nama database yang akan anda buat pada poin nomor 4
   ```
4. Buat database baru di xampp. Jika Anda tidak tahu cara membuat database baru, Anda dapat mengunjungi tautan berikut: [Buat database baru](https://www.dewaweb.com/blog/cara-membuat-database-di-xampp/).
5. Setelah pembuatan database selesai di xampp, Anda dapat membuka folder `database/local` maka Anda akan menemukan nama database `sistemkeputusan.sql` Selanjutnya anda perlu mengimport database di localhost/xampp/database yang telah anda buat pada poin nomor 4. Jika anda belum tahu cara mengimportnya, anda bisa membaca tutorialnya [disini](https://www.niagahoster.co.id/blog/cara-import-database-mysql/)
6. Proses instalasi selesai. Anda dapat mengakses aplikasi Anda dengan: `localhost/namefolder`. Misalnya jika saya memberi nama folder aplikasi saya di htdocs dengan nama `spk`, maka saya mengaksesnya di browser adalah: `localhost/spk`.
