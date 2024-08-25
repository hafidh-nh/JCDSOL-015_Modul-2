# Analisis Data Perjalanan NYC TLC

## Latar Belakang

Industri transportasi perkotaan, khususnya layanan taksi, menghadapi tantangan yang semakin kompleks di kota-kota besar seperti New York. Dengan meningkatnya kompetisi dari layanan ridesharing dan perubahan perilaku konsumen, perusahaan taksi perlu lebih adaptif dalam mengelola operasi mereka. 

Proyek ini bertujuan untuk menganalisis data perjalanan taksi dari NYC Taxi and Limousine Commission (TLC) guna memberikan wawasan yang dapat membantu perusahaan taksi memahami pola perjalanan, meningkatkan efisiensi operasional, dan mengoptimalkan kepuasan pelanggan.

## Pernyataan Masalah

1. **Efisiensi Operasional**: Bagaimana perusahaan dapat mengoptimalkan distribusi armada mereka untuk memenuhi permintaan yang tinggi selama jam-jam tertentu?
2. **Ketidaksesuaian Tarif**: Bagaimana perusahaan dapat menyesuaikan struktur tarif mereka agar lebih adil dan transparan bagi pelanggan?
3. **Peningkatan Kepuasan Pelanggan**: Bagaimana perusahaan dapat meningkatkan pengalaman pelanggan dengan mengurangi durasi perjalanan dan memastikan biaya yang dikenakan sesuai dengan jarak yang ditempuh?

## Tujuan Analisis

1. Memahami pola perjalanan penumpang berdasarkan jarak, durasi, dan waktu.
2. Mengidentifikasi faktor-faktor yang memengaruhi biaya dan durasi perjalanan.
3. Memberikan rekomendasi untuk peningkatan layanan dan efisiensi operasional.

## Data yang Digunakan

- **Dataset**: NYC TLC Trip Record Data
- **Periode**: Januari 2023
- **Fitur Utama**: Waktu penjemputan, lokasi, jarak perjalanan, jumlah penumpang, dan tarif.

## Analisis Data

### Distribusi Jarak dan Durasi Perjalanan
Mayoritas perjalanan memiliki jarak antara 1 hingga 3 mil dan berlangsung selama 5 hingga 20 menit.

### Pola Waktu Perjalanan
Puncak perjalanan terjadi pada pagi hari (8-10 AM) dan sore hari (5-7 PM), konsisten dengan jam sibuk di New York City.

### Hubungan Jarak dan Tarif
Tarif perjalanan meningkat seiring dengan jarak perjalanan. Namun, terdapat outlier yang menunjukkan tarif tinggi untuk perjalanan jarak pendek.

### Ketidaksesuaian Tarif
Terdapat variasi yang signifikan dalam tarif yang dikenakan untuk jarak yang sama, menunjukkan ketidakseimbangan dalam penetapan harga.

## Kesimpulan

1. **Optimasi Operasional**: Pengelolaan armada selama jam sibuk dapat ditingkatkan untuk mengurangi waktu tunggu pelanggan.
2. **Penyesuaian Struktur Tarif**: Peninjauan ulang struktur tarif diperlukan untuk mengatasi ketidakseimbangan harga.
3. **Peningkatan Layanan Pelanggan**: Pengembangan aplikasi mobile dengan fitur yang lebih canggih dapat meningkatkan pengalaman pelanggan.

## Rekomendasi Bisnis

1. **Optimasi Operasional**: Gunakan teknologi prediksi permintaan berbasis data untuk pengelolaan armada yang lebih efisien.
2. **Penyesuaian Struktur Tarif**: Revisi struktur tarif untuk memastikan transparansi dan keadilan dalam penetapan harga.
3. **Peningkatan Layanan Pelanggan**: Investasi dalam pengembangan aplikasi mobile untuk memberikan perkiraan waktu tiba yang lebih akurat dan fitur promosi.

## File Terkait

- **Capstone_Modul_2.ipynb**: Notebook Jupyter yang berisi analisis lengkap.
- **NYC_TLC_Trip_Cleaned.csv**: Dataset yang sudah dibersihkan dan siap untuk analisis lebih lanjut.
