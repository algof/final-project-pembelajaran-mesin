# Final Project Machine Learning

| Name           | NRP        | Kelas      | Kelompok    |
| ---            | ---        | ---------- | ---         |
| Daffa Rinali | 5025231209 | Pembelajaran Mesin (D) | Kelompok 6 |
| Algof Kristian Zega | 5025231235 | Pembelajaran Mesin (D) | Kelompok 6 |
| Filbert Hainsly Martin | 5025231256 | Pembelajaran Mesin (D) | Kelompok 6 |
| Gregorius Setiadharma | 5025231268 | Pembelajaran Mesin (D) | Kelompok 6 |
| Muhammad Davin Aulia Risky | 5025231275 | Pembelajaran Mesin (D) | Kelompok 6 |

![deskripsi-final-project](./asset/deskripsi-final-project.png)

---

## Dataset

> https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data

| Index | Feature Name         | Tipe    |
| ----- | -------------------- | ------- |
| 0     | class                | integer |
| 1     | Alcohol              | float   |
| 2     | Malic acid           | float   |
| 3     | Ash                  | float   |
| 4     | Alcalinity of ash    | float   |
| 5     | Magnesium            | float   |
| 6     | Total phenols        | float   |
| 7     | Flavanoids           | float   |
| 8     | Nonflavanoid phenols | float   |
| 9     | Proanthocyanins      | float   |
| 10    | Color intensity      | float   |
| 11    | Hue                  | float   |
| 12    | OD280/OD315          | float   |
| 13    | Proline              | float   |

---

## Features

| No. | Nama Fitur            | Tipe Data   | Deskripsi                                                                        | 
| --- | --------------------- | ----------- | -------------------------------------------------------------------------------- |
| 1   | class                 | Kategorikal | Kelas anggur (1, 2, atau 3) mewakili tiga kultivar berbeda.                      | 
| 2   | alcohol               | Numerik     | Persentase alkohol dalam volume (%) dari anggur.                                 | 
| 3   | malic\_acid           | Numerik     | Konsentrasi asam malat dalam miligram per liter (mg/L).                          | 
| 4   | ash                   | Numerik     | Kandungan abu dalam gram per liter (g/L).                                        | 
| 5   | alcalinity\_of\_ash   | Numerik     | Alkalinitas abu, diukur dengan pH dari larutan abu.                              | 
| 6   | magnesium             | Numerik     | Konsentrasi magnesium dalam miligram per liter (mg/L).                           | 
| 7   | total\_phenols        | Numerik     | Total fenol dalam miligram per liter (mg/L).                                     | 
| 8   | flavanoids            | Numerik     | Konsentrasi flavanoid dalam miligram per liter (mg/L).                           | 
| 9   | nonflavanoid\_phenols | Numerik     | Konsentrasi fenol non-flavanoid dalam miligram per liter (mg/L).                 | 
| 10  | proanthocyanins       | Numerik     | Konsentrasi proantosianin dalam miligram per liter (mg/L).                       | 
| 11  | color\_intensity      | Numerik     | Intensitas warna anggur, diukur dengan absorbansi pada panjang gelombang 420 nm. | 
| 12  | hue                   | Numerik     | Hue anggur, diukur dengan absorbansi pada panjang gelombang 520 nm.              | 
| 13  | od280/od315           | Numerik     | Rasio absorbansi pada panjang gelombang 280 nm dan 315 nm.                       | 
| 14  | proline               | Numerik     | Konsentrasi prolin dalam miligram per liter (mg/L).                              | 

---

## Algoritma Supervised Learning (Klasifikasi)

| Algoritma                  | Catatan                                                                 |
|----------------------------|-------------------------------------------------------------------------|
| **Decision Tree**          | Klasifikasi jenis wine                                                  |
| **K-Nearest Neighbor**     | Klasifikasi jenis wine                                                  |
| **Naive Bayes**            | Klasifikasi jenis wine                                                  |
| **Logistic Regression**    | Klasifikasi jenis wine                                                  |
| **Random Forest**          | Ensemble dari banyak Decision Tree, cocok untuk meningkatkan akurasi    |
| **XG Boost**               | Gradient boosting yang kuat untuk klasifikasi dengan performa tinggi    |
| **Support Vector Machine** | Multiclass dengan SVM One-vs-One                                        |