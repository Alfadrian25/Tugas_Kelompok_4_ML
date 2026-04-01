# 🚀 OpenCV Object Detection - Machine Learning Practice

## 📌 Deskripsi

Project ini merupakan hasil praktikum **Machine Learning menggunakan OpenCV** dengan fokus pada **Object Detection menggunakan Cascade Classifier**.

Cascade Classifier adalah metode deteksi objek berbasis fitur Haar yang digunakan untuk mendeteksi berbagai objek seperti wajah, mata, senyum, kendaraan, dan tubuh manusia.

---

## 🎯 Fitur Utama

✅ Face Detection (Deteksi Wajah)  
✅ Eye Detection (Deteksi Mata)  
✅ Smile Detection (Deteksi Senyum)  
✅ Real-time Detection (Kamera)  
✅ Cars Detection (Deteksi Kendaraan)  
✅ Full Body Detection (Deteksi Tubuh)  
✅ Custom Bounding Box (draw_ped)

---

## 🛠️ Teknologi yang Digunakan

- Python
- OpenCV (cv2)
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 Struktur Repository


Tugas_Kelompok_4_ML/
│
├── OpenCV_4.ipynb
├── haarcascades/
│ ├── haarcascade_frontalface_default.xml
│ ├── haarcascade_eye.xml
│ ├── haarcascade_smile.xml
│ ├── cars.xml
│ └── haarcascade_fullbody.xml
│
| ├── results/
|
│ ├── lena.jpg
│ ├── family.jpg
│ ├── cars2.jpg  
|
│
├── videos/
│ ├── cars_video.mp4
│ ├── pedestrians.mp4
│
└── README.md


---

## ⚙️ Cara Menjalankan

1. Clone repository ini:
```bash
git clone https://github.com/Alfadrian25/opencv-object-detection.git

Install dependencies:

pip install opencv-python numpy matplotlib

Jalankan file notebook atau script Python

📊 Penjelasan Singkat
🔹 Cascade Classifier

Cascade Classifier adalah metode deteksi objek berbasis fitur Haar yang diperkenalkan oleh Viola-Jones Algorithm.

🔹 Cara Kerja
Menggunakan fitur Haar
Menggunakan classifier berlapis (cascade)
Mengscan gambar pada berbagai ukuran

🎥 Video Presentasi

📌 Link YouTube:

Masukkan link video di sini


🧠 Kesimpulan
Cascade Classifier merupakan metode deteksi objek yang cepat dan efisien
OpenCV menyediakan banyak model siap pakai (.xml)
Dapat digunakan untuk gambar, video, dan real-time kamera
Dapat dikembangkan untuk custom object detection

👥 Anggota Kelompok
Alfadrian Januarsyah  (231001067)
Tasri Zulfitriyati    (231001074)
M. Irvan Maulana P.   (231001071)
Nabila Isnaeni        (231001054)
Silvia Fasya Aprilian (231001002)

📌 Catatan

Project ini dibuat untuk memenuhi tugas praktikum Machine Learning.

⭐ Credits

OpenCV Documentation
Haar Cascade Classifier
Viola-Jones Algorithm
