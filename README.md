# Jarkom-Modul-5-ITB03-2022
---
Kelompok ITB03:
1. Haffif Rasya Fauzi - 5027201002 (Kontribusi 50%)
2. M. Hilmi Azis - 5027201049 (Kontribusi 0%)
3. Gennaro Fajar Mende - 5027201061 (Kontribusi 50%)
---

## Soal
---
(A) Tugas pertama kalian yaitu membuat topologi jaringan sesuai dengan rancangan yang diberikan Loid dibawah ini
gambar topologi di soal

Keterangan :	
Eden adalah DNS Server
WISE adalah DHCP Server
Garden dan SSS adalah Web Server
Jumlah Host pada Forger adalah 62 host
Jumlah Host pada Desmond adalah 700 host
Jumlah Host pada Blackbell adalah 255 host
Jumlah Host pada Briar adalah 200 host

(B) Untuk menjaga perdamaian dunia, Loid ingin meminta kalian untuk membuat topologi tersebut menggunakan teknik CIDR atau VLSM setelah melakukan subnetting.

(C) Anya, putri pertama Loid, juga berpesan kepada anda agar melakukan Routing agar setiap perangkat pada jaringan tersebut dapat terhubung.

(D) Tugas berikutnya adalah memberikan ip pada subnet Forger, Desmond, Blackbell, dan Briar secara dinamis menggunakan bantuan DHCP server. Kemudian kalian ingat bahwa kalian harus setting DHCP Relay pada router yang menghubungkannya.


## Jawab

Berikut ini adalah topologi yang telah kelompok kami buat:
gambar topologi kita

Untuk subnetting yang kami gunakan adalah VLSM dengan pembagian ip seperti berikut ini
gambar VLSM kita

Berikut ini adalah konfigurasi network pada setiap node
[Strix]
[Westalis]
[Ostania]
[Eden]
[WISE]
[Garden]
[SSS]
[Blackbell] [Briar] [Desmond] [Forger]
Dibawah ini adalah setting Router agar semua rute dapat terhubung
Pada Router Westalis dimasukkan kode berikut ini untuk rutenya dan DHCP Relaynya
Pada Router Ostania dimasukkan kode berikut ini untuk rutenya dan DHCP Relaynya
Untuk DHCP Server (WISE) di-setting
Untuk DNS Server (Eden) di-setting
Untuk Web-server (SSS dan Garden) di-setting seperti berikut ini

Jika dibuka webnya akan terlihat nama hostnya

Hasilnya semua node dapat ping dengan sesama
