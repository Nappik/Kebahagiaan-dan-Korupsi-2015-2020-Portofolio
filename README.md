
# Analisis Kebahagiaan dan Korupsi 2015-2020

Proyek ini bertujuan untuk menganalisis hubungan antara skor kebahagiaan dan tingkat korupsi di berbagai negara dari tahun 2015 hingga 2020. Dataset yang digunakan diambil dari Kaggle (https://www.kaggle.com/datasets/eliasturk/world-happiness-based-on-cpi-20152020) dan mencakup informasi tentang skor kebahagiaan dan persepsi korupsi di berbagai benua dan negara.

## Daftar Isi
1. Dataset
2. Instalasi
3. Struktur Proyek
4. Penggunaan
5. Hasil
6. Kesimpulan
7. Lisensi

## Dataset
Dataset berisi data terkait skor kebahagiaan dan persepsi korupsi yang mencakup:
- Country
- happiness_score
- gdp_per_capita
- family
- health
- freedom
- generosity
- government_trust
- dystopia_residual
- continent
- Year
- social_support
- cpi_score


## Instalasi
### Prasyarat
Pastikan Anda telah menginstal:
- Python 3.x
- Jupyter Notebook
- Paket berikut: pandas, numpy, matplotlib, seaborn, scikit-learn

Instal paket yang diperlukan dengan perintah:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Unduh Dataset
1. Kunjungi Kaggle.
2. Unduh dataset terkait kebahagiaan dan korupsi dari tahun 2015 hingga 2020.

## Struktur Proyek
Struktur repositori adalah sebagai berikut:
```
├── Kebahagiaan dan Korupsi 2015-2020.ipynb  # Jupyter Notebook analisis
├── dataset/                                # Folder berisi dataset
│   └── happiness_corruption_2015_2020.csv
├── README.txt                              # File README ini
```

## Penggunaan
1. Clone repositori ke komputer lokal:
```bash
git clone https://github.com/Nappik/Kebahagiaan-dan-Korupsi-2015-2020-Portofolio.git
```
2. Masuk ke direktori proyek:
```bash
cd Kebahagiaan-dan-Korupsi-2015-2020-Portofolio
```
3. Buka Jupyter Notebook:
```bash
jupyter notebook "Kebahagiaan dan Korupsi 2015-2020.ipynb"
```
4. Jalankan sel di notebook untuk menghasilkan analisis.

## Hasil
Hasil analisis menunjukkan tren skor kebahagiaan di berbagai benua dan negara dari tahun 2015 hingga 2020, yang diilustrasikan melalui beberapa visualisasi sebagai berikut:

1. **Rata-rata Skor Kebahagiaan**: Grafik menunjukkan bahwa ada fluktuasi dalam skor kebahagiaan di seluruh benua, dengan Australia dan Eropa memiliki skor yang lebih tinggi dibandingkan benua lainnya.

2. **Pembagian Benua**: Diagram lingkaran menunjukkan persentase rata-rata skor kebahagiaan berdasarkan benua. Eropa memiliki proporsi terbesar dalam kebahagiaan, diikuti oleh Asia dan Australia.

3. **Skor Kebahagiaan per Kontinen**: Grafik batang menggambarkan rata-rata skor kebahagiaan per kontinen, di mana Australia memiliki skor tertinggi.

4. **Tren Skor Kebahagiaan per Negara**: Grafik garis menunjukkan tren skor kebahagiaan untuk masing-masing negara dari 2015 hingga 2020. Beberapa negara mengalami peningkatan signifikan, sementara yang lain menunjukkan fluktuasi yang lebih besar.

## Kesimpulan
Analisis ini menunjukkan bahwa terdapat perbedaan signifikan dalam skor kebahagiaan antara benua dan negara. Negara-negara di Eropa dan Australia cenderung memiliki skor kebahagiaan yang lebih tinggi dibandingkan dengan negara-negara di Afrika dan Asia. Ini mengindikasikan bahwa faktor-faktor seperti ekonomi, sosial, dan politik dapat berperan dalam menentukan tingkat kebahagiaan suatu negara.

## Lisensi
