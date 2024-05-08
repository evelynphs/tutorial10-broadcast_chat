# Tutorial 10

### 2.1. Original code of broadcast chat.

![2.1](images/2.1.png)
Program ini dijalankan dengan satu terminal untuk server dan tiga terminal untuk client. Server dijalankan dengan `cargo run --bin server` dan client dijalankan dengan `cargo run --bin client`. Setiap kali ada client yang baru disambungkan, server akan mencetak "New connection from {ip address client}" dan mengirimkan pesan "Welcome to chat! Type a message" pada client tersebut.

Pada client, kita bisa mengirim pesan dan mengirim pesan tersebut dengan menekan tombol enter. Setiap kali client mengirimkan message melalui console, server akan mencetak "From client {ip address client} "{pesan dari client}" ", kemudian mengirimkan message tersebut ke semua client dengan format "From server: {message}".

