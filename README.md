# **Pertemuan-8**
# **_Crafting_ dan _DNS Recon_**

## Crafting
> Pada hasil tangkapan wireshark di Windows setelah menjalankan perintah hping3 -c 3 10.33.107.46 pada terminal VM Kali Linux terdapat 37 paket yang tertampil. Opsi -c atau --count pada perintah tersebut digunakan untuk menentukan jumlah paket yang ditampilkan pada terminal Linux yang mana pada perintah berjumlah 3 sesuai dengan hasil run yang juga berjumlah 3 paket yang ditransmisikan dan diterima.

> Perintah hping3 --scan 1-3000 -S [IP_PC_Windows] adalah perintah yang digunakan untuk memindai port 1 hingga port 3000 dengan disertai opsi -S atau --syn yang berguna untuk mengirim paket SYN ke alamat IP target yang dalam praktikum ini menggunakan alamat IP PC Windows.

> Perintah hping3 [IP_PC_Windows] --udp --rand-source --data 500 berfungsi untuk mengubah data length sumber paket udp pada IP target menjadi 500.

> Fungsi --flood pada perintah hping3 [IP_PC_Windows] --flood adalah untuk menampilkan paket TCP yang membanjiri dari mesin penyerang. Pada hasil praktium diketahui untuk sementara saat menangkap layar adalah 14.693.838 paket dan akan terus bertambah seiring berjalannya waktu.

## DNS Recon
> DNSRecon adalah sebuah perintah Linux yang dapat melakukan berbagai fungsi mulai dari penilaian keamanan hingga pemecahan masalah jaringan dasar dengan memungkinkan pengguna untuk memeriksa catatan cache server DNS, menghitung catatan DNS umum untuk domain tertentu, memeriksa semua catatan NS untuk transfer zona, memeriksa resolusi wildcard, melakukan pencacahan data SRV umum dan ekspansi domain tingkat atas (TLD), memeriksa brute force, subdomain, dan host A dan catatan AAAA yang diberikan domain dan daftar kata, melakukan pencarian rekaman PTR untuk rentang IP atau CIDR tertentu, melakukan enumerasi subdomain dan host melalui Google Dorks, menyimpan temuan dalam format file teks untuk memudahkan manipulasi.
