# Mathematics for AI – K-Nearest Neighbor (KNN)

## Deskripsi
Repository ini berisi proyek Ujian Akhir Semester (UAS) mata kuliah **Mathematics for AI**.  
Proyek ini bertujuan untuk menerapkan konsep matematika dalam kecerdasan buatan menggunakan algoritma **K-Nearest Neighbor (KNN)** untuk memprediksi kelulusan mahasiswa.

## Dataset
Dataset disimpan dalam file Excel dan terdiri dari data mahasiswa dengan variabel:
- **Jam Belajar (X1)**
- **Kehadiran (%) (X2)**
- **Kelas (Y)**: Lulus dan Tidak Lulus

Data digunakan sebagai input untuk proses klasifikasi menggunakan metode KNN.

## Metode
Algoritma yang digunakan adalah **K-Nearest Neighbor (KNN)** dengan tahapan sebagai berikut:
1. Membaca dataset dari file Excel
2. Menentukan nilai K
3. Menghitung jarak menggunakan rumus Euclidean
4. Menentukan kelas berdasarkan mayoritas tetangga terdekat
5. Menampilkan hasil prediksi dan akurasi model

## Implementasi
Program diimplementasikan menggunakan:
- Python
- Pandas
- NumPy
- Scikit-learn

Kode program terdapat pada file **knn.ipynb**.

## Hasil
Hasil pengujian menunjukkan bahwa algoritma KNN mampu mengklasifikasikan kelulusan mahasiswa dengan cukup baik berdasarkan jam belajar dan tingkat kehadiran.

## Struktur Repository
uas-mathematic-for-ai
│
├── Data dan Perhitungan.xlsx
├── knn.ipynb
├── Andre_Firmansyah_105841101123_5AI-B_Mathematic_AI.pdf
└── README.md


## Penulis
**Andre Firmansyah**  
NIM: 105841101123  
Program Studi Informatika  
Universitas Muhammadiyah Makassar
