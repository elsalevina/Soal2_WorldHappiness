## **Soal 2 - World Happiness 😄**

Disediakan dataset laporan tingkat kebahagiaan di berbagai negara di dunia, unduh di sini: [World Happiness](https://www.kaggle.com/unsdsn/world-happiness#2019.csv). Gunakan hanya dataset _2019.csv_, lalu buatlah sebuah file _notebook_ (__.ipynb__) dan selesaikanlah beberapa soal berikut:

1. Untuk setiap numerik _feature/column_ (kecuali column ```Overall Rank```), hitunglah:
    - Mean, Median dan Modus
    - Range, Q1, Q3 dan IQR
    - Standard Deviasi & Variance
    - Z-score tiap data point

2. Untuk setiap numerik _feature/column_ (kecuali column ```Overall Rank```), carilah _data outlier_-nya berdasarkan:
    - IQR method
    - Z-score method

3. Tampilkan sebaran masing-masing numerik _feature/column_ (kecuali column ```Overall Rank```) dalam bentuk _boxplot_ dan _histogram_!

4. Di antara semua numerik _feature/column_ (kecuali column ```Overall Rank```), _feature/column_ mana saja yang sangat mempengaruhi _happiness score_ suatu negara? Buktikan dengan menghitung nilai:
    - Covariance
    - Pearson Correlation
    - Spearman Correlation
    - Kendall Correlation

5. Visualisasikan dalam bentuk _bar chart_ data berikut:
    - 10 Negara dengan _GDP per capita_ tertinggi.
    - 10 Negara dengan _Healthy life expectancy_ tertinggi.
    - 10 Negara dengan _Perceptions of corruption_ tertinggi.
