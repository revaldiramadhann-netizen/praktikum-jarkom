# Laporan Praktikum Jarkom

# Lampiran Modul 4 DNS
# Soal 4.2 Nslookup
1. Jalankan nslookup untuk mendapatkan alamat IP dari server web di Asia. Berapa alamat IP 
server tersebut? ![Hasil Percobaan](../assets/image/soal1(4.2).png)

2. Jalankan nslookup agar dapat mengetahui server DNS otoritatif untuk universitas di Eropa. ![Hasil Percobaan](../assets/image/soal2(4.2).png)

3. Jalankan nslookup untuk mencari tahu informasi mengenai server email dari Yahoo! Mail
melalui salah satu server yang didapatkan di pertanyaan nomor 2. Apa alamat IP-nya? 
![Hasil Percobaan](../assets/image/soal3.1(4.2).png)
![Hasil Percobaan](../assets/image/soal3.2(4.2).png)

# Soal 4.4 Tracing DNS dengan Wireshark
# Soal Pertama
1. Cari pesan permintaan DNS dan balasannya. Apakah pesan tersebut dikirimkan melalui UDP 
atau TCP? YA ![Hasil Percobaan](../assets/image/soal1(4.4).png)

2. Apa port tujuan pada pesan permintaan DNS? Apa port sumber pada pesan balasannya?
![Hasil Percobaan](../assets/image/soal2.1(4.4).png)
![Hasil Percobaan](../assets/image/soal2.2(4.4).png)

3. Pada pesan permintaan DNS, apa alamat IP tujuannya? Apa alamat IP server DNS lokal anda 
(gunakan ipconfig untuk mencari tahu)? Apakah kedua alamat IP tersebut sama? 
![Hasil Percobaan](../assets/image/soal3(4.4).png)

4. Periksa pesan permintaan DNS. Apa “jenis” atau ”type” dari pesan tersebut? Apakah pesan 
permintaan tersebut mengandung ”jawaban” atau ”answers”? Tipe nya AAAA dan mengandung answer
![Hasil Percobaan](../assets/image/soal4(4.4).png)

5. Periksa pesan balasan DNS. Berapa banyak ”jawaban” atau ”answers” yang terdapat di 
dalamnya? Apa saja isi yang terkandung dalam setiap jawaban tersebut? Ada 2 answers
![Hasil Percobaan](../assets/image/soal5.1(4.4).png)
![Hasil Percobaan](../assets/image/soal5.2(4.4).png)

6. Perhatikan paket TCP SYN yang selanjutnya dikirimkan oleh host Anda. Apakah alamat IP 
pada paket tersebut sesuai dengan alamat IP yang tertera pada pesan balasan DNS? Ya 

7. Halaman web yang sebelumnya anda akses (http://www.ietf.org) memuat beberapa 
gambar. Apakah host Anda perlu mengirimkan pesan permintaan DNS baru setiap kali ingin 
mengakses suatu gambar? Tidak perlu

# Soal Kedua
1. Apa port tujuan pada pesan permintaan DNS? Apa port sumber pada pesan balasan DNS?
Port tujuannya yaitu 53 dan sumbernya adalah 50968
![Hasil Percobaan](../assets/image/soal1(2).png)

2. Ke alamat IP manakah pesan permintaan DNS dikirimkan? Apakah alamat IP tersebut 
merupakan default alamat IP server DNS lokal Anda? 
![Hasil Percobaan](../assets/image/soal1.2(2).png)

3. Periksa pesan permintaan DNS. Apa ”jenis” atau ”type” dari pesan tersebut? Apakah pesan 
tersebut mengandung ”jawaban” atau ”answers”? ![Hasil Percobaan](../assets/image/soal2.1(2).png)

4. Periksa pesan balasan DNS. Berapa banyak ”jawaban” atau “answers” yang terdapat di 
dalamnya. Apa saja isi yang terkandung dalam setiap jawaban tersebut?
 ![Hasil Percobaan](../assets/image/soal2.2(2).png)

5. Sertakan hasil tangkapan layar. ![Hasil Percobaan](../assets/image/soal3(2).png)

# Soal Ketiga
1. Ke alamat IP manakah pesan permintaan DNS dikirimkan? Apakah alamat IP tersebut 
merupakan default alamat IP server DNS lokal Anda? Port tujuannya ada 53 dan sumbernya ada 61384
![Hasil Percobaan](../assets/image/soal1(3).png)
![Hasil Percobaan](../assets/image/soal2(3).png)

2. Periksa pesan permintaan DNS. Apa ”jenis” atau ”type” dari pesan tersebut? Apakah pesan
tersebut mengandung ”jawaban” atau ”answers”? Jenis atau tipe AAAA, dan ada dua jawaban
![Hasil Percobaan](../assets/image/soal3(3).png)

3. Periksa pesan balasan DNS. Apa nama server MIT yang diberikan oleh pesan balasan? 
Apakah pesan balasan ini juga memberikan alamat IP untuk server MIT tersebut? Server DNS tidak menyertakan Additional Records yang berisi daftar Name Server otoritatif untuk domain mit.edu. Namun, pesan tersebut memberikan jawaban atas query AAAA

4. Sertakan hasil tangkapan layar. ![Hasil Percobaan](../assets/image/soal4(3).png)

# Soal Keempat
1. Ke alamat IP manakah pesan permintaan DNS dikirimkan? Apakah alamat IP tersebut 
merupakan default alamat IP server DNS lokal Anda? 
![Hasil Percobaan](../assets/image/soal1(4).png)
![Hasil Percobaan](../assets/image/soal2(4).png)

2. Periksa pesan permintaan DNS. Apa ”jenis” atau ”type” dari pesan tersebut? Apakah pesan 
tersebut mengandung ”jawaban” atau ”answers”? ![Hasil Percobaan](../assets/image/soal2(5).png)

3. Periksa pesan balasan DNS. Berapa banyak ”jawaban” atau “answers” yang terdapat di 
dalamnya. Apa saja isi yang terkandung dalam setiap jawaban tersebut? 
![Hasil Percobaan](../assets/image/soal3(4).png)

4. Sertakan hasil tangkapan layar.


