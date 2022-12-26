# Submission 1: Pendeteksi Berita Palsu
Nama: Hanif Al Irsyad

Username dicoding: hanifanta

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Fake News Dataset for Machine Learning](https://www.kaggle.com/datasets/bipulnath98/fake-news-dataset-for-machine-learning) |
| Masalah | Berita palsu adalah informasi yang tersebar di media massa atau melalui internet yang tidak benar atau tidak sesuai dengan kenyataan. Berita palsu dapat tersebar dengan cepat melalui media sosial atau aplikasi chatting, dan dapat memiliki dampak negatif yang signifikan terutama jika informasi yang disebarkan merupakan propaganda atau berisi fitnah atau hoax yang dapat menimbulkan kepanikan atau kekacauan di masyarakat. |
| Solusi machine learning | Berdasar deskripsi masalah yang sudah disebutkan, maka diperlukan sistem machine learning guna untuk melakukan klasifikasi sebuah berita benar atau palsu. |
| Metode pengolahan | Persiapan data: Tahap ini meliputi pengumpulan data berita yang telah terverifikasi kebenarannya, pemilihan algoritma klasifikasi yang sesuai, dan pembagian data latihan dan data uji. Preprocessing data: Tahap ini meliputi pembersihan data dari noise atau informasi yang tidak relevan, serta pengubahan data ke dalam bentuk yang lebih sesuai untuk diolah oleh algoritma klasifikasi. Pelatihan model: Tahap ini meliputi proses pelatihan algoritma klasifikasi dengan menggunakan data latihan yang telah disiapkan. Proses ini akan menghasilkan model yang mampu mengklasifikasi berita baru dengan menggunakan pola-pola yang telah ditemukannya. Evaluasi model: Tahap ini meliputi proses menguji kemampuan model yang telah dilatih dengan menggunakan data uji. Hasil evaluasi ini akan memberikan informasi tentang akurasi model dalam mengklasifikasi berita baru. Fine-tuning model: Jika hasil evaluasi menunjukkan bahwa model masih kurang akurat, maka perlu dilakukan fine-tuning terhadap model dengan cara mengubah hiperparameter-nya atau dengan menambahkan data latihan yang lebih banyak dan beragam. |
| Arsitektur model | Model yang dibangun menggunakan layer TextVectorization yang akan memproses input string kedalam bentuk susunan angka, kemudian layer Embedding yang bertugas untuk mempelajari kemiripan dari sebuah kata yang berguna untuk mengetahui apakah kata tersebut merupakan kata negatif atau kata positif. |
| Metrik evaluasi | Metric yang digunakan pada model yaitu BinaryAccuracy, TruePositive, FalsePositive, TrueNegative, FalseNegative untuk mengevaluasi performa model dalam menentukan klasifikasi. |
| Performa model | Model yang dibuat menghasilkan performa yang cukup baik dalam memberikan prediksi untuk text berita yang diinputkan, dan dari pelatihan yang dilakukan model menghasilkan binary_accuracy dan val_binary_accuracy di sekitar 89% |
