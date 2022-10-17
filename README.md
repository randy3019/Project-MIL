# Project-MIL

*******************Project Mata Kuliah Matematika Industri &amp; Lingkungan (Computer Vision)*******************

"Deteksi OBJEK(CABE) BERBASIS WARNA (PROSES MORFOLOGI) DENGAN OPENCV PYTHON"

Program ini menggunakan metode pengolahan citra deteksi warna dalam melakukan pendeteksian cabe dan membedakan sesuai kategorinya berdasarkan warna kulit cabe.
Pengolahan citra ini di jalankan menggunakan program python dan library open cv.

# Requirements

Program ini menggunakan bahasa pemrograman Python versi 3.* yang  ditulis secara "Procedural Programming" dan untuk menjalankan program dapat menggunakan Google Colaboratory.
Dataset yang diperlukan untuk menjalankan program adalah adalah 3 gambar cabe yang berbeda yaitu: cabe berwarna merah,kuning,dan hijau.


#Output Program:

Gambar Asli:

![resized](https://user-images.githubusercontent.com/59527893/196135984-62bc8eca-b2ef-4cf1-a389-ed6ab1350d16.png)


Gambar hasil konversi RGB Ke HSV:

![bgr-hsv](https://user-images.githubusercontent.com/59527893/196136145-c75b9528-b3b8-431a-ab7f-398dad181c96.png)


Gambar Hasil Thresholding:


![result](https://user-images.githubusercontent.com/59527893/196136465-c10f0f14-4b18-43ec-89a5-5a4dc957f5d0.png)


![noise](https://user-images.githubusercontent.com/59527893/196136664-8dee2a9a-c0ca-4d3c-a390-7fa9cf3f6620.png)


** Pada gambar kedua hasil Thresholding masih terdapat moise berwarna hitam, dimana noise tersebut dapat di hilangkan dengan proses morfologi yaitu erosi dan dilasi.

