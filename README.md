# learntic-machinelearning
Pengembangan Learntic bagian machine learning

Machine Learning Workflow

## Machine Learning Workflow

### Data Preparation
- [x] Tambah Kasus yang bervariasi (Murid dengan nilai yang rendah & tinggi)
- [x] Tambah Kolom Absensi (jika tersedia atau buat simulasi)
- [x] Hapus kolom yang tidak digunakan pada pelatihan (contoh: nama, id_siswa)


### Feature Engineering
- [x] Hitung nilai rata-rata per siswa
- [x] Tambah fitur tren peningkatan/penurunan nilai
- [ ] Tambah fitur statistik (maksimum, minimum, std)

### Model Development (Compliance Focus)
- [ ] Normalisasi nilai (0–100 → 0–1) jika diperlukan
- [ ] Splitting Data (Train/Test: 80/20)
- [ ] Gunakan TensorFlow untuk membangun model prediksi (multi-output regression)
- [ ] Jangan menggunakan model dari TensorFlow Hub / API lain
- [ ] Aplikasikan PCA untuk ngereduce dimensionality?
- [ ] Latih model menggunakan cross-validation
- [ ] Simpan model (`.h5` atau `SavedModel`) untuk inference

Plan B (Kalau modelnya jelek..)
- [ ] Gunakan Transfer Learning?

### Evaluation
- [ ] Evaluasi model: MAE, RMSE, R²
- [ ] Visualisasi hasil prediksi vs nilai asli

### Inference & Integration
- [ ] Buat kode inference sederhana (`predict_student.py`)
- [ ] Pastikan input dapat diterima dari UI atau API
- [ ] Tampilkan hasil prediksi ke dashboard

