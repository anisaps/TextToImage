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

## Alur Sistem
![image](https://github.com/anisaps/TextToImage/assets/72723369/cfe85c12-677e-4cb4-b7d2-5d80846c741f)

## Hasil Training
![image](https://github.com/anisaps/TextToImage/assets/72723369/045d5415-06f8-4af3-a281-6f342d8bde14)	 


## Referensi
[1] Dong, H., Zhang, J., Mcilwraith, D., & Guo, Y. (2017). I2T2I: LEARNING TEXT TO IMAGE SYNTHESIS WITH TEXTUAL DATA AUGMENTATION. IEEE Conference Proceeding. https://ieeexplore.ieee.org/abstract/document/8296635/

[2] Hossain, M. Z., Sohel, F., Shiratuddin, M. F., Laga, H., & Bennamoun, M. (2021). Text to Image Synthesis for Improved Image Captioning. IEEE Access, 9, 64918–64928. https://doi.org/10.1109/ACCESS.2021.3075579

[3] Lin, Z., Sekar, V., & Fanti, G. (2014). Why Spectral Normalization Stabilizes GANs : Analysis and Improvements.

[4] Mao, X., Li, Q., Xie, H., Lau, R. Y. K., Wang, Z., & Smolley, S. P. (2017). Least Squares Generative Adversarial Networks. Proceedings of the IEEE International Conference on Computer Vision, 2017-Octob, 2813–2821. https://doi.org/10.1109/ICCV.2017.304

[5] Reed, S., Akata, Z., Yan, X., Logeswaran, L., Schiele, B., & Lee, H. (2016). Generative adversarial text to image synthesis. 33rd International Conference on Machine Learning, ICML 2016, 3, 1681–1690.

[6] Vo, D. M., & Sugimoto, A. (2022). Paired-D ++ GAN for image manipulation with text. Machine Vision and Applications, 33(3), 1–15. https://doi.org/10.1007/s00138-022-01298-7

[7] Zhang, Z., Yu, W., Jiang, N., & Zhou, J. (2021). Text To Image Synthesis With Erudite Generative Adversarial Networks. Proceedings - International Conference on Image Processing, ICIP, 2021-September, 2438–2442. https://doi.org/10.1109/ICIP42928.2021.9506487
[8] Zisserman, M.-E. N. A. (n.d.). 102 Category Flower Dataset. Retrieved May 15, 2023, from https://www.robots.ox.ac.uk/~vgg/data/flowers/102/https://www.robots.ox.ac.uk/~vgg/data/flowers/102/

