# **Pertemuan-4**

## **`Steganografi`**
> Steganografi adalah ilmu pengetahuan dan seni dalam menyembunyikan komunikasi. Suatu sistem steganografi sedemikian rupa menyembunyikan isi suatu data di dalam suatu sampul media yang tidak dapat di duga oleh orang biasa sehingga tidak membangunkan suatu kecurigaan kepada orang yang melihatnya.

> Pada praktikum pertemuan ini, praktikan mencoba dengan menggunakan peragkat lunak QS12 Setup, untuk langkah-langkahnya dapat dilihat pada file PDF terlampir.

## **`MD5Sum`**
> MD5SUM adalah semacam _fingerprint_ dari suatu file yang digunakan untuk memastikan bahwa data yang kita download benar-benar sesuai dengan data aslinya. Yang tertera pada lampiran adalah langkah-langkah menggunakan Command Prompt (CMD) dengan file STEGO yang telah dibuat pada poin A.

## **`Analisis Log Server`**
> Pada bagian analisis ini, praktikan menggunakan perangkat lunak VM VirtualBox dan VM CyberOps Workstation. Jalankan perintah-perintah yang ada pada laporan lampiran melalui terminal yang tersedia di dalam VM.

>1. Perintah 'cat' : Mendapatkan informasi lengkap mengenai suatu file.
>2. Perintah 'more' : Memisahkan informasi pada beberapa part. Jika ingin lebih banyak dari yang terlihat pada layar, gunakan tombol Enter. Jika ingin berhenti lalu membuat perintah lain, gunakan kombinasi Ctrl+Q.
>3. Perintah 'less' : Memberikan informasi mengenai suatu file pada jendela lain yang hanya dikhususkan untuk informasi tersebut. Jika ingin kembali pada jendela perintah, klik tombol Q atau kombinasi Ctrl+Q.
>4. Perintah 'tail' : Menampilkan 10 baris terakhir pada file.
>5. Perintah 'tail -f' : Menampilkan 10 baris terakhir file yang akan dicek ulang filenya setiap 1 detik.
>6. Perintah 'echo' : Mencetak string yang akan di proses sebagai argumen ke output standar.
>7. Perintah 'sudo cat /var/log/syslog' : Melihat file syslog yang mana file log sistem merekam berbagai pesan yang berguna untuk debugging.
>8. Perintah 'journalctl' : Melihat log sistem di distribusi Linux yang menggunakan Systemd.
>9. Perintah 'sudo journalctl –utc' : perintah yang digunakan jika ingin menentukan log in UTC.
>10. Perintah 'sudo journalctl –b' : Menampilkan boot saat ini dan boot yang spesifik.
>11. Perintah 'sudo journalctl -u nginx.service --since today' : menentukan catatan log perangkat sejak hari saat perintah dijalankan.
>12. Perintah 'sudo journalctl –k' : Menampilkan catatan log kernel.
>13. Perintah 'sudo journalctl –f' : Menampilkan log secara real time.

## **Daftar Referensi**
1. Wijaya, Ermadi Satriya dan Prayudi, Yudi. (2004, Juni). KONSEP HIDDEN MESSAGE MENGGUNAKAN TEKNIK STEGANOGRAFI DYNAMIC CELL SPREADING. Media Informatika Universitas Islam Indonesia. Vol. 2. No. 1. 23-38. ISSN: 0854-4743. Diakses pada 13 Maret 2023, dari https://journal.uii.ac.id/media-informatika/article/view/3/3.
2. Hadi, Cahaya. (2014, 14 November). WinMD5Free : Cara Mengecek MD5SUM dengan Cara yang Sangat Mudah. Diakses pada 13 Maret 2023, dari http://erwincahyadi.blogspot.com/2014/11/winmd5free-cara-mengecek-md5sum-dengan.html.
