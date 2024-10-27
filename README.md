# Prediksi Pencarian Kata Kunci Menggunakan Time Series 📈 - ![Keyword Search](https://img.shields.io/badge/Keyword%20Search-007ACC?style=for-the-badge&logo=google&logoColor=white)

Repositori ini berisi proyek prediksi pencarian kata kunci menggunakan analisis time series. Proyek ini bertujuan untuk memprediksi volume pencarian berdasarkan data historis, sehingga dapat memberikan insight untuk strategi pemasaran dan perencanaan konten. Repositori ini mencakup file Jupyter Notebook yang menjelaskan proses secara menyeluruh, mulai dari eksplorasi data hingga penerapan model time series untuk peramalan.

## Daftar Isi 🗒️
1. [Project Overview](#project-overview-)
2. [Latar Belakang Masalah](#latar-belakang-masalah-)
3. [Problem Statement](#problem-statement-)
4. [Metode yang Digunakan](#metode-yang-digunakan-)
5. [Hasil Analisa](#hasil-analisa-)
6. [Rekomendasi](#rekomendasi-)
7. [File yang Tersedia](#file-yang-tersedia-)
8. [Cara Menggunakan Project Ini](#cara-menggunakan-project-ini-)
9. [Dependencies](#dependencies-)
10. [Libraries](#libraries-)
11. [Author](#author-)

## Project Overview 📝

Dalam proyek ini, saya menggunakan analisis time series untuk memprediksi volume pencarian kata kunci berdasarkan data historis. Beberapa langkah utama yang dicakup dalam proyek ini adalah:

1. **Import Libraries dan Eksplorasi Data**:
    - Memuat dataset dan melakukan eksplorasi awal untuk memahami struktur dan karakteristik data.

2. **Preprocessing Data**:
    - Melakukan pembersihan dan persiapan data, termasuk penanganan outlier dan imputasi nilai yang hilang.

3. **Pengembangan Model**:
    - Membangun dan melatih model time series untuk memprediksi volume pencarian.

4. **Evaluasi Model**:
    - Menggunakan metrik evaluasi untuk menilai kinerja model.

5. **Prediksi**:
    - Menghasilkan prediksi berdasarkan model yang sudah dilatih dan mengevaluasi hasilnya.

## Latar Belakang Masalah 🧐
Saya diminta untuk menganalisis permintaan paket wisata ke Pulau Pari dan memprediksi seberapa populer wisata ke Pulau Pari di minggu depan oleh sebuah perusahaan travel agent. Data yang dimiliki berasal Dari Google Trends yang mengandung informasi seberapa populer kata kunci "Pulau Pari" di pencarian Google.

## Problem Statement √
1. Bagaimana prediksi trendnya?
2. Apa rekomendai yang bisa dilakukan?

## Metode yang Digunakan 🛠️

- Analisis Time Series
- Visualisasi Data
- Pemodelan Prediktif

## Hasil Analisa 🧠

Dari hasil prediksi SARIMA, dalam satu tahun kedepan akan terjadi kenaikan dalam bulan maret dalam keyword search Pulau Pari, jika dibandingkan dengan plot data aktual maka seasonalitynya sedikit bergesar ke bulan April. Jika dilihat trennya sudah mengalami perubahan pola walaupun tidak terlalu signifikan, jadi mungkin selanjutnya masih bisa dipertimbangkan lagi penggunaan ARIMA atau mungkin pemilihan parameter di SARIMA akan diatur lagi.

## Rekomendasi 📌

Jika dilihat dari trennya ada beberapa rekomendasi yang bisa dilakukan oleh perusahaan travel:
1. Meningkatkan Aktivitas Pemasaran Digital
- Peluncuran Kampanye Iklan Berbayar:
Perusahaan dapat meluncurkan iklan PPC (Pay-Per-Click) melalui platform seperti Google Ads, menargetkan kata kunci "Pulau Pari" atau destinasi sejenis. Iklan ini akan membantu mempertahankan visibilitas meskipun volume pencarian organik menurun.
Gunakan juga iklan media sosial di platform seperti Instagram, Facebook, atau TikTok dengan promosi yang berfokus pada keindahan Pulau Pari dan aktivitas yang bisa dilakukan di sana.
- Konten Kreatif di Media Sosial:
Buat konten kreatif yang berfokus pada gambar dan video dari Pulau Pari. Misalnya, unggah cerita wisatawan yang baru saja berkunjung, atau video reel yang menunjukkan pantai, snorkeling, dan kegiatan wisata lainnya. Konten ini bisa menarik perhatian audiens di media sosial.
Buat hashtag kampanye spesifik untuk Pulau Pari dan ajak audiens berbagi pengalaman mereka di sana, sehingga meningkatkan buzz di media sosial.
2. Promosi dan Diskon Spesial untuk Pulau Pari
- Penawaran Diskon Terbatas: Perusahaan dapat meluncurkan diskon terbatas atau penawaran eksklusif untuk paket wisata ke Pulau Pari, seperti diskon untuk pemesanan awal, harga khusus untuk keluarga atau grup, atau bonus aktivitas tambahan (misalnya, tour gratis atau penyewaan peralatan snorkeling).
- Bundle Packages: Buat paket bundling yang menggabungkan Pulau Pari dengan destinasi terdekat lainnya, menawarkan nilai lebih bagi pelanggan yang mencari pengalaman liburan yang lebih komprehensif.
3. Optimasi Konten dan SEO
- Optimasi Konten Website: Buat artikel blog atau halaman website baru dengan tema yang lebih spesifik dan unik tentang Pulau Pari, seperti "Panduan Liburan Terbaik ke Pulau Pari" atau "10 Aktivitas Wajib di Pulau Pari". Ini membantu mengangkat SEO untuk jangka panjang dan menarik pengguna yang mencari informasi terkait destinasi ini.
- Targetkan Kata Kunci Long-Tail: Jika pencarian untuk "Pulau Pari" secara spesifik menurun, cobalah menargetkan kata kunci long-tail seperti "wisata snorkeling di Pulau Pari", "liburan pantai keluarga di Pulau Pari", atau "penginapan murah di Pulau Pari". Ini bisa menangkap minat calon pelanggan yang lebih spesifik dan berpotensi mendatangkan konversi.
4. Menggunakan Influencer atau Blogger
- Kerja sama dengan Influencer atau Travel Blogger: Undang influencer atau blogger yang memiliki banyak pengikut untuk mengunjungi Pulau Pari dan membagikan pengalaman mereka. Mereka dapat membuat konten promosi yang menarik, baik dalam bentuk foto, video, maupun cerita di media sosial, sehingga meningkatkan minat terhadap Pulau Pari.
- User-Generated Content: Dorong pelanggan yang sudah pernah berkunjung ke Pulau Pari untuk membagikan pengalaman mereka di media sosial atau di situs review seperti Google Reviews dan TripAdvisor. Ini dapat meningkatkan visibilitas destinasi secara organik.
5. Edukasi dan Konten Inspiratif
- Buat Konten Edukasi: Edukasi audiens mengenai keunikan Pulau Pari, seperti kekayaan biota laut, keindahan pantai, atau keberlanjutan lingkungan di pulau tersebut. Artikel atau video yang mendalam tentang keindahan alam dan cara-cara menjaga kelestarian bisa menjadi daya tarik bagi wisatawan yang peduli lingkungan.
- Konten Inspiratif: Ciptakan konten inspiratif seperti cerita tentang bagaimana Pulau Pari bisa menjadi destinasi liburan yang tenang dan aman untuk keluarga atau untuk pengunjung yang ingin bersantai dan menjauh dari keramaian.

## File yang Tersedia 📂

- `keyword_search_forecasting.ipynb`: Jupyter Notebook yang berisi langkah-langkah analisis data, pengembangan model time series, evaluasi model, dan mengambil insight yang diperoleh dari setiap proses analisa.
- `multiTimeline.csv`: Dataset yang digunakan dalam analisis (disediakan oleh Hacktiv8).
  
## Cara Menggunakan Project Ini 💻

1. Clone repositori ini ke dalam lokal Anda:
    ```bash
    git clone https://github.com/ciputrawangsa/Keyword_Search-TimeSeries.git
    ```

2. Jalankan Jupyter Notebook untuk mengikuti alur analisis data:
    ```bash
    jupyter notebook keyword_search_forecasting.ipynb
    ```

## Dependencies ⚙️

- ![Jupyter Notebook](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)
- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 3.10.14

## Libraries 📚
- Pandas
- Scikit-learn
- Statsmodels
- Matplotlib

## Author ✍️
**Ciputra Wangsa**

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ciputra-wangsa/)
