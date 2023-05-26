# Least Squares Generative Adversarial Network with Spectral Normalization (LSGAN-SN)

Repositori ini berisi implementasi model Least Squares Generative Adversarial Network with Spectral Normalization (LSGAN-SN) untuk pembangkitan gambar.

## Pendahuluan

LSGAN-SN merupakan varian dari model Generative Adversarial Network (GAN) yang menggunakan fungsi kerugian least squares dan normalisasi spektral untuk menstabilkan proses pelatihan dan meningkatkan kualitas gambar yang dihasilkan. Model LSGAN-SN terdiri dari generator dan discriminator, yang dilatih secara adversarial untuk menghasilkan gambar-gambar realistis.

## Arsitektur Model

Model LSGAN-SN terdiri dari komponen-komponen berikut:

- `Generator`: Kelas ini mendefinisikan arsitektur modul generator, yang digunakan untuk menghasilkan gambar-gambar baru.

- `Discriminator`: Kelas ini mendefinisikan arsitektur modul discriminator, yang bertugas membedakan antara gambar-gambar asli dan yang dihasilkan.

## Dependensi

- Python (>=3.6)
- PyTorch (>=1.8.0)

