Proyek Akhir : Klasifikasi Gambar Gunting Batu Kertas
A.	Pengantar
Dalam course “Belajar Machine Learning untuk Pemula” bersama Dicoding Academy, saya mempelajari dasar-dasar machine learning dan bagaimana jaringan saraf bekerja. Untuk bisa lulus dari course ini, saya harus mengirimkan submission berupa program jaringan saraf tiruan menggunakan TensorFlow. Program saya harus mampu mengenali bentuk tangan yang membentuk gunting, batu, atau kertas.

B.	Dataset
Dataset yang dipakai adalah dataset berikut : rockpaperscissors, atau gunakan link ini pada wget command: https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip.
Proyek ini merupakan proyek klasifikasi 3 kelas (rock, scissors, and paper) dengan total 2188 image samples.

C.	Perancangan model
•	Dataset dibagi menjadi train set dan validation set (60:40)
•	Model mengimplementasikan augmentasi gambar, image data generator, dan model sequential
•   Menggunakan optimizer dan loss function
•	Model menggunakan transfer learning VGG16 dan Resnet50
•	Akurasi yang diperoleh >95%

