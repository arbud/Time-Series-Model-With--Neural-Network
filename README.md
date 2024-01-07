# Time-Series-Model-With--Neural-Network
Project Membuat Model Machine Learning Time Series dengan Neural Network, Proyek berikut dibuat berdasarkan tugas course "Belajar Pengembangan Machine Learning" sebagai syarat kelulusan course dan untuk memperoleh sertifikasi kompetensi Machine Learning.

Pertama-tama dalam proyek ini saya menggunakan dataset yang diperoleh dari [Kaggle](https://www.kaggle.com/) yaitu dataset [Electric Power Consumption](https://www.kaggle.com/datasets/fedesoriano/electric-power-consumption) yang diperoleh dari User Kaggle Bernama Fedesoriano.

Dataset dari link kaggle tersebut akan dicopy API nya untuk diambil datanya berikut API dari Electric Power Consumption : (kaggle datasets download -d fedesoriano/electric-power-consumption).

Tujuan dari proyek ini adalah dapat membangun model Machine Learning Time Series untuk menganalisis dari suatu label yaitu Humidity (Kelembapan) terhadap konsumsi daya listrik yang diperoleh dari rentang tanggal 1 January 2017 - 30 December 2017. Total data berjumlah 52.416 record dengan kolom yang digunakan adalah kolom Datetime dan kolom Hum.

Dalam pembangunan model menggunakan arsitektur LSTM dan menggunakan model sequential, dataset dibagi menjadi 80% merupakan data train dan 20% merupakan data validation, data preprocessing menggunakan standardscaler dan model evaluation dengan menggunakan MAE dengan threshold <10% skala data.
