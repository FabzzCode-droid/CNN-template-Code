# CNN-template-Code
📌 Deskripsi
Proyek ini merupakan bagian dari program belajar 30 hari AI praktis tanpa matematika kompleks. Fokus utama proyek ini adalah memahami konsep dan praktik dasar Convolutional Neural Network (CNN) menggunakan dataset MNIST — kumpulan gambar angka tulisan tangan dari 0 hingga 9.

🧪 Apa yang Dilakukan:
Menggunakan Keras (TensorFlow) untuk membangun arsitektur CNN sederhana.

Melatih model dengan dataset train dan mengevaluasi pada test.

Menerapkan 4 lapisan utama CNN: Conv2D, MaxPooling2D, Flatten, Dense.

Menggunakan batch training (batch size = 32) per epoch untuk efisiensi komputasi.

Mengevaluasi performa model dengan metrik akurasi dan visualisasi loss/accuracy per epoch.

🖼️ Dataset
MNIST dari keras.datasets

Total gambar: 60,000 (train), 10,000 (test)

Gambar hitam putih ukuran 28×28 piksel

⚙️ Tools & Library
Python

TensorFlow / Keras

Matplotlib (untuk visualisasi)

🔍 Insight Pribadi
Melalui latihan ini, saya belajar bahwa CNN mampu mengenali pola visual dari data gambar secara efisien. Teknik batch training sangat krusial untuk melatih model secara stabil, terutama saat jumlah data besar. Praktik ini membuka wawasan saya tentang bagaimana model mengenali angka hanya dari piksel.

📈 Hasil
Akurasi training dan testing stabil dan tinggi

Model mampu mengenali angka tulisan tangan dengan performa baik

Visualisasi training loss dan accuracy menunjukkan learning yang konsisten
