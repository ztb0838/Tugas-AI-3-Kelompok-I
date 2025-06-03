# Tugas-AI-3-Kelompok-I
# Tutorial
- Ketika pada code baris ke dua atau " from google.colab import files
uploaded = files.upload() " maka masukkan file wdbc.data
# Deskripsi
Proyek ini bertujuan untuk memprediksi apakah suatu tumor bersifat ganas (malignant) atau jinak (benign) berdasarkan data medis pasien. Dataset yang digunakan merupakan dataset umum dari Wisconsin Diagnostic Breast Cancer (WDBC) yang sering digunakan dalam studi klasifikasi.

**Dataset**
Dataset terdiri dari 569 sampel tumor, masing-masing dengan 30 fitur numerik yang dihasilkan dari citra digital hasil biopsi sel payudara. Fitur-fitur tersebut mencakup karakteristik statistik seperti:
- Rata-rata ukuran (radius_mean, area_mean)
- Tekstur (texture_mean)
- Bentuk (smoothness_mean, compactness_mean, concavity_mean)
- Nilai ekstrim (fitur *_worst menunjukkan nilai maksimum dari setiap karakteristik)

Setiap baris data juga memiliki label diagnosis:
- **M** (Malignant): Tumor ganas
- **B** (Benign): Tumor jinak

**Metode Klasifikasi**
Model yang digunakan untuk klasifikasi adalah Random Forest Classifier, yaitu algoritma berbasis ensemble yang menggabungkan banyak pohon keputusan untuk menghasilkan prediksi yang stabil dan akurat.

**Hasil Evaluasi**
Model dilatih dan diuji menggunakan pembagian data train/test. Berdasarkan hasil evaluasi:
![image](https://github.com/user-attachments/assets/79e07a1f-bdf1-477b-a8c9-d365a3b55553)
![AI3](https://github.com/user-attachments/assets/49fa3278-152b-4066-b1f5-b999e0127817)

- Akurasi keseluruhan: 96%
- Model sangat andal dalam mengenali tumor jinak maupun ganas
- F1-score menunjukkan keseimbangan yang baik antara precision dan recall

**Kesimpulan**
Model klasifikasi yang dibangun berhasil memprediksi jenis tumor dengan tingkat akurasi yang sangat tinggi. Ini menunjukkan bahwa pendekatan berbasis machine learning, khususnya Random Forest, sangat efektif dalam deteksi dini kanker payudara dan dapat digunakan sebagai alat bantu diagnosis oleh tenaga medis.

