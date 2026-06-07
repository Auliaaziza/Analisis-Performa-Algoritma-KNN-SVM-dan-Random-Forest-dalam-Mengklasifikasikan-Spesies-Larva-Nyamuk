# Analisis-Performa-Algoritma-KNN-SVM-dan-Random-Forest-dalam-Mengklasifikasikan-Spesies-Larva-Nyamuk

Project ini untuk memenuhi tugas akhir Mata Kuliah Pembelajaran Mesin, Semester Genap 2025/2026, Kelas 2024D, Universitas Negeri Surabaya. Project ini membandingkan performa algoritma KNN, SVM, dan Random Forest dalam mengklasifikasikan spesies larva nyamuk Aedes aegypti dan Culex quinquefasciatus menggunakan ekstraksi fitur tekstur berbasis GLCM.

## Dataset
MLMI-2024 (Mosquito Larvae Microscopic Images)  
https://data.mendeley.com/datasets/pgby6jmtp4

## Anggota
- Nia Ayu Agustin (24031554081)
- Aulia Aziza (24031554102)

## Metode
- Preprocessing: Resize 128x128, Grayscale, Normalisasi
- Augmentasi: Flip, Rotasi, Gaussian Noise, Brightness
- Ekstraksi Fitur: GLCM (48 fitur)
- Model: KNN, SVM (RBF), Random Forest
- Evaluasi: Accuracy, Precision, Recall, F1-Score
  
## Hasil
SVM menjadi model terbaik dengan akurasi 90,63%, unggul dibandingkan Random Forest dan KNN K=19 yang sama-sama mencapai 83,13%, serta KNN Best dengan akurasi 82,50%. Secara keseluruhan, SVM terbukti paling efektif dalam mengklasifikasikan spesies larva nyamuk berbasis fitur GLCM.
