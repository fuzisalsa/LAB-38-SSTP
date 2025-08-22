# LAB-38-SSTP
Tanggal 20 agustus 2025
# SSTP (Secure Socket Tunneling Protocol),


# konfigurasi SSTP client 
1. masuk ke winbox
2. lalukan konfigurasi dasar untuk terhubung ke internet
3. pilih menu ppp > interface
4. klik (+)
5. isi nama(opsional)

![m](z1.PNG)

6. di bagian tab Dial out bagian connet to isi dengan ip lan office A non aktifkan verify server address from certificate masukkan user dan password yang telah di buat oleh office A

![M](z2.PNG)

7. bisa dilihat ada tangget R yang artinya sudah ter koneksi

![M](z3.PNG)

8. kita mendapatkan ip address secara otomatis dari office A dan intercae baru 

![M](z4.PNG)

9. kita buat route 

![M](z5.PNG)

10. lalu kita coba ping ke office  A

![M](z6.PNG)

# kesimpulan 

SSTP adalah protokol VPN yang menggunakan enkripsi SSL/TLS (port 443) untuk membuat koneksi aman antara client dan server.
