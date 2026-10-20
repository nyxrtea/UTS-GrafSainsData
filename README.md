# UTS Graf Sains Data

Repository ini berisi laporan dan implementasi praktikum Ujian Tengah Semester (UTS) untuk mata kuliah Graf Sains Data dengan dataset RetailRocket E-commerce Dataset.

## Identitas

- Nama: Thea Bayu Revalina
- NIM: 23031554035
- Kelas: 2023A
- Dataset: RetailRocket E-commerce Dataset

## Deskripsi Proyek

Proyek ini membahas penerapan konsep graf pada data interaksi pengguna dan produk dalam lingkungan e-commerce. Dataset yang digunakan merepresentasikan aktivitas pengguna seperti:

- `view` — pengguna melihat produk
- `addtocart` — pengguna menambahkan produk ke keranjang
- `transaction` — pengguna melakukan pembelian

Pada notebook utama, data diproses dan dianalisis dengan pendekatan berikut:

- representasi graf bipartit Visitor–Item
- pemodelan Vector Space Model (VSM)
- perhitungan cosine similarity
- penerapan Neo4j dan Cypher untuk penyimpanan graf
- rekomendasi berbasis K-Nearest Neighbors (KNN)
- validasi dan interpretasi hasil analisis

## Tujuan 

Tujuan utama dari proyek ini adalah:

1. memahami representasi interaksi pengguna-produk dalam bentuk graf,
2. membangun model berbasis vektor dan matriks sparse,
3. menghitung kemiripan antar pengguna atau produk,
4. mengimplementasikan rekomendasi berbasis KNN,
5. mengevaluasi hasil analisis secara sistematis dan akademis.

## Dataset

Dataset yang digunakan adalah RetailRocket E-commerce Dataset. Dataset ini mencerminkan interaksi pengguna terhadap item pada platform e-commerce dan menjadi dasar analisis untuk membangun rekomendasi berbasis graf dan similarity.

## Struktur Repository

- `UTS_GRAF_SADA_23031554035_THEA BAYU REVALINA.ipynb` — notebook utama berisi laporan, kode, dan output analisis
- `data/` — folder berisi dataset yang digunakan pada praktikum
- `output/` — folder hasil preprocessing, matriks, dan file pendukung yang dihasilkan dari notebook
- `requirements.txt` — daftar dependency Python yang diperlukan

## Library yang Digunakan

- Python
- Pandas
- NumPy
- SciPy
- NetworkX
- Matplotlib
- scikit-learn
- Neo4j
- Cypher

## Alur Analisis

Proyek ini mengikuti beberapa tahapan utama:

1. pengumpulan dan pembersihan data,
2. representasi interaksi dalam bentuk graf bipartit,
3. pembentukan matriks/vektor untuk model VSM,
4. perhitungan similarity antar item atau pengguna,
5. penerapan metode KNN untuk merekomendasikan item,
6. evaluasi hasil rekomendasi dan interpretasi temuan.

## Cara Menjalankan

Pastikan environment sudah memiliki dependency yang tercantum pada `requirements.txt`.

```bash
pip install -r requirements.txt
```

Lalu buka notebook utama:

```bash
jupyter notebook "UTS_GRAF_SADA_23031554035_THEA BAYU REVALINA.ipynb"
```

## Catatan

Notebook ini dibuat untuk keperluan Ujian Tengah Semester Mata Kuliah Graf Sains Data. Seluruh penjelasan dalam notebook disusun berdasarkan kode dan output yang telah dieksekusi dan tersedia di repository ini.

Beberapa bagian analisis atau evaluasi dapat memerlukan eksekusi ulang agar hasilnya dapat diperiksa dan dilengkapi secara penuh sesuai kebutuhan penerapan di lingkungan masing-masing.

## Referensi

- Repository GitHub: https://github.com/nyxrtea/UTS-GrafSainsData
- Notebook utama: `UTS_GRAF_SADA_23031554035_THEA BAYU REVALINA.ipynb`
