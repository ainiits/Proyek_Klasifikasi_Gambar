# Proyek Klasifikasi Gambar: Buah-buahan (Fruits Classification🍇)
Ini adalah proyek akhir dari kelas "Belajar Pengembangan Machine Learning". Lokasi proyek ini terdapat pada folder `Submission-Klasifikasi-Gambar` yang didalamnya terdapat file `requirements.txt`.

## Download Dataset
Dataset yang digunakan dalam proyek ini berasal dari Kaggle dan diunduh langsung melalui Google Colab. 
Adapun langkah-langkah untuk mengunduh dataset melalui Google Colab, yaitu:
1. Daftar kemudian login menggunakan akun Kaggle
2. Buat API Token dari halaman akun Kaggle, kemudian unduh file `kaggle.json`
3. Uploud `kaggle.json` ke Google Colab, lalu jalankan perintah berikut:
   ```
   !pip install -q kaggle
   !mkdir -p ~/.kaggle
   !cp kaggle.json ~/.kaggle/
   !chmod 600 ~/.kaggle/kaggle.json

   !kaggle datasets download -d utkarshsaxenadn/fruits-classification
   !unzip fruits-classification.zip -d fruits_dataset
   ```
