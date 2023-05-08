# **Pertemuan-8**
# **_Crafting_ dan _DNS Recon_**

## Crafting
> Pada hasil tangkapan wireshark di Windows setelah menjalankan perintah hping3 -c 3 10.33.107.46 pada terminal VM Kali Linux terdapat 37 paket yang tertampil. Opsi -c atau --count pada perintah tersebut digunakan untuk menentukan jumlah paket yang ditampilkan pada terminal Linux yang mana pada perintah berjumlah 3 sesuai dengan hasil run yang juga berjumlah 3 paket yang ditransmisikan dan diterima.

> Perintah hping3 --scan 1-3000 -S [IP_PC_Windows] adalah perintah yang digunakan untuk memindai port 1 hingga port 3000 dengan disertai opsi -S atau --syn yang berguna untuk mengirim paket SYN ke alamat IP target yang dalam praktikum ini menggunakan alamat IP PC Windows.

