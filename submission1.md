
# Laporan Proyek Machine Learning - Muchammad 'Irfan Chanif Rusydi

## Domain Proyek
Machine Learning dapat digunakan dalam berbagai bidang salah satunya peternakan. Kali ini industri susu menjadi fokus. Dengan menggunakan Machine Learning, industri susu dapat memprediksi atau mengkategorikan susu yang baik dan buruk. Dengan demikian, industri susu dapat mengurangi kerugian yang disebabkan oleh susu yang buruk. 

Pada bagian ini, kamu perlu menuliskan latar belakang yang relevan dengan proyek yang diangkat.

**Rubrik/Kriteria Tambahan (Opsional)**:
- Jelaskan mengapa dan bagaimana masalah tersebut harus diselesaikan
- Menyertakan hasil riset terkait atau referensi. Referensi yang diberikan harus berasal dari sumber yang kredibel dan author yang jelas.
  
  Format Referensi: [Judul Referensi](https://scholar.google.com/) 

## Business Understanding

Pada bagian ini, kamu perlu menjelaskan proses klarifikasi masalah.

Bagian laporan ini mencakup:

### Problem Statements

Menjelaskan pernyataan masalah latar belakang:
- Bagaimana pH, suhu, rasa, bau, lemak, kekeruhan dan warna dapat mempengaruhi kualitas susu?
- Bagaimana kualitas susu dapat diprediksi berdasarkan pH, suhu, rasa, bau, lemak, kekeruhan dan warna?
### Goals

Menjelaskan tujuan dari pernyataan masalah:
- Mengetahui pengaruh pH, suhu, rasa, bau, lemak, kekeruhan dan warna terhadap kualitas susu
- Memprediksi atau mengklasifikasikan kualitas susu berdasarkan pH, suhu, rasa, bau, lemak, kekeruhan dan warna
- Jawaban pernyataan masalah n

Semua poin di atas harus diuraikan dengan jelas. Anda bebas menuliskan berapa pernyataan masalah dan juga goals yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**:
- Menambahkan bagian “Solution Statement” yang menguraikan cara untuk meraih goals. Bagian ini dibuat dengan ketentuan sebagai berikut: 

    ### Solution statements
    - Mengajukan 2 atau lebih solution statement. Misalnya, menggunakan dua atau lebih algoritma untuk mencapai solusi yang diinginkan atau melakukan improvement pada baseline model dengan hyperparameter tuning.
    - Solusi yang diberikan harus dapat terukur dengan metrik evaluasi.

## Data Understanding
Dataset yang digunakan kali ini adalah Milk Quality Prediction Dataset. Selengkapnya dapat lihat di [sini](https://www.kaggle.com/datasets/cpluzshrijayan/milkquality).
 

### Variabel-variabel pada Milk Quality Prediction Dataset adalah sebagai berikut:
- pH : Kolom ini mendefinisikan pH susu yang berkisar antara 3 hingga 9,5 maks: 6,25 hingga 6,90
- Temperature : Kolom ini mendefinisikan suhu susu yang berkisar dari 34 C sampai 90'C max : 34'C sampai 45.20'C
- Taste : Kolom ini mendefinisikan Rasa susu yang merupakan data kategori 0 (Buruk) atau 1 (Baik) max : 1 (Baik)
- Odor : Kolom ini mendefinisikan bau susu yang merupakan data kategori 0 (Buruk) atau 1 (Baik) max : 1 (Baik)
- Fat : Kolom ini mendefinisikan Bau susu yang merupakan data kategorikal 0 (Rendah) atau 1 (Tinggi) maks : 1 (Tinggi)
- Turbidity : Kolom ini mendefinisikan Kekeruhan susu yang merupakan data kategorikal 0 (Rendah) atau 1 (Tinggi) maks : 1 (Tinggi)
- Colour : Kolom ini mendefinisikan Warna susu yang berkisar dari 240 hingga 255 maks : 255
- Grade : Kolom ini mendefinisikan Grade (Target) susu yang merupakan data kategorikal Dimana Rendah (Buruk) atau Sedang (Sedang) Tinggi (Baik)

**Rubrik/Kriteria Tambahan (Opsional)**:
- Melakukan beberapa tahapan yang diperlukan untuk memahami data, contohnya teknik visualisasi data atau exploratory data analysis.

## Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan proses data preparation yang dilakukan
- Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.

## Modeling

Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan. Anda perlu menjelaskan tahapan dan parameter yang digunakan pada proses pemodelan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan kelebihan dan kekurangan dari setiap algoritma yang digunakan.
- Jika menggunakan satu algoritma pada solution statement, lakukan proses improvement terhadap model dengan hyperparameter tuning. **Jelaskan proses improvement yang dilakukan**.
- Jika menggunakan dua atau lebih algoritma pada solution statement, maka pilih model terbaik sebagai solusi. **Jelaskan mengapa memilih model tersebut sebagai model terbaik**.

## Evaluation
Metrik evaluasi yang digunakan adalah akurasi, presisi, homogeneity score, dan rand score. Metrik akurasi adalah metrik yang digunakan untuk mengukur seberapa akurat model dalam memprediksi kelas target. Metrik presisi adalah metrik yang digunakan untuk mengukur seberapa akurat model dalam memprediksi kelas positif. Metrik homogeneity score adalah metrik yang digunakan untuk mengukur seberapa homogen cluster yang dibentuk oleh model. Metrik rand score adalah metrik yang digunakan untuk mengukur seberapa baik model dalam memisahkan data.

Pada bagian ini anda perlu menyebutkan metrik evaluasi yang digunakan. Lalu anda perlu menjelaskan hasil proyek berdasarkan metrik evaluasi yang digunakan.

Hasil model Random Forest Classifier dan Decision Tree Classifier adalah sebagai berikut:
Random Forest Classifier :
- Akurasi : 0.98
- Presisi : 0.98
- Homogeneity Score : 0.98
- Rand Score : 0.98


Sebagai contoh, Anda memiih kasus klasifikasi dan menggunakan metrik **akurasi, precision, recall, dan F1 score**. Jelaskan mengenai beberapa hal berikut:
- Penjelasan mengenai metrik yang digunakan
- Menjelaskan hasil proyek berdasarkan metrik evaluasi

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
- _Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_
- Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin di
```
