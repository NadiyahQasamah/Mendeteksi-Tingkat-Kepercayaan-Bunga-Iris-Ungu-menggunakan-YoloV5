# Mendeteksi Tingkat Kepercayaan Bunga Iris Ungu menggunakan YOLOv5
Metode yang digunakan dalam mendeteksi bunga iris ungu :

![image](https://github.com/user-attachments/assets/5152613c-5788-44d3-89de-723744e9ab12)

1. Pengumpulan data dilakukan dengan tujuan memperoleh dataset sebanyak 150 gambar/citra dengan menggunakan bahasa pemrograman _Python_
2. Processing data melibatkan tahapan _labelling_ dataset dengan tujuan menandai objek yang diteliti dengan dikelompokan berdasarkan jenisnya.
3. Merancang Yolo
Peracancangan dibuat dengan mengkloning repository YOLOv5 dan mendapatkan klasifikasi sebanyak 8 kelas

![image](https://github.com/user-attachments/assets/cf141b35-a84d-4604-a235-f6c0cb6da14a)

4. Percobaan
Percobaan dilakukan dengan memasukkan data setelah dilakukan klasifikasi dan mengujinya dengan penerapan algoritma YOLOv5 pada _google colab_

# Hasil Pembahasan
Dari hasil yang dilakukan terdapat pembagian gambar/citra sebanyak 88% _training data_, 8% _valid data_, 4% _testing data_. Dengan menggunakan _img_ 416, _batch_ 8 dan _epochs_ 80. memperoleh grafik model _training_ dan validasi

![image](https://github.com/user-attachments/assets/98987217-14e0-4e99-a65d-3c18a9c05b14)

Serta terdapat output berupa kurva _precision-recall_ dengan kurva tertinggi paling tinggi yaitu bunga iri ungu, dapat dikatakan kinerja model berjalan dengan baik pada saat mengenali objek yang diuji

![image](https://github.com/user-attachments/assets/22b23d9b-ccac-4014-a5c2-932b20f92cac)

# Hasil dengan mendeteksi gambar
Mendeteksi Bunga iris ungu dengan memasukan gambar sehingga mendapatkan tingkat kepercayaan 92%

![image](https://github.com/user-attachments/assets/a5205213-c249-4fd4-a8a4-da517551991a)

Mendeteksi Bunga iri ungu secara _real time_ dengan tingkat kepercayaan 86%

![image](https://github.com/user-attachments/assets/881e7ffb-f9c3-4283-8a91-3f09e899bc1e)
