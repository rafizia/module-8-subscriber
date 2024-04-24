Nama: Muhammad Rafi Zia Ulhaq<br>
NPM: 2206814551<br>
Kelas: Pemrograman Lanjut B<br>

# Module 8 - Subscriber

### Reflection 1
a. AMQP (Advanced Message Queuing Protocol) adalah sebuah protokol komunikasi yang digunakan untuk mengirim pesan antara aplikasi. AMQP memberi cara untuk mengirim, menyimpan, dan menerima pesan, dengan dukungan untuk antrian pesan, pertukaran pesan, dan routing pesan.<br>
b. `amqp://` menunjukkan protokol yang digunakan, yaitu AMQP (Advanced Message Queuing Protocol), `guest` pertama adalah nama pengguna sedangkan `guest` kedua adalah kata sandi. Keduanya digunakan untuk mengotentikasi koneksi ke server AMQP. `localhost:5672` adalah alamat dan port dari server AMQP yang akan diakses. "localhost" menunjukkan bahwa server AMQP berjalan di _local machine_, sedangkan "5672" adalah nomor port default untuk koneksi AMQP.

### Reflection 2
![alt text](https://github.com/rafizia/module-8-subscriber/blob/master/image/RabbitMQ-Slow-1.png?raw=true)

Grafik Queued messages RabbitMQ saya menunjukkan angka 15, hal ini berarti terdapat total 15 pesan yang saat ini menunggu di queue untuk diproses oleh subscriber. Jumlah ini merupakan total pesan yang telah dikeluarkan oleh publisher namun belum diambil atau diproses oleh subscriber.

![alt text](https://github.com/rafizia/module-8-subscriber/blob/master/image/RabbitMQ-Slow-2.png?raw=true)