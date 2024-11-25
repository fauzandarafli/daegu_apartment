# Prediksi Harga Apartemen di Daegu, Korea Selatan

## Deskripsi Proyek
Proyek ini menggunakan *dataset* Daegu Apartment untuk menganalisis faktor-faktor yang memengaruhi harga apartemen di Daegu, Korea Selatan. Dengan atribut seperti tipe apartemen, jarak ke stasiun *subway* terdekat, fasilitas di sekitar, ukuran apartemen, dan tahun pembangunan, proyek ini bertujuan untuk membangun model prediktif yang dapat memperkirakan harga apartemen secara akurat. Model ini akan membantu dalam pengambilan keputusan strategis terkait harga jual atau pembelian apartemen di wilayah tersebut.

Proyek ini adalah bagian dari **Capstone Project Module 3** dalam program **Data Science di Purwadhika Jakarta**.

## Tujuan Proyek
- Membangun model prediktif untuk memprediksi harga apartemen di Daegu.
- Menganalisis faktor-faktor yang memengaruhi harga apartemen.
- Membantu pemilik properti atau agen dalam menetapkan harga jual yang ideal dan kompetitif.

## Konten
1. **Business Problem Understanding**: Memahami masalah yang dihadapi dalam penetapan harga apartemen yang ideal.
2. **Data Understanding and Exploratory Data Analysis (EDA)**: Menganalisis dan memahami data yang tersedia.
3. **Data Preprocessing**: Proses pembersihan dan persiapan data untuk analisis lebih lanjut.
4. **Modeling**: Membangun dan melatih model regresi untuk memprediksi harga apartemen.
5. **Conclusion**: Menyimpulkan temuan dari analisis dan hasil model.
6. **Recommendation**: Memberikan rekomendasi berbasis data untuk strategi penetapan harga apartemen.

## Latar Belakang
Daegu adalah kota terbesar keempat di Korea Selatan dengan lebih dari 2,4 juta penduduk. Kepadatan penduduk yang tinggi menjadikan apartemen sebagai pilihan utama untuk hunian. Namun, banyak pemilik apartemen yang kesulitan dalam menetapkan harga jual yang tepat, yang dapat mengarah pada kesulitan dalam menjual atau merugi.

Proyek ini bertujuan untuk mengatasi masalah tersebut dengan membangun model prediktif yang dapat memperkirakan harga apartemen berdasarkan berbagai faktor internal (seperti ukuran dan fasilitas apartemen).

## Metode Evaluasi
Model regresi yang dibangun akan dievaluasi menggunakan beberapa metrik:
- **RMSE (Root Mean Squared Error)**: Mengukur kesalahan prediksi dalam bentuk akar kuadrat dari rata-rata kesalahan.
- **MAE (Mean Absolute Error)**: Menghitung rata-rata kesalahan prediksi tanpa memperhatikan arah kesalahan.
- **MAPE (Mean Absolute Percentage Error)**: Menunjukkan persentase kesalahan prediksi.
- **R-Squared (R2)**: Mengukur seberapa baik model menjelaskan variabilitas data.

Semakin kecil nilai RMSE, MAE, dan MAPE, semakin baik akurasi model dalam memprediksi harga apartemen.

## Instalasi
Untuk menjalankan proyek ini, Anda memerlukan beberapa pustaka Python, seperti:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Anda dapat menginstalnya menggunakan pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
