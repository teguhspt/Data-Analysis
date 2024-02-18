>#  PUBLIC TRANSPORTATION TRANSACTION TRANSJAKARTA

## Latar Belakang
Transjakarta adalah moda transportasi berbasis Bus Rapid Transit (BRT) dan non-BRT yang sudah beroperasi sejak tahun 2004 di Jakarta. Tidak hanya melayani perjalanan di dalam Kota Jakarta bahkan hingga ke wilayah megapolitan Bodetabek (Bogor, Depok, Tangerang, dan Bekasi). Transjakarta memiliki Visi `Connecting the Life of Jakarta` Menghubungkan Kehidupan Jakarta dan Misi `Togetether we provide integrated transportation services to ease and bring happiness in the life of Jakarta` Bersama-sama menyediakan layanan transportasi terintegrasi yang memudahkan dan membahagiakan kehidupan Jakarta.

Dalam mencapai visi dan misi yang telah ditetapkan, peran seorang *Data Analyst* menjadi krusial dalam memberikan dukungan konkret kepada visi dan misi yang diusung oleh Transjakarta. Melalui analisis data yang mendalam, seorang *Data Analyst* dapat memberikan kontribusi yang signifikan untuk meningkatkan kualitas layanan yang sesuai dengan prinsip-prinsip inti perusahaan. Dengan fokus pada menyediakan layanan transportasi yang terintegrasi, kami berupaya mempersembahkan kemudahan dan kegembiraan kepada warga Jakarta, sambil menjembatani dan menghubungkan kehidupan kota yang dinamis ini.

## Pernyataan Masalah

Transjakarta dihadapkan pada pertumbuhan yang cepat dalam jumlah pengguna dan kompleksitas jaringan rute. Memahami karakteristik serta perilaku pengguna menjadi sangat penting dalam mengevaluasi dan meningkatkan standar layanan. Dalam konteks ini, diperlukan analisis data yang mendalam untuk mengidentifikasi pola penggunaan serta menemukan solusi yang dapat meningkatkan kenyamanan bagi para penumpang Transjakarta sesuai dengan Misi Transjakarta.

Selain itu, upaya untuk meningkatkan profit Transjakarta juga menjadi tantangan krusial mengingat penurunan pendapatan usaha dari Rp3,3 triliun pada 2019 menjadi Rp3,07 triliun pada 2020, dan lebih lanjut menyentuh angka Rp3,06 triliun pada 2021. Dalam menghadapi tren penurunan ini, diperlukan strategi yang efektif untuk meningkatkan pendapatan, seperti optimalisasi pemanfaatan layanan, promosi, dan pengembangan inovatif, termasuk penerapan metode pembayaran online melalui aplikasi JAKI untuk meningkatkan keterlibatan pengguna dan potensi pendapatan tambahan.

Source: <br>
[Pertumbuhan Pesat Jumlah Pengguna](https://bisnispro.id/pengguna-transjakarta-naik-hingga-800-ribu-orang-per-hari/) <br>
[Kondisi Keuangan Transjakarta](https://www.cnnindonesia.com/ekonomi/20230411171428-92-936355/mengintip-kondisi-keuangan-transjakarta-di-tengah-isu-tarif-naik)

## Business Questions
Berdasarkan Pernyataan Masalah yang telah disampaikan, sebagai seorang Data Analyst kita akan mencari tahu beberapa pertanyaan bisnis yang dapat dijawab berdasarkan dataset yang sudah disediakan oleh perusahaan:

1. **Demografi Pengguna:**
    - Bagaimana Distribusi Pengguna Transjakarta berdasarkan Gender?
    - Bagaimana Distribusi Pengguna Transjakarta berdasarkan Usia?
    - Bagaimana Distribusi Usia dan Gender pengguna terhadap Metode Pembayaran? 
2. **Tren Penggunaan:**
    - Bagaimana Tren penggunaan Transjakarta dalam rentang waktu satu bulan?
    - Bagaimana Persebaran penggunaan Transjakarta pada jam-jam tertentu sepanjang hari? Apakah ada pola perbedaan antara hari kerja dan akhir pekan?
3. **Pola Perjalanan dan Rute:**
    - Bagaimana distribusi perjalanan pengguna pada koridor pada saat peak hour?
    - Apakah terdapat perbedaan pola antara hari kerja dan akhir pekan?
    - Bagaimana pengaruh urutan pemberhentian terhadap waktu perjalanan?

Setiap pertanyaan bisnis ini dapat menjadi landasan untuk melakukan analisis data yang lebih mendalam. Dengan menjawab pertanyaan-pertanyaan ini, akan muncul wawasan yang lebih komprehensif terkait pola penggunaan, kebutuhan layanan, dan preferensi pengguna Transjakarta.

# Kesimpulan dan Rekomendasi 

**Kesimpulan**

Dari analisa yang telah kita lakukan pada Koridor Ciputat - CSW (S21), dapat ditarik beberapa kesimpulan

1. Jumlah Pengguna Koridor: <br>
   Koridor Cibubur - Balai Kota memiliki 190 pengguna, sementara Koridor Ciputat - CSW memiliki 180 pengguna. Pemilihan untuk menganalisis Koridor Ciputat - CSW didasarkan pada **`CARI TAU DULU.`**

2. Distribusi Pengguna Koridor S21 berdasarkan Gender: <br>
   Mayoritas pengguna (67.36%) adalah pria, sementara wanita menyumbang 32.64%.

3. Distribusi Pengguna Koridor S21 berdasarkan Kategori Usia: <br>
   Mayoritas pengguna (80.2%) termasuk dalam kategori dewasa, sedangkan remaja menyumbang 19.8%. Tidak ada data untuk bayi dan balita, anak-anak, maupun lansia.

4. Distribusi Pengguna Metode Pembayaran berdasarkan Gender: <br>
   - Metode pembayaran "bni" dan "dki" lebih populer secara jumlah.
   - Menariknya jika dikategorikan berdasarkan Gender, pria lebih dominan dibanding perempuan. dengan pengguna pria sebanyak 121 dan perempuan hanya 3 orang. 
   - Begitu juga untuk pembayaran online menggunakan Aplikasi JAKI, hanya terdapat 1 perempuan  dari 39 total pengguna pembayaran via online.
   - Penggunaan metode pembayaran brizzi dan flazz juga kurang diminati pada koridor S21.

5. Peak Time pada Koridor "Ciputat - CSW" pada Hari Kerja:<br>
   - Pagi hari, puncak penggunaan terjadi pada jam 6 pagi dan 9 pagi, menunjukkan penggunaan koridor saat menuju [tempat kerja](https://megapolitan.kompas.com/read/2023/02/18/01450021/rute-transjabodetabek-s21-csw-ciputat), sekolah, dan kampus.
   - Sore hari, puncak penggunaan terjadi pada 17:00 dan 21:00, kemungkinan terkait dengan pulang kerja atau [aktivitas setelah jam kerja](https://megapolitan.kompas.com/read/2023/02/18/01450021/rute-transjabodetabek-s21-csw-ciputat).
   - Pola penggunaan menunjukkan peluang peningkatan layanan atau frekuensi transportasi pada jam-jam sibuk untuk memenuhi kebutuhan pengguna pada puncak waktu tersebut.

6. Persebaran Waktu pada Koridor "Ciputat - CSW" pada Akhir Pekan: <br>
   Terlihat adanya perbedaan dalam persebaran pengguna pada akhir pekan dibandingkan dengan hari kerja.

7. Pola Penggunaan Transjakarta pada Koridor "Ciputat - CSW" selama April 2023: <br>
   - Pola penggunaan transportasi stabil selama hari kerja dengan penurunan pada akhir pekan. 
   - Tidak terjadi peningkatan pengguna saat libur lebaran bahkan pada tanggal 23 menunjukan bahwa masyarakat cenderung mengurangi perjalanan saat libur lebaran.
8. Persebaran Jumlah Pengguna pada saat TapIn di setiap Halte:<br>
   Terdapat variasi signifikan dalam jumlah pengguna pada saat TapIn di setiap halte pada waktu Morning Peak Hour. Lokasi strategis, keterkaitan dengan rute, dan karakteristik lingkungan mempengaruhi jumlah pengguna.

9. Persebaran Jumlah Pengguna pada saat TapOut di setiap Halte pada waktu Evening Peak Hour:<br>
   Halte "Pom Bensin Ciputat" memiliki jumlah pengguna tertinggi saat TapOut selama Evening Peak Hour. Variasi jumlah pengguna terjadi di berbagai halte.

10. Distribusi Arah Perjalanan Pengguna: <br>
   Terdapat distribusi yang seimbang antara pengguna yang melakukan perjalanan keberangkatan dan kembali. Implikasinya perlu dianalisis lebih lanjut untuk memahami preferensi dan kebutuhan pengguna.

   **Rekomendasi**

1. Mengurangi Penumpukan pada Peak Hour: <br>
    Peningkatan frekuensi layanan pada jam-jam sibuk, khususnya pada pukul 6 pagi, 9 pagi, 17:00, dan 21:00, dapat membantu mengurangi penumpukan. Penerapan sistem pengaturan antrean di halte strategis juga dapat meningkatkan efisiensi pemberhentian.
2. Meniadakan Armada pada Waktu Akhir Pekan:
    Dengan mengetahui bahwa jumlah pengguna pada akhir pekan sangat rendah (paling banyak 5 pengguna), pertimbangkan untuk meniadakan operasional armada pada akhir pekan atau mengurangi jumlah perjalanan armada yang beroperasi. Ini dapat membantu menekan biaya operasional tanpa mengorbankan kualitas layanan. 
3. Strategi Peningkatan Profit melalui Aplikasi JAKI: <br>
    Mendorong penggunaan aplikasi JAKI dengan memberikan promosi, atau penawaran khusus bagi pengguna yang memilih pembayaran online melalui aplikasi. Bisa dengan mengadopsi sistem poin yang diterapkan oleh Alfamart dimana setiap melakukan transaksi sebanyak n-kali,mendapatkan free biaya perjalanan. Kampanye pemasaran yang cermat dapat meningkatkan kepercayaan dan popularitas aplikasi.
4. Kolaborasi dengan Bank: <br>
    Mengidentifikasi dan berkolaborasi dengan bank yang memiliki ketertarikan rendah pada koridor S21. Potensi kemitraan dapat mencakup program promosi bersama, penawaran diskon bagi pemegang kartu bank tertentu, atau pengembangan fitur khusus untuk pengguna dengan metode pembayaran tertentu.
5. Optimasi Layanan di Jam Tengah Hari: <br>
    Melakukan optimasi untuk perjalanan di jam 10 dan 12, karna hanya terdapat sedikit penumpang pada jam tersebut. Hal ini dapat diinfokan melalui aplikasi JAKI agar pengguna yang memerlukan armada untuk perjalanan dapat melakukan pengecekan terlebih dahulu sehingga masih mendapatkan kendaraan guna untuk memenuhi kebutuhan perjalanan mereka.

    Link Tableau: [click here](https://public.tableau.com/app/profile/teguh.saputra4922/viz/Transjakarta_17050260690670/Dashboard1)

#### Created By : Teguh Saputra | [Email](hi.teguhsaputra@gmail.com) | JCDSOL-012 (C)