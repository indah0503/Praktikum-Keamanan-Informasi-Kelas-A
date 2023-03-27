# **Pertemuan-6**
# _**Snort and Frirewall Rules**_

> Setelah skrip mnet dijalankan lalu perintah xterm R1 dimasukkan, akan muncul jendela terminal untuk shell R1, pengguna yang masuk ke shell tersebut adalah analyst ditandai keterangan [root@secOps analyst]# pada terminal R1.

> Kemudian buat terminal baru dengan nama H5. Pada H5 gunakan perintah wget untuk mengunduh file bernama W32.Nimda.Amm.exe dengan nomor ip 209.165.202.133 port 6666. Jika running file telah mencapai 100% artinya file berasil terunduh lalu akan muncul peringatan tanggal, waktu, muatan file, nama, dan jumlah file yang terunduh di bawahnya.

> Saat file berbahaya sedang transit, saat memasukkan baris perintah tail -f /var/log/snort/alert akan muncul peringatan berisi alamat ip (dari 209.165.200.235 menuju 209.165.202.133), port sumber (34484) dan port tujuan (6666), waktu pengunduhan (pada bulan 4 tanggal 28 pukul 17:00:04.092153, serta pesan yang direkam IDS (Malicious Server Hit!)

> File PCAP berguna bagi analisis keamanan untuk memeriksa / memverifikasi apakah file tersebut asli atau tidak dengan melihat ukuran file tersebut, jika ukurannya lebih dari nol maka file aman dari malware.

> Saat menyetel firewall pada terminal R1, rantai yang digunakan adalah INPUT, FORWARD, dan OUTPUT.

> Setelah firewall berhasil diset, unduhan file yang mengandung malware akan diblokir oleh aturan FORWARD maka dari itu akan muncul peringatan 'failed: Connection timed out'. Ada juga pendekatan yang lebih valid untuk memblokir server yang melanggar yakni dengan menambahkan aturan protokol, ip tujuan paket, port tujuan, dan atur aksi ke drop pada rantai FORWARD.
