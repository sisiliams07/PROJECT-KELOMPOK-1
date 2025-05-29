# PROJECT-KELOMPOK-1
Dalam proyek ini, kami memulai dengan menyiapkan dataset klasifikasi SMS spam mandiri yang berisi data dalam format CSV. Kami kemudian melakukan *Exploratory Data Analysis* (EDA) tahap pertama untuk memahami karakteristik awal data, seperti distribusi label (normal, promo, penipuan), deteksi duplikat, dan panjang teks, guna menentukan metode *preprocessing* yang sesuai.

Tahap *preprocessing* dilakukan dengan serangkaian langkah seperti *case folding*, normalisasi kata, penghapusan *stopword*, *stemming*, dan penyusunan pipeline. Setelah itu, kami melakukan EDA tahap kedua untuk mengevaluasi hasil pembersihan, termasuk analisis ulang panjang teks dan kata-kata yang paling sering muncul.

Pada tahap *feature engineering*, teks yang telah dibersihkan diubah menjadi fitur numerik menggunakan metode TF-IDF dan N-Gram, serta dilakukan seleksi fitur menggunakan Chi-Square. Model kemudian dibangun menggunakan algoritma SVM (*Support Vector Machine*) dengan kernel linear, dan melalui proses validasi serta evaluasi.

Terakhir, model diimplementasikan dalam aplikasi berbasis web menggunakan Streamlit, yang memungkinkan pengguna menginput teks SMS dan mendapatkan hasil klasifikasi secara interaktif.
