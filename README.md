# Game Sales Analysis Using KNN

##Deskripsi
Project ini menganalisis data penjualan game untuk menjawab pertanyaan
bisnis terkait wilayah, platform, genre, dan tren penjualan, serta
menerapkan algoritma K-Nearest Neighbor (KNN) sebagai metode *Supervised
Learning* untuk proses klasifikasi data.

# Dataset
Dataset yang digunakan merupakan data penjualan game global yang diperoleh
dari sumber publik (Kaggle).

- **vgsales.csv** : data mentah (raw data)
- Data mencakup informasi penjualan game berdasarkan wilayah
  (NA, EU, JP, dan Global), platform, genre, dan publisher.

Dataset disimpan pada folder:
dataset/vgsales.csv

## Tahapan Analisis
1. **Assessing Data**
   - Meninjau struktur dan kondisi data
2. **Cleaning Data**
   - Menangani missing value
   - Mengubah tipe data
3. **Exploratory Data Analysis (EDA)**
   - Analisis penjualan berdasarkan wilayah, platform, genre, dan tahun
4. **Pertanyaan Bisnis**
   - Menjawab pertanyaan berdasarkan hasil eksplorasi data
5. **Supervised Learning**
   - Train-Test Split
   - Normalisasi data
   - KNN Classification
   - Parameter tuning menggunakan Randomized Search CV
6. **Evaluasi Model**
   - Confusion Matrix
   - Classification Report
7. **Visualisasi**
   - Visualisasi hasil analisis dan performa model


## Algoritma yang Digunakan
- K-Nearest Neighbor (KNN)
- Randomized Search CV untuk optimasi parameter

## Tools & Library
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Cara Menjalankan Project
1. Clone repository ini atau download sebagai ZIP
2. Buka file notebook: game_sales_analysis.ipynb
3. Jalankan notebook menggunakan **Google Colab** atau **Jupyter Notebook**
4. Pastikan path dataset sesuai:
```python
pd.read_csv("dataset/vgsales.csv")
