# Deteksi Retinopati Diabetik Menggunakan Transfer Learning dengan CNN & RCNN

## Anggota Kelompok

1. Inayah Ayu Deswita – 1227050058 
2. Marisah Lofiana – 1227050068  
3. Muhamad Fazar Rizky Ardianto – 1227050077  

## Deskripsi Proyek

Proyek ini bertujuan untuk membandingkan kinerja beberapa model deep learning yang menggunakan pendekatan *transfer learning, yaitu EfficientNetB0, ResNet50, dan DenseNet121, dalam mendeteksi **Retinopati Diabetik (RD)* melalui citra fundus retina. RD merupakan salah satu komplikasi serius dari diabetes dan menjadi penyebab utama kebutaan yang dapat dicegah.

Penelitian ini menggabungkan *Convolutional Neural Network (CNN)* sebagai arsitektur dasar, dan mengeksplorasi penerapan *Region-based CNN (RCNN)* untuk deteksi serta lokalisasi lesi retina. Dataset yang digunakan berasal dari Kaggle: [Diagnosis of Diabetic Retinopathy](https://www.kaggle.com/datasets/pkdarabi/diagnosis-of-diabetic-retinopathy).

### Fitur Utama
- Preprocessing gambar fundus retina (resizing, CLAHE, normalisasi)
- Augmentasi data (rotasi, flipping, zooming, brightness adjustment)
- Pelatihan model dengan transfer learning (EfficientNetB0, ResNet50, DenseNet121)
- Evaluasi model menggunakan akurasi, presisi, recall, F1-score, AUC-ROC
- Visualisasi hasil prediksi dan Grad-CAM untuk interpretasi model

### Hasil Akurasi (Pengujian):
| Model           | Akurasi | F1-Score |
|----------------|---------|----------|
| DenseNet121     | 97%     | 0.97     |
| EfficientNetB0  | 94%     | 0.94     |
| ResNet50        | 94%     | 0.94     |

### Tools & Framework:
- Python 3.x
- TensorFlow / Keras
- OpenCV
- Google Colab (GPU Tesla T4/P100)

