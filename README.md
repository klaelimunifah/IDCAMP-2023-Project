# IDCAMP-2023-Project
Keseluruhan proyek yang sudah dikerjakan selama mengikuti IDCAMP 2023 Learning Path Data Scientist

## 1. Kelas Basic dan Beginner
### Proyek Analisis Data
Kriteria:
- Kriteria 1: Menggunakan Salah Satu dari Dataset yang Telah Disediakan
- Kriteria 2: Melakukan Seluruh Proses Analisis Data
- Kriteria 3: Proses Analisis Dibuat dalam Notebook yang Rapi
- Kriteria 4: Membuat Dashboard Sederhana Menggunakan Streamlit
     
Pada proyek ini saya menganalisis data dari Air Quality Dataset (https://github.com/marceloreis/HTI/tree/master). Berhasil memenuhi seluruh kriteria.

**Skills** : Dasar-Dasar Analisis Data, Penerapan Dasar-Dasar Descriptive Statistics, Pertimbangan dalam Pengolahan Data, Data Wrangling, Exploratory Data Analysis, Data, Visualization, Pengembangan Dashboard
     
**Tools** : Python, Pandas, Mathplotlib, Seaborn, Streamlit
     
**Link Proyek** : https://github.com/klaelimunifah/Proyek-Analisis-Data---Kurniati-L-M/tree/main

### Proyek Akhir : Klasifikasi Gambar
Kriteria: 
- Dataset yang dipakai haruslah dataset berikut : rockpaperscissors, atau gunakan link wget command.
- Dataset harus dibagi menjadi train set dan validation set.
- Ukuran validation set harus 40% dari total dataset (data training memiliki 1314 sampel, dan data validasi sebanyak 874 sampel).
- Harus mengimplementasikan augmentasi gambar.
- Menggunakan image data generator.
- Model harus menggunakan model sequential.
- Pelatihan model tidak melebihi waktu 30 menit.
- Program dikerjakan pada Google Colaboratory.
- Akurasi dari model minimal 85%.
- Dapat memprediksi gambar yang diunggah ke Colab.

Berhasil memenuhi kriteria dengan accuracy >93%

**Skills**: Klasifikasi Gambar, Machine Learning, Image Augmentation

**Tools**: Python, Tensorflow, Numpy, Mathplotlib, Import files, Zipfile

**Link Proyek** : https://github.com/klaelimunifah/IDCAMP-2023-Project/tree/ebe951926ebe39eeb8e3e69c91f9f4edd2575584/Proyek%20Akhir%20%3A%20Klasifikasi%20Gambar
   
## 2. Kelas Intermediate
### Proyek Pertama : Membuat Model NLP dengan TensorFlow
Kriteria:
- Dataset yang akan dipakai bebas, namun minimal memiliki 1000 sampel.
- Harus menggunakan LSTM dalam arsitektur model.
- Harus menggunakan model sequential.
- Validation set sebesar 20% dari total dataset.
- Harus menggunakan Embedding.
- Harus menggunakan fungsi tokenizer.
- Akurasi dari model minimal 75% pada train set dan validation set.
  
Proyek ini menggunakan dataset News Category dataset (https://www.kaggle.com/datasets/rmisra/news-category-dataset). Berhasil memenuhi seluruh kriteria yang diberikan dengan akurasi di atas 90%

**Skills**: Data Preparation, NLP Model Machine Learning, Data Visualization, Embedding, Tokenizer, Callback 

**Tools**: Python, Tensorflow, Pandas, Mathplotlib, SKLearn

**Link Proyek** : https://github.com/klaelimunifah/IDCAMP-2023-Project/tree/cb1ee8e5a507e212b9fe1423e0ed2950b0cb8e61/Proyek%20Pertama%20%3A%20Membuat%20Model%20NLP%20dengan%20TensorFlow

### Proyek Kedua : Membuat Model Machine Learning dengan Data Time Series
Kriteria:
- Dataset yang akan dipakai bebas, namun minimal memiliki 1000 sampel.
- Harus menggunakan LSTM dalam arsitektur model.
- Validation set sebesar 20% dari total dataset.
- Model harus menggunakan model sequential.
- Harus menggunakan Learning Rate pada Optimizer.
- MAE < 10% skala data.

Proyek ini menggunakan dataset LSTM-Multivariate_pollution.csv (https://www.kaggle.com/datasets/rupakroy/lstm-datasets-multivariate-univariate). Berhasil memenuhi seluruh kriteria yang diberikan dengan MAE<5% skala data.

**Skills**: Data Preparation, LSTM Model Machine Learning, Data Visualization, Callback

**Tools**: Python, Tensorflow, Pandas, Mathplotlib, SKLearn

**Link Proyek** : https://github.com/klaelimunifah/IDCAMP-2023-Project/tree/cb1ee8e5a507e212b9fe1423e0ed2950b0cb8e61/Proyek%20Kedua%20%3A%20Membuat%20Model%20Machine%20Learning%20dengan%20Data%20Time%20Series

### Proyek Akhir : Image Classification Model Deployment
Kriteria:
- Dataset yang akan dipakai bebas, namun minimal memiliki 1000 buah gambar.
- Dataset tidak pernah digunakan pada submission kelas machine learning sebelumnya.
- Dataset dibagi menjadi 80% train set dan 20% test set.
- Model harus menggunakan model sequential.
- Model harus menggunakan Conv2D Maxpooling Layer.
- Akurasi pada training dan validation set minimal sebesar 80%.
- Menggunakan Callback.
- Membuat plot terhadap akurasi dan loss model.
- Menulis kode untuk menyimpan model ke dalam format TF-Lite.

Proyek ini menggunakan Garbage dataset (https://www.kaggle.com/datasets/sumn2u/garbage-classification-v2). Berhasil memenuhi seluruh kriteria yang diberikan dengan akurasi > 95%.

**Skills**: Data Preparation, Image Classification Model Machine Learning, Data Visualization, Callback

**Tools**: Python, Tensorflow, Numpy, Mathplotlib, SKLearn, Zipfile, Pathlib

**Link Proyek** : https://github.com/klaelimunifah/IDCAMP-2023-Project/tree/cb1ee8e5a507e212b9fe1423e0ed2950b0cb8e61/Proyek%20Akhir%20%3A%20Image%20Classification%20Model%20Deployment
