How to install postgreSQL
1. Pertama, Anda harus membuka halaman unduh penginstal PostgreSQL di EnterpriseDB. Kedua, klik link download seperti gambar di bawah ini:
   ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/096cede9-c86e-43bc-8953-97fc9b1546ae)
2. Klik dua kali pada file penginstal, wizard penginstalan akan muncul dan memandu Anda melalui beberapa langkah di mana Anda dapat memilih opsi berbeda yang ingin Anda miliki di PostgreSQL.
   Klik tombol Berikutnya
   ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/95977c20-badf-42f6-8752-a213acefb00d)
3. Tentukan folder instalasi, pilih folder Anda sendiri atau pertahankan folder default yang disarankan oleh penginstal PostgreSQL dan klik tombol Berikutnya
   ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/32e3b9f2-f3a7-4dd4-91a1-460819008f6a)
4. Pilih komponen perangkat lunak yang akan diinstal:
   - Server PostgreSQL untuk menginstal server database PostgreSQL
   - pgAdmin 4 untuk menginstal alat manajemen GUI database PostgreSQL.
   - Alat Baris Perintah untuk menginstal alat baris perintah seperti psql, pg_restore, dll. Alat ini memungkinkan Anda berinteraksi dengan server database PostgreSQL menggunakan antarmuka baris perintah.
   - Stack Builder menyediakan GUI yang memungkinkan Anda mengunduh dan menginstal driver yang berfungsi dengan PostgreSQL. Untuk tutorial di website ini, Anda tidak perlu menginstal Stack Builder jadi silakan hapus centangnya dan klik tombol Next untuk memilih direktori data:
  ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/ad5f937d-7025-4734-9e76-fda4766c49af)
5. Pilih direktori database untuk menyimpan data atau terima folder default. Dan klik tombol Berikutnya untuk melanjutkan ke langkah berikutnya:        
   ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/cdfdc676-b652-4659-8375-a481104ab2d6)
6. Masukkan kata sandi untuk superuser database (postgres)
   PostgreSQL berjalan sebagai layanan di latar belakang dengan akun layanan bernama postgres. Jika Anda sudah membuat akun layanan dengan nama postgres, Anda perlu memberikan kata sandi akun tersebut di jendela berikut.
   Setelah memasukkan kata sandi, Anda perlu mengetik ulang untuk mengonfirmasi dan klik tombol Berikutnya:
   ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/352e733b-8154-4f47-aaa5-167eb827ae9c)
7. Masukkan nomor port yang akan didengarkan oleh server database PostgreSQL. Port default PostgreSQL adalah 5432. Anda perlu memastikan tidak ada aplikasi lain yang menggunakan port ini.
   ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/c2fb6e23-4686-411a-8e07-294bcf08b644)
8. Pilih lokal default yang digunakan oleh database PostgreSQL. Jika Anda membiarkannya sebagai lokal default, PostgreSQL akan menggunakan lokal sistem operasi. Setelah itu klik tombol Berikutnya.
   ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/1d495716-27ef-40f5-9a96-24c4d0d785f1)
9. Wizard pengaturan akan menampilkan ringkasan informasi PostgreSQL. Anda perlu meninjaunya dan klik tombol Berikutnya jika semuanya sudah benar. Jika tidak, Anda perlu mengklik tombol Kembali untuk mengubah konfigurasinya.
   ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/714b584f-0239-4433-801d-097de63d8a86)      
    Sekarang, Anda siap menginstal PostgreSQL di komputer Anda. Klik tombol Berikutnya untuk mulai menginstal PostgreSQL.
   ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/c67e0873-8e76-4124-b2e3-5f1d9acf79dd)       
    Instalasi mungkin memerlukan waktu beberapa menit untuk selesai.
   ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/c71b0178-2157-4dfa-8424-acc362bb11d8)     
10. Klik tombol Selesai untuk menyelesaikan instalasi PostgreSQL.
    ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/f07087b3-a25d-4f26-8006-c89c89111856)
11. Kemudian beeikut terdapat cara verifikasi aplikasi ini
    Pertama, klik psqlaplikasi untuk meluncurkannya. Program baris perintah psql akan ditampilkan.           
    ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/ec8f14dd-144e-4ce6-b5ae-0ca7fde2bf9a)                   
    Kedua, masukkan semua informasi yang diperlukan seperti server, database, port, nama pengguna, dan kata sandi. Untuk menerima default, Anda dapat menekan Enter . Perhatikan bahwa Anda harus memberikan kata sandi yang Anda masukkan saat menginstal PostgreSQL.
    ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/da26f8a7-862b-4fb8-b861-30eca0631fc3)                       
    Ketiga, keluarkan perintah, SELECT version();Anda akan melihat output berikut:               
    ![image](https://github.com/nikejul/pertemuan1-basis-data/assets/148309211/10d21d37-882e-4cf7-857c-4018ab5a5c3e)             
    Selamat! Anda telah berhasil menginstal server database PostgreSQL di sistem lokal Anda. Mari pelajari berbagai cara untuk terhubung ke server database PostgreSQL .









