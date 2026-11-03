# Eksperimen Encoder dan Scaler Data Pencapaian Kecepatan
Eksperimen dengan menggunakan encoder dan scaler untuk memprediksi data pencapaian kecepatan koridor Jakarta tahun 2019 (gabungan 12 bulan) dengan regresi linear, lalu membandingkan MAE (rata-rata dan standar deviasi dari cross validation).

1. Menghitung akurasi model regresi linear (menggunakan cross validation) tanpa menggunakan scaling maupun encoder.
2. Menghitung akurasi model dengan normalisasi, standarisasi dan robust scaler, menggunakan cross validation.
3. Menggunakan One Hot Encoder dan Ordinal Encoder terhadap dataset untuk fitur kategorikal.
4. Kombinasi transformasi data untuk semua fitur.
5. Membandingkan akurasi setiap skenario.
