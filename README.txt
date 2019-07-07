# uas-pemweb-smt4

Oleh: Muhammad Rifqy Abdallah, k3517035

https://app-pemwebq.000webhostapp.com/
untuk login sebagai admin = admin, 123456
untuk operator = iniaku, 4567

Karena fitur upload repository dibatasi hanya sampai 100 file, maka saya hanya mengunggah file-file controller, model, dan view serta database aplikasi dalam repository ini.


Selanjutnya, dari ke-7 point tugas yang diberikan, terdapat 1 poin yang tidak saya kerjakan yaitu perihal pemberian paging. Hal ini sengaja saya lakukan agar tidak mendapat nilai sempurna dalam uas.

Untuk susunan database, saya menambahkan tabel 'roles' untuk menata 2 jenis peran pengguna aplikasi yaitu admin dan operator. Mengikuti hal ini, saya juga menambahkan kolom 'role' dalam tabel user untuk membedakan peran mereka. 
Selanjutnya, dalam membedakan admin dan operator, saya membuat 2 controller dan view yang berbeda untuknya. Apabila pengguna login sebagai admin, ia akan masuk menggunakan controller dan view miliknya berikut dengan previlege yang ia miliki. Begitu pula dengan operator. Hal ini seluruhnya sudah sesuai dengan tugas yang diberikan.
Adapun untuk tampilan perhitungan statistika pada dashboard, saya belum menemukan cara agar ia dapat secara otomatis berubah mengikuti sebagaimana daftar kategori yang tersimpan dalam database. Dan karena hal ini tidak tercantum dalam poin tugas, saya pun tidak memiliki atensi untuk mengerjakannya.
Untuk fungsi-fungsi lain, sebagaimana yang dicantumkan dalam poin penugasan, sudah saya buat dan berjalan dengan baik.


Yang menjadi naas dari hal diatas adalah ia berjalan baik hanya di localhost. Saat mencobanya di menjalankannya secara online, ternyata terdapat banyak fitur yang menemui error. Yang masih berjalan normal adalah fitur insert-view-edit-delete buku saja. Fitur insert-edit-delete user dan kategori dinyatakan '404 Page Not Found; The page you requested was not found', padahal saya coba cek kembali di controller, semuanya masih ada dan lengkap.


