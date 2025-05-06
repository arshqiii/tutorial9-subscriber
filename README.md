# Tutorial 9 - Software Architecture

## Muhammad Radhiya Arshq - 2306275885

### a. What is amqp?
AMQP singkatan dari Advanced Message Queuing Protocol yang merupakan sebuah protokol komunikasi berbasis pesan yang digunakan untuk mengirim pesan antara sistem terdistribusi. Protokol ini umum digunakan dalam sistem antrian pesan seperti RabbitMQ untuk memastikan komunikasi yang handal dan terpisah antar komponen sistem (misalnya antara producer dan consumer).


### b. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?
Dari kode yang ditulis sebelumnya snippet kode itu digunakan di fungsi main sebagai URL koneksi ke message broker queue. "guest" pertama merupakan username yang digunakan untuk login ke message broker, "guest" kedua merupakan password dari user guest, dan localhost:5672 merupakan alamat host server sekaligus port default untuk protokol AMQP yang digunakan message broker, dalam kasus ini, RabbitMQ.