# :zap: **Jarkom-Modul-1-ITB01-2022** :zap:

| Nama                      | NRP            |
|---------------------------|----------------|
| Rafael Nixon              | 05311940000025 |
| Fairuz Azka Maulana       | 5027201017     |
| Muhammad Firdho Kustiawan | 5027201005     | 
<br/>


## :large_blue_circle: **Soal 1** :large_blue_circle: 
Sebutkan web server yang digunakan pada "monta.if.its.ac.id"!

**Jawaban:**
<br>
1. Pertama-tama kami memfilter paket yang ada dengan filter ```http.host eq “monta.if.its.ac.id```.
   <img src="./img/Nomor1a.png">
2. Kemudian memilih salah satu paket yang tersedia dan ```klik kanan -> Follow -> TCP Stream```.
   <img src="./img/Nomor1b.png">
3. Akhirnya didapatkan informasi web server yang digunakan.
   <img src="./img/Nomor1c.png">

## :large_blue_circle: **Soal 2** :large_blue_circle: 
## :large_blue_circle: **Soal 3** :large_blue_circle: 
Filter sehingga wireshark hanya menampilkan paket yang menuju port 80! 

**Jawaban:**
<br>
Kami memfilter paket yang tersedia dengan filter ```tcp.dstport == 80```
<img src="./img/Nomor3.png">

## :large_blue_circle: **Soal 4** :large_blue_circle: 
## :large_blue_circle: **Soal 5** :large_blue_circle: 
## :large_blue_circle: **Soal 6** :large_blue_circle: 
Filter sehingga wireshark hanya menampilkan paket yang menuju ke lipi.go.id !

**Jawaban:**
<br>
Kami memfilter paketnya dengan dua cara:
1. Kami ping terlebih dahulu website lipi.go.id nya dan didapatkan alamat IP-nya. Kemudian kami filter paketnya dan didapatkan terdapat 1 paket yang memiliki IP yang sama dengan alamat IP yang telah dilakukan ping.
   <img src="./img/Nomor6.png">
2. Kami tinggal memfilter paket-paket yang tersedia dengan filter ```http.host == lipi.go.id```
   <img src="./img/Nomor6b.png">

## :large_blue_circle: **Soal 7** :large_blue_circle: 
## :large_blue_circle: **Soal 8** :large_blue_circle: 
## :large_blue_circle: **Soal 9** :large_blue_circle: 
## :large_blue_circle: **Soal 10** :large_blue_circle: 