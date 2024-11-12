Skin Cancer Detection API
REST API ini digunakan untuk mendeteksi jenis kanker kulit berdasarkan gambar yang diunggah. Aplikasi ini menerima gambar kulit, melakukan prediksi dengan model Machine Learning, dan mengembalikan jenis kanker kulit yang teridentifikasi.

Fitur
Menerima file gambar melalui endpoint /scan
Memprediksi jenis kanker kulit menggunakan model ML
Mengembalikan hasil prediksi sebagai respon JSON
Persyaratan

Node.js
Model Machine Learning dalam format TensorFlow.js (tfjs-node)