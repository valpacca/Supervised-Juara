# Supervised-Juara
1. Data yang digunakan adalah data e-commerce shipping data dari Kaggle: https://www.kaggle.com/datasets/prachi13/customer-analytics
2. Model digunakan untuk memprediksi ketepatan waktu pengiriman barang pada sebuah e-commerce
3. Dilakukan 3 tahapan pada data yaitu, EDA, Pre-Processing dan penentuan model machine learning.
4. Dilakukan encoding pada beberapa feature kategori yang bertipe string
5. Pada data skew dilakukan feature transformation dengan metode log transformati dan squared transformation feature
6. Feature dengan korelasi < 0.01 didrop untuk menghindari curse of dimensionality
7. Data displit 75% untuk data train dan 25% untuk data test.
8. Model evaluation yang digunakan adalah Precision dengan tujuan meminimalisir false positive
9. Model terbaik yang digunakan adalah Support Vector Machine (SVM) dengan nilai presisi 0.87 untuk train dan 0.86 untuk test
10. Feature importance dari model tersebut adalah Weight_in_gms dan Discount_offered yang sudah distandarisasi
