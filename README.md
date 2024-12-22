# Tugas Besar IF2211 OOP STI 2024
Kelompok 38 | KmBrEmpat
1. Daffa Ramadhan Elengi		18222009
2. Alessandro Jusack Hasian		18222025
3. Matthew Nicholas Gunawan		18222058
4. Viktor Arsidiantoro Siringoringo	18222083

## Deskripsi 
PhiUSIIL Phishing URL Dataset adalah dataset yang terdiri dari deskripsi suatu URL dan juga fitur-fitur yang terkait dengan URL tersebut beserta label URL legitimate dan URL phishing. Label 1 merupakan label untuk URL legitimate, sementara label 0 merupakan label untuk URL phishing.

**Repository Tubes-2-IF3070** merupakan kumpulan algoritma yang berisi beberapa tahapan penting dalam pemrosesan data untuk dapat **memprediksi suatu label dalam dataset** merupakan Phising atau Non-Phising. 
Dalam hal ini, Repository ini telah memenuhi alur pemrograman yang jelas dan memenuhi spesifikasi Tugas Besar **IF3070**, beberapa tahapannya meliputi 

### 1. Data Cleaning 
- Data Cleaning and Preprocessing
- Dealing with Outliers
- Data Validation
- Removing Duplicates
- Removing Duplicates
### 2. Data Preprocessing
- Feature Scaling
- Encoding Categorical Variables
- Handling Imbalanced Classes
- Dimensionality Reduction

Setelah melewati tahap pemrosesan data, selanjutnya repository ini menyediakan tahap pemodelan yang dilakukan baik melalui **Library dan Scratch** khusus untuk model **KNN dan Naive Bayes**

## Cara Setup dan Run Program 

Sebelum menjalankan proyek ini, pastikan anda telah menginstall:
- **Python 3.7+** (Jika belum, download terlebih dahulu dari [python.org](https://www.python.org/downloads/))

### 1. Clone proyek dari repository berikut

```bash
  git clone https://github.com/Reasondro/Tubes-2-IF3070
```

### 2. Buka folder tempat proyek tersimpan

```bash
  cd Tubes-2-IF3070
```

### 3. Buat virtual environment (Opsional, tetapi direkomendasikan)

```bash
  python -m venv venv
```
Lalu aktifkan virtual environment.
#### Windows:
```bash
  .\venv\Scripts\activate
```
#### Mac/Linux:
```bash
  source venv/bin/activate
```

### 3. Install dependencies

```bash
  pip install -r requirements.txt
```
- Jika ada package yang belum terpasang atau missing saat program dijalankan, silakan install secara manual menggunakan perintah
```
pip install <nama_package>
```

### 4. Jalankan Jupyter Notebook
```bash
  jupyter notebook
```
Lalu ketika Jupyter Notebook telah terbuka, jalankan program dengan mengklik run all.

## Pembagian Tugas 
### 18222009 
1. Menyusun template dokumen
2. Menyusun dokumentasi laporan

### 18222025
1. Membagi training set dan validation set
2. Melakukan preprocessing
3. Membuat Feature Engineering 
4. Membangun model Gaussian Naive Bayes scratch
5. Melakukan proses imbalance Data


### 18222058 
1. Membangun pemodelan KNN scratch
2. Menyusun dokumentasi laporan

### 18222083
1. Membuat bagian pembagian training set dan validation set
2. Membuat bagian transformasi data
3. Menyusun imputer untuk data cleaning
4. Membuat feature engineering
5. Melakukan proses scaling
6. Membangun pemodelan KNN scratch




