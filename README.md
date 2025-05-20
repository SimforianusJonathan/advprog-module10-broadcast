#  Chat Broadcast 

## Client 1
![alt text](image.png)

## Client 2
![alt text](image.png)

## Client 3
![alt text](image-1.png)

## Server 
![alt text](image.png)

Pada dasarnya, server berperan sebagai pusat komunikasi yang selalu siaga memantau setiap koneksi dari para klien. Ketika sebuah klien mengirimkan pesan, server menangkap pesan tersebut melalui jalur koneksi yang sudah terbuka sebelumnya. Karena server menyimpan daftar lengkap seluruh klien yang sedang terhubung, ia tahu persis ke mana saja pesan perlu dikirimkan.

Setelah pesan diterima, server segera memprosesnya dan kemudian mendistribusikannya kembali ke semua klien yang ada pada daftar itu, termasuk si pengirim. Proses pengiriman ulang ini berlangsung sangat cepat sehingga setiap peserta percakapan seolah menerima pesan secara serempak. Dengan cara inilah konsistensi percakapan terjaga: semua orang, tanpa kecuali, mendapatkan informasi yang sama pada waktu hampir bersamaan.

Mekanisme tersebut juga memungkinkan sinkronisasi tampilan pesan di masing-masing perangkat. Klien tidak perlu bertanya lagi ke server apakah pesan yang baru dikirim sudah diterima pengguna lain, karena server sendirilah yang memastikan propagasi pesan terjadi. Alhasil, percakapan tetap lancar, real-time, dan terasa natural bagi semua pengguna.