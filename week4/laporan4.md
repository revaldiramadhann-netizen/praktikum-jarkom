# Laporan Praktikum Jarkom

# Lampiran Modul 4
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
2. Ke alamat IP manakah pesan permintaan DNS dikirimkan? Apakah alamat IP tersebut 
merupakan default alamat IP server DNS lokal Anda?
3. Periksa pesan permintaan DNS. Apa ”jenis” atau ”type” dari pesan tersebut? Apakah pesan 
tersebut mengandung ”jawaban” atau ”answers”?
4. Periksa pesan balasan DNS. Berapa banyak ”jawaban” atau “answers” yang terdapat di 
dalamnya. Apa saja isi yang terkandung dalam setiap jawaban tersebut?
5. Sertakan hasil tangkapan layar.

# Soal Ketiga
1. Ke alamat IP manakah pesan permintaan DNS dikirimkan? Apakah alamat IP tersebut 
merupakan default alamat IP server DNS lokal Anda?
2. Periksa pesan permintaan DNS. Apa ”jenis” atau ”type” dari pesan tersebut? Apakah pesan 
tersebut mengandung ”jawaban” atau ”answers”?
3. Periksa pesan balasan DNS. Apa nama server MIT yang diberikan oleh pesan balasan? 
Apakah pesan balasan ini juga memberikan alamat IP untuk server MIT tersebut?
4. Sertakan hasil tangkapan layar.

# Soal Keempat
1. Ke alamat IP manakah pesan permintaan DNS dikirimkan? Apakah alamat IP tersebut 
merupakan default alamat IP server DNS lokal Anda?
2. Periksa pesan permintaan DNS. Apa ”jenis” atau ”type” dari pesan tersebut? Apakah pesan 
tersebut mengandung ”jawaban” atau ”answers”?
3. Periksa pesan balasan DNS. Berapa banyak ”jawaban” atau “answers” yang terdapat di 
dalamnya. Apa saja isi yang terkandung dalam setiap jawaban tersebut?
4. Sertakan hasil tangkapan layar.

# Lampiran Modul 5
# Soal 5.2
1. Pilih satu paket UDP yang terdapat pada trace Anda. Dari paket tersebut, berapa banyak 
“field” yang terdapat pada header UDP? Sebutkan nama-nama field yang Anda temukan!
2. Perhatikan informasi “content field” pada paket yang Anda pilih di pertanyaan 1. Berapa 
panjang (dalam satuan byte) masing-masing “field” yang terdapat pada header UDP?
3. Nilai yang tertera pada ”Length” menyatakan nilai apa? Verfikasi jawaban Anda melalui 
paket UDP pada trace.
4. Berapa jumlah maksimum byte yang dapat disertakan dalam payload UDP? (Petunjuk: 
jawaban untuk pertanyaan ini dapat ditentukan dari jawaban Anda untuk pertanyaan 2)
5. Berapa nomor port terbesar yang dapat menjadi port sumber? (Petunjuk: lihat petunjuk 
pada pertanyaan 4)
6. Berapa nomor protokol untuk UDP? Berikan jawaban Anda dalam notasi heksadesimal dan 
desimal. Untuk menjawab pertanyaan ini, Anda harus melihat ke bagian ”Protocol” pada 
datagram IP yang mengandung segmen UDP.
7. Periksa pasangan paket UDP di mana host Anda mengirimkan paket UDP pertama dan paket 
UDP kedua merupakan balasan dari paket UDP yang pertama. (Petunjuk: agar paket keduamerupakan balasan dari paket pertama, pengirim paket pertama harus menjadi tujuan dari 
paket kedua). Jelaskan hubungan antara nomor port pada kedua paket tersebut!