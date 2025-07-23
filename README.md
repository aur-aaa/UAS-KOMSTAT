SoVInesia - Dashboard Kerentanan Sosial
=======================================

Dashboard interaktif berbasis R Shiny yang dirancang untuk mengeksplorasi dan menganalisis data kerentanan sosial di Indonesia berdasarkan indeks SoVI. Proyek ini dikembangkan untuk memenuhi tugas mata kuliah Komputasi Statistik oleh mahasiswa Politeknik Statistika STIS.

URL Publik: https://aurarara.shinyapps.io/uas_komstat_2/

------------------------------------------------------------
Deskripsi Singkat
------------------------------------------------------------

Dashboard SoVInesia memberikan akses visual dan interaktif terhadap data kerentanan sosial tingkat kabupaten/kota di Indonesia. Pengguna dapat mengeksplorasi data, melakukan analisis statistik dasar dan lanjutan, serta menampilkan peta interaktif.

------------------------------------------------------------
Fitur Utama
------------------------------------------------------------

1. Beranda
   - Menampilkan ringkasan data, value box, dan metadata variabel.

2. Manajemen Data
   - Kategorisasi variabel numerik dengan metode tertentu dan fitur unduh data hasil kategorisasi.

3. Eksplorasi Data
   - Visualisasi interaktif seperti histogram, boxplot, barplot, scatterplot, heatmap korelasi, dan peta.

4. Uji Asumsi
   - Melakukan uji normalitas dan homogenitas variansi dengan interpretasi hasil.

5. Statistik Inferensia
   - Uji t, uji proporsi, uji variansi, dan ANOVA satu/dua arah.

6. Regresi Linear Berganda
   - Model regresi multivariat dan pemeriksaan asumsi model.

7. Download File Gabungan
   - Unduh seluruh output (grafik, hasil, interpretasi) dalam satu klik.

8. Tentang
   - Informasi tim dan tujuan pembuatan dashboard.

------------------------------------------------------------
Struktur Proyek
------------------------------------------------------------


    UAS KOMSTAT (2)/
    ├── data/                         
    │   ├── sovi_data.csv               
    │   ├── distance.csv           
    │   ├── indonesia511.geojson 
    ├── www/                            
    │   ├── style.css                   
    ├── global.R                        
    ├── ui.R                            
    ├── server.R 
    ├── install_packages.R
    ├── UAS KOMSTAT (2).Rproj

------------------------------------------------------------
Paket R yang Digunakan
------------------------------------------------------------

- shiny, shinydashboard
- ggplot2, plotly
- dplyr, tidyr, readr
- DT
- leaflet, sf
- car, nortest, lmtest
- rmarkdown
- stringr, shinyWidgets, shinyjs

------------------------------------------------------------
Sumber Data
------------------------------------------------------------

- [sovi_data.csv)](https://raw.githubusercontent.com/bmlmcmc/naspaclust/main/data/sovi_data.csv)
- [matrik_penimbang_jarak](https://raw.githubusercontent.com/bmlmcmc/naspaclust/main/data/distance.csv)
- [metadata](https://www.sciencedirect.com/science/article/pii/S2352340921010180)

------------------------------------------------------------
Laporan Final
------------------------------------------------------------

Laporan proyek ini dapat diakses melalui link berikut:
[Buka laporan final (word)](./laporan/2KS3_222313003_Aura Hanifa Kasetya Putri_UAS.word)

------------------------------------------------------------
Tujuan Dashboard
------------------------------------------------------------

1. Memvisualisasikan indikator kerentanan sosial di Indonesia.
2. Memberikan analisis statistik yang intuitif dan mudah dipahami.
3. Menyediakan tools interaktif untuk edukasi dan eksplorasi data sosial.

