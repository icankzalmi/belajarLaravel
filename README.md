# belajarLaravel
Halo.. dikesempatan kali ini saya ingin membuat sebuah artikel tentang salah satu mata kuliah yang saya ikuti saat ini. sebelumnya saya ingin memperkenalkan diri terlebih dahulu, nama saya adalah Mohammad Ikhsan Zalmi, tapi saya biasa di panggil Icank, saya mahasiswa semester 7, jurusan Sistem Informasi, disalah satu kampus yang bisa dibilang masih baru tetapi telah cukup terkenal di international, yaitu Universitas Komputer Indonesia atau lebih terkenal dengan nama UNIKOM. mata kuliah yang saya ikuti yaitu adalah E-Commerce Lanjut. di mata kuliah ini saya mempelajari tentang Laravel, teman-teman tau ga apa itu Laravel? berikut adalah penjelasan singkat tentang Laravel :

Laravel adalah sebuah framework PHP yang dirilis dibawah lisensi MIT, dibangun dengan konsep MVC (model view controller). Laravel adalah pengembangan website berbasis MVP yang ditulis dalam PHP yang dirancang untuk meningkatkan kualitas perangkat lunak dengan mengurangi biaya pengembangan awal dan biaya pemeliharaan, dan untuk meningkatkan pengalaman bekerja dengan aplikasi dengan menyediakan sintaks yang ekspresif, jelas dan menghemat waktu.

Beberapa fitur yang terdapat di Laravel :
- Bundles, yaitu sebuah fitur dengan sistem pengemasan modular dan tersedia beragam di aplikasi.
- Eloquent ORM, merupakan penerapan PHP lanjutan menyediakan metode internal dari pola “active record” yang menagatasi masalah pada hubungan objek database.
- Application Logic, merupakan bagian dari aplikasi, menggunakan controller atau bagian Route.
- Reverse Routing, mendefinisikan relasi atau hubungan antara Link dan Route.
- Restful controllers, memisahkan logika dalam melayani HTTP GET and POST.
- Class Auto Loading, menyediakan loading otomatis untuk class PHP.
- View Composer, adalah kode unit logikal yang dapat dieksekusi ketika view sedang loading.
- IoC Container, memungkin obyek baru dihasilkan dengan pembalikan controller.
- Migration, menyediakan sistem kontrol untuk skema database.
- Unit Testing, banyak tes untuk mendeteksi dan mencegah regresi.
- Automatic Pagination, menyederhanakan tugas dari penerapan halaman.

di mata kuliah e-commerce lanjut ini saya mendapatkan sebuah proyek dari dosen yang mengajar mata kuliah ini untuk membuat sebuah proyek yang bersangkutan dengan laravel. untuk lebih jelasnya saya akan menjelaskan sedikit tentang proyek yang saya kerjakan.

sebenarnya saya tidak terlalu suka dengan yang namanya coding-codingan karena bikin lieur kalo kata orang sunda mah, tetapi untuk laravel cukup mudah karena laravel sudah memberikan banyak keuntungan dan kemudahan bagi siapa saja yang menggunakannya. pada proyek ini saya menggunakan template yang sudah ada yaitu AdminLTE-2.3.11.

pertama-tama kita disuruh untuk mengerjakan CRUD (Create Read Update Delete). CRUD adalah metode umum yang harus ada pada sebuah sistem informasi, di proyek laravel ini langkah pertama yang kita lakukan adalah create database tentang table kelas, pada tabel kelas kita membuat daftar tampilan kelas apa saja yang ada dan ditampilkan nanti di tampilan utama proyek kita. dan juga kita pasti harus memberikan fitur update untuk apabila ada kelas yang bertambah atau ada nama kelas yang berubah, dan juga fitur delete untuk menghapus apabila ada kelas yang berkurang atau kelas itu tidak ada lagi. di table kelas kita memasukkan nama kelas dan jurusan.

yang kedua adalah mengerjakan Eloquent Relationship yaitu membuat table siswa yang nantinya akan dimasukkan ke daftar siswa pada kelas dilangkah pertama, dilangkah kedua juga kita harus memberikan CRUD pada table siswa untuk update dan delete. di table siswa kita memasukkan NIS yang nantinya akan dijadikan primary key karena memiliki kode unique yang hanya ada 1 di sekolah tersebut. setelah NIS kita juga memasukkan nama lengkap siswa, jenis kelamin, alamat, nomor telepon dan terakhir ada id kelas yang berhubungan dengan kelas yang ada pada langkah pertama.

langkah ketiga yaitu membuat Login. pada login kita membuat tabel login yang nanti akan berisi id login, username, password, dan remember token untuk memberikan fitur remember me. user untuk Login pada saat ini saya hanya membuat untuk admin. tetapi nanti kalau ada waktu saya akan mengembangkan proyek ini dan membuat login untuk siswa juga. dan juga tidak lupa memberikan fitur logout.

sampai pada saat ini tiga langkah di atas sudah menghasilkan sistem informasi yang sudah layak pakai. tetapi saya memberikan satu fitur yang bisa meng-upload foto ke dalam tabel data siswa, sehingga dengan upload foto bisa menampilkan wajah dari siswa tersebut, dan ini bisa dibilang langkah ke empat. pada langkah ke empat ini saya menambah kolom untuk foto yang sebelumnya sudah ada di tabel siswa.

dan 4 langkah di atas adalah cerita singkat tentang proyek yang saya kerjakan pada saat ini di mata kuliah e-commerce lanjut yang saya ikuti saat ini.

mungkin pada kesempatan ini hanya itu saja yang dapat saya ceritakan kepada teman-teman tentang proyek yang saya kerjakan dengan laravel. terima kasih untuk teman-teman juga yang sudah menyempatkan diri dan meluangkan sedikit waktu untuk membaca artikel proyek laravel saya ini. akhirulkalam saya ucapkan wassalamu'alaikum.
