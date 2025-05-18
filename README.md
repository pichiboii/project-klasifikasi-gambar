# 🌸 Klasifikasi Gambar pada Flower Classification Dataset
Project Klasifikasi Gambar *Coding Camp 2025 by DBS Foundation* oleh Hafizha Aghnia Hasya <br>
Project ini bertujuan untuk membangun model klasifikasi gambar yang mampu mengenali dan mengklasifikasikan jenis bunga berdasarkan citra visualnya. Model ini dilatih menggunakan dataset gambar bunga yang terdiri dari 14 kelas

## 🔄 Alur Proyek
### 1. Data Preparation
Dataset diambil dari [kaggle](https://www.kaggle.com/datasets/marquis03/flower-classification/data) kemudian diproses, termasuk resize dan pembagian menjadi data training, validasi, dan testing.
### 2. Modeling
Model dikembangkan menggunakan arsitektur MobileNetV3Large sebagai base model dengan bobot pretrained dari ImageNet. Base model dibekukan (non-trainable) untuk menjaga bobot awal.
Di atas base model, ditambahkan beberapa layer tambahan
### 3. Pelatihan & Evaluasi
Model dilatih dengan data training, lalu dievaluasi menggunakan metrik akurasi dan loss yang divisualisasikan
### 4. Konversi model
Model dikonversi menjadi 3 format, yaitu savedmodel, TensorFlow Lite, dan TensorFlow.js
