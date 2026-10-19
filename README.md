# UTS Graf Sains Data

Repository ini berisi laporan dan implementasi praktikum Ujian Tengah Semester mata kuliah Graf Sains Data dengan dataset RetailRocket E-commerce Dataset.

## Identitas

- Nama: Thea Bayu Revalina
- NIM: 23031554035
- Kelas: 2023A
- Dataset: RetailRocket E-commerce Dataset

## Deskripsi Proyek

Proyek ini membahas penerapan konsep graf pada data interaksi pengguna dan produk dalam lingkungan e-commerce. Data yang digunakan merepresentasikan aktivitas seperti melihat produk (`view`), menambahkan ke keranjang (`addtocart`), dan pembelian (`transaction`).

Pada notebook utama, data diproses dan dianalisis dengan pendekatan berikut:

- representasi graf bipartit Visitor–Item
- pemodelan Vector Space Model (VSM)
- perhitungan cosine similarity
- penerapan Neo4j dan Cypher untuk penyimpanan graf
- rekomendasi berbasis K-Nearest Neighbors (KNN)
- validasi dan interpretasi hasil analisis

## Struktur Repository

- `UTS_GRAF_SADA_23031554035_THEA BAYU REVALINA.ipynb` — notebook utama berisi laporan, kode, dan output analisis
- `data/` — folder berisi dataset yang dipakai pada praktikum
- `output/` — folder hasil preprocessing, matriks, dan file pendukung yang dihasilkan dari notebook
- `requirements.txt` — daftar dependency Python yang diperlukan

## Teknologi yang Digunakan

- Python
- Pandas
- NumPy
- SciPy
- NetworkX
- Matplotlib
- scikit-learn
- Neo4j
- Cypher

## Tujuan Praktikum

Tujuan utama dari proyek ini adalah:

1. memahami representasi interaksi pengguna-produk dalam bentuk graf,
2. membangun model berbasis vektor dan matriks sparse,
3. menghitung kemiripan antar pengguna atau produk,
4. mengimplementasikan rekomendasi berbasis KNN,
5. mengevaluasi hasil analisis secara sistematis dan akademis.

## Dataset

Dataset yang digunakan adalah RetailRocket E-commerce Dataset. Dataset ini mencerminkan interaksi pengguna terhadap item dalam platform e-commerce, yang terdiri dari aktivitas seperti:

- `view` — pengguna melihat item
- `addtocart` — pengguna menambahkan item ke keranjang
- `transaction` — pengguna melakukan pembelian

## Catatan

Notebook ini dibuat untuk keperluan Ujian Tengah Semester Graf Sains Data. Seluruh penjelasan dalam notebook disusun berdasarkan kode dan output yang telah dieksekusi dan tersedia di repository ini.

Beberapa bagian analisis atau evaluasi dapat memerlukan eksekusi ulang agar hasilnya dapat diperiksa dan dilengkapi secara penuh sesuai kebutuhan penerapan di lingkungan masing-masing.

## Referensi

- Repository GitHub: https://github.com/nyxrtea/UTS-GrafSainsData
- Notebook utama: `UTS_GRAF_SADA_23031554035_THEA BAYU REVALINA.ipynb`

## Panduan Singkat

Untuk menjalankan notebook, pastikan environment sudah memiliki dependency yang tercantum di `requirements.txt`.

```bash
pip install -r requirements.txt
```

Lalu buka notebook menggunakan Jupyter Notebook atau JupyterLab.
