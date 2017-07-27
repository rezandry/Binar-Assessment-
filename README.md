
1.1. Alasan menggunakan design seperti itu adalah karena ketika mobile apps request data dari device, maka request akan masuk ke controller yang mana akan mengeksekusi perintah yang dibutuhkan, dimana perintah tersebut membutuhkan hubungan ke database yang akan dilewatkan melalui controller. 
1.2. Sedangkan tools yang digunakan adalah phpmyadmin untuk database, bracket untuk text editor, codeigniter untuk framework php. semua itu digunakan karena bisa mencakup apa yang dibutuhkan, serta cukup banyak digunakan, sehingga untuk development kedepannya tidak susah untuk mencari developer yang mumpuni.

2. Untuk menangani masalah keamanan dapat dalam transfer data digunakan SSL/HTTPS karena pada layer tersebut data yang ditransfer akan aman. Untuk mengamankan data pada sisi client/apps, maka dapat dilakukan tokenisasi seperti jwt untuk verifikasi.
