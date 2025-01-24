# Statistical Analysis

## Deskripsi Proyek
Proyek ini mencakup analisis statistik yang luas, termasuk statistika regresi, statistika non-parametrik, pengujian hipotesis, dan metode resampling. Dengan menggunakan berbagai teknik, proyek ini bertujuan untuk memahami hubungan antara variabel dalam dataset, memvalidasi hipotesis, dan memberikan wawasan berbasis data untuk pengambilan keputusan.

### Ruang Lingkup Proyek
1. **Statistika Regresi**
   - **Model OLS (Ordinary Least Squares):** Menganalisis hubungan antara variabel-variabel dalam dataset.
   - **Koefisien Korelasi:**
     - Pearson
     - Spearman
     - Tau Kendall
   - **R-square:** Mengevaluasi sejauh mana model regresi menjelaskan variasi data.
   - **Identifikasi Masalah Model:**
     - Heteroskedastisitas
     - Autokorelasi
   - **Uji Signifikansi:** Menggunakan uji t untuk mengevaluasi signifikansi statistik dari koefisien regresi.

2. **Statistika Non-Parametrik**
   - Digunakan untuk analisis data tanpa asumsi distribusi tertentu.
   - Teknik yang diterapkan:
     - Uji Wilcoxon (Wilcoxon Signed-Rank Test)
     - Uji Mann-Whitney (Mann-Whitney U Test)
     - Uji Kruskal-Wallis
     - Uji Friedman
   - Cocok untuk membandingkan kelompok data ketika asumsi normalitas tidak terpenuhi.

3. **Pengujian Hipotesis**
   - Menyediakan uji statistik untuk memvalidasi hipotesis tertentu berdasarkan data.
   - Mendukung berbagai jenis uji statistik untuk mengevaluasi parameter model.

4. **Metode Resampling**
   - **Bootstrap:** Mengestimasi mean, varians, dan parameter lainnya tanpa asumsi distribusi populasi.
   - **Jackknife:** Mengestimasi statistik deskriptif dengan menghilangkan satu observasi pada satu waktu dari dataset.

5. **Visualisasi Data**
   - Menggunakan grafik batang, scatter plot, dan heatmap untuk menunjukkan hubungan dan pola dalam data.
   - Alat visualisasi utama:
     - Matplotlib
     - Seaborn

### Teknologi yang Digunakan
Proyek ini menggunakan bahasa pemrograman Python dan pustaka-pustaka berikut:
- **NumPy**: Untuk komputasi numerik dan manipulasi array.
- **Pandas**: Untuk manipulasi dan analisis data berbasis tabel.
- **SciPy**: Untuk pengujian hipotesis dan analisis non-parametrik.
- **Statsmodels**: Untuk analisis regresi dan model statistik.
- **Matplotlib & Seaborn**: Untuk visualisasi data.

## Cara Menggunakan
1. **Clone repositori ini:**
   ```bash
   git clone https://github.com/username/statistical-analysis.git
2. Masuk ke direktori proyek:
   ```bash
   git clone https://github.com/username/statistical-analysis.git
   cd statistical-analysis
3. Jalankan analisis:
Gunakan file notebook (.ipynb) untuk langkah-langkah analisis interaktif, atau
4. Jalankan skrip Python utama untuk analisis otomatis:
   ```bash
   python

#Tujuan Proyek
- Mengajarkan cara menggunakan berbagai teknik statistik pada data nyata.
- Meningkatkan pemahaman tentang hubungan antar variabel melalui analisis regresi dan non-parametrik.
- Memberikan wawasan berbasis data untuk pengambilan keputusan.
- Menyediakan metode resampling untuk analisis lanjutan.
