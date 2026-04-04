# Lampiran Modul 5 UDP

# Soal 5.2
1. Pilih satu paket UDP yang terdapat pada trace Anda. Dari paket tersebut, berapa banyak 
“field” yang terdapat pada header UDP? Sebutkan nama-nama field yang Anda temukan!
Ada 4 field yang terdapat pada header UDP yaitu:
- Source Port
- Destination Port
- Length
- Checksum
![Hasil Percobaan](../assets/image/soal1(5).png)
![Hasil Percobaan](../assets/image/soal2.1(5).png)

2. Perhatikan informasi “content field” pada paket yang Anda pilih di pertanyaan 1. Berapa 
panjang (dalam satuan byte) masing-masing “field” yang terdapat pada header UDP?
![Hasil Percobaan](../assets/image/soal2.1(5).png)

3. Nilai yang tertera pada ”Length” menyatakan nilai apa? Verfikasi jawaban Anda melalui 
paket UDP pada trace. ![Hasil Percobaan](../assets/image/soal2.2(5).png)

4. Berapa jumlah maksimum byte yang dapat disertakan dalam payload UDP? (Petunjuk: 
jawaban untuk pertanyaan ini dapat ditentukan dari jawaban Anda untuk pertanyaan 2)
![Hasil Percobaan](../assets/image/soal3(5).png)

5. Berapa nomor port terbesar yang dapat menjadi port sumber? (Petunjuk: lihat petunjuk 
pada pertanyaan 4) ![Hasil Percobaan](../assets/image/soal4(5).png)

6. Berapa nomor protokol untuk UDP? Berikan jawaban Anda dalam notasi heksadesimal dan 
desimal. Untuk menjawab pertanyaan ini, Anda harus melihat ke bagian ”Protocol” pada 
datagram IP yang mengandung segmen UDP. ![Hasil Percobaan](../assets/image/soal5(5).png)

7. Periksa pasangan paket UDP di mana host Anda mengirimkan paket UDP pertama dan paket 
UDP kedua merupakan balasan dari paket UDP yang pertama. (Petunjuk: agar paket keduamerupakan balasan dari paket pertama, pengirim paket pertama harus menjadi tujuan dari 
paket kedua). Jelaskan hubungan antara nomor port pada kedua paket tersebut!
Hubungan antara nomor port pada kedua paket tersebut bersifat saling berkebalikan (inverse). Polanya:
- Source Port pada paket permintaan menjadi Destination Port pada paket balasan
- Destination Port pada paket permintaan menjadi Source Port pada paket balasan Paket Pertama (Request/Permintaan):
- Source Port (Port Asal): 4334
- Destination Port (Port Tujuan): 161 Paket Kedua (Response/Balasan):
- Source Port (Port Asal): 161
- Destination Port (Port Tujuan): 4334 Nomor port berfungsi sebagai "alamat aplikasi" di dalam sebuah komputer. Ketika komputer mengirimkan permintaan ke server, server harus mengetahui ke mana jawaban tersebut harus dikirimkan kembali agar sampai ke aplikasi yang benar (dalam hal ini, aplikasi yang membuka port 4334)
![Hasil Percobaan](../assets/image/soal1(5).png)
![Hasil Percobaan](../assets/image/soal6(5).png)
