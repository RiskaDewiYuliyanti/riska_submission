
# Proyek Analisis Data: Air Quality Dataset

## Identitas
- **Nama**: Riska Dewi Yuliyanti
- **Email**: [riskadewiyuliyanti@gmail.com]
- **ID Dicoding** : riskady

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis kualitas udara menggunakan dataset yang terdiri dari 12.880 entri dan 26 kolom, mencakup variabel terkait suhu, kelembapan, dan jumlah pengendara. Analisis ini berfokus pada distribusi harian kelembapan, suhu rata-rata harian, dan variasi total jumlah pengendara berdasarkan musim.

## Dataset
- **Jumlah Entri**: 12.880
- **Jumlah Kolom**: 26
- **Kolom yang Terdapat dalam Dataset**: `instant_x`, `dteday`, `season`, `yr_x`, `mnth`, `holiday`, `weekday`, `workingday`, `weathersit`, `temp_x`, `atemp_x`, `hum_x`, `windspeed_x`, `casual_x`, `registered_x`, `cnt_x`, `instant_y`, `yr_y`, `hr`, `temp_y`, `atemp_y`, `hum_y`, `windspeed_y`, `casual_y`, `registered_y`, `cnt_y`.

## Analisis
1. **Distribusi Kelembapan**: Kelembapan harian menunjukkan pola yang jelas, dengan fluktuasi berdasarkan musim dan kondisi cuaca.
2. **Suhu Rata-rata Harian**: Suhu rata-rata harian menunjukkan variasi yang signifikan yang dipengaruhi oleh perubahan musim.
3. **Variasi Jumlah Pengendara**: Jumlah pengendara mengalami variasi yang sejalan dengan perubahan musim dan kondisi cuaca, menunjukkan tren positif pada bulan-bulan tertentu.

## Kebutuhan Sistem
- Python 3.10
- Library yang diperlukan dapat ditemukan dalam file `requirements.txt`.

## Kesimpulan
1. Dataset yang dianalisis menunjukkan adanya hubungan antara kondisi cuaca dengan variabel kelembapan dan suhu.
2. Fluktuasi suhu dan kelembapan berperan penting dalam memengaruhi jumlah pengendara, yang dapat diindikasikan oleh tren yang diamati.

## Cara Menjalankan Proyek
1. Klon repositori ini atau download ZIP.
2. Pastikan semua dependensi terinstal dengan menjalankan:
   ```bash
   pip install -r requirements.txt

## Cara jalankan Jupyter Notebook
jupyter notebook notebook.ipynb

### Catatan:
- Email dan ID DICODING saya : `[riskadewiyuliyanti@gmail.com]` dan `[riskady]`
