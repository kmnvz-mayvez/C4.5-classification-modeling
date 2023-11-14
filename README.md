# C4.5-classification-modeling

## Algoritma Dasar

**Decision Tree:**
Decision tree adalah konsep umum yang dapat diimplementasikan dengan berbagai algoritma, seperti ID3 (Iterative Dichotomiser 3), CART (Classification and Regression Trees), dan C4.5. Decision tree mewakili aturan keputusan dalam bentuk pohon, di mana setiap simpul dalam pohon mewakili suatu keputusan atau pemisahan.

**C4.5:**
C4.5 (atau C5.0) adalah salah satu algoritma khusus untuk membangun decision tree. Algoritma ini dikembangkan oleh Ross Quinlan dan dirancang khusus untuk klasifikasi, dapat menangani data yang mengandung nilai yang hilang, dan membangun pohon keputusan yang lebih efisien.

## Penanganan Data Hilang

**Decision Tree:**
Banyak implementasi decision tree tidak dapat menangani nilai yang hilang secara langsung. Beberapa algoritma memerlukan imputasi nilai yang hilang sebelum membangun pohon keputusan.

**C4.5:**
C4.5 memiliki kemampuan bawaan untuk menangani nilai yang hilang dalam data pelatihan. Ini membuatnya lebih tangguh dalam menghadapi data yang tidak lengkap.

## Pemilihan Fitur

**Decision Tree:**
Berbagai algoritma decision tree menggunakan kriteria yang berbeda untuk memilih fitur terbaik untuk membagi data pada setiap simpul. Contohnya adalah Gini impurity untuk CART dan information gain untuk ID3.

**C4.5:**
C4.5 menggunakan information gain untuk menentukan mana yang merupakan fitur terbaik untuk membagi data. Information gain mengukur seberapa baik suatu fitur dapat membagi data menjadi kelompok-kelompok homogen.

## Penanganan Aturan yang Tidak Jelas

**Decision Tree:**
Beberapa implementasi decision tree mungkin menghasilkan aturan yang sulit diinterpretasikan atau tidak jelas.

**C4.5:**
C4.5 memiliki proses post-pruning (pemangkasan) yang membantu menghilangkan aturan yang tidak signifikan atau yang menyebabkan overfitting, sehingga menghasilkan model yang lebih interpretable dan umumnya lebih generalis.

Perlu dicatat bahwa ketika orang berbicara tentang "model C4.5," mereka mungkin merujuk pada decision tree yang dibangun dengan menggunakan algoritma C4.5. Namun, secara umum, C4.5 dan decision tree adalah dua konsep yang berbeda.
