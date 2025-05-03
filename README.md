# 🧠 Brain Tumor MRI Classification

Proyek ini bertujuan untuk memenuhi proyek kelas Belajar Pengembangan Machine Learning dengan membangun sebuah model klasifikasi otomatis berdasarkan citra **MRI otak** menggunakan metode **Deep Learning**. Model ini dapat mengenali dan mengklasifikasikan jenis tumor otak berdasarkan gambar MRI ke dalam empat kategori utama.
Adapun dataset yang digunakan: https://www.kaggle.com/datasets/tombackert/brain-tumor-mri-data 

## 🎯 Tujuan
Mengembangkan model klasifikasi citra yang dapat:
- Mendeteksi keberadaan tumor otak.
- Mengidentifikasi jenis tumor berdasarkan citra MRI.

## 🧾 Deskripsi Dataset
Dataset berisi gambar MRI otak yang telah dikategorikan ke dalam 4 kelas berikut:
- **Glioma**  
  Tumor otak primer yang berasal dari jaringan otak, bersifat agresif dan sering memerlukan penanganan medis intensif.
- **Meningioma**  
  Tumor jinak yang tumbuh di **meninges**, yaitu selaput pelindung otak dan sumsum tulang belakang. Pertumbuhannya lambat dan umumnya tidak menyebar.
- **No Tumor**  
  Gambar MRI dari otak yang sehat tanpa indikasi adanya tumor.
- **Pituitary**  
  Tumor yang tumbuh di **kelenjar pituitari**. Umumnya bersifat jinak, tetapi dapat memengaruhi fungsi hormonal tubuh.

## 🛠️ Tools & Teknologi
- Python
- TensorFlow & Keras
- Scikit-learn
- Matplotlib
- Google Colaboratory

## 🚀 Output
- Model terlatih dalam format `SavedModel` (`saved_model.pb`), `.tflite`, dan `.json`)
- Visualisasi hasil klasifikasi

