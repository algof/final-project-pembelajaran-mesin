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

> https://archive.ics.uci.edu/dataset/186/wine+quality

---

## Features

| **Fitur**              | **Penjelasan**                                                                                                  |
|------------------------|-----------------------------------------------------------------------------------------------------------------|
| Fixed Acidity          | Kebanyakan asam dalam anggur bersifat tetap (nonvolatile) dan tidak mudah menguap.                              |
| Volatile Acidity       | Jumlah asam asetat dalam anggur; jika terlalu tinggi dapat menghasilkan rasa asam seperti cuka.                 |
| Citric Acid            | Asam yang terdapat dalam jumlah kecil dan dapat menambah rasa segar pada anggur.                                |
| Residual Sugar         | Sisa gula setelah fermentasi berhenti; anggur dengan lebih dari 45 g/L dianggap manis.                          |
| Chlorides              | Kandungan garam dalam anggur.                                                                                   |
| Free Sulfur Dioxide    | Bentuk bebas dari SO₂ yang mencegah pertumbuhan mikroba dan oksidasi anggur.                                    |
| Total Sulfur Dioxide   | Jumlah total bentuk bebas dan terikat dari SO₂; dalam konsentrasi tinggi (>50 ppm), SO₂ bisa tercium dan terasa.|
| Density                | Kerapatan anggur, dipengaruhi oleh kadar alkohol dan gula; mendekati kerapatan air.                             |
| pH                     | Tingkat keasaman atau kebasaan anggur pada skala 0-14; umumnya anggur berada pada pH 3-4.                       |
| Sulphates              | Aditif anggur yang bisa berkontribusi pada tingkat SO₂; berfungsi sebagai antimikroba dan antioksidan.          |
| Alcohol                | Kandungan alkohol dalam anggur.                                                                                 |
| Quality                | Variabel output berupa skor kualitas anggur berdasarkan data sensorik, dengan rentang nilai antara 0 sampai 10. |

---

## Algoritma Supervised Learning (Klasifikasi)

| Algoritma                  | Catatan                                                             |
|----------------------------|---------------------------------------------------------------------|
| **Decision Tree**          | Klasifikasi jenis wine                                              |
| **K-Nearest Neighbor**     | Klasifikasi jenis wine                                              |
| **Naive Bayes**            | Klasifikasi jenis wine                                              |
| **Logistic Regression**    | Klasifikasi jenis wine                                              |
| **Random Forest**          | Ensemble dari banyak Decision Tree, cocok untuk meningkatkan akurasi|
| **XG Boost**               | Gradient boosting yang kuat untuk klasifikasi dengan performa tinggi|
| **Support Vector Machine** | Multiclass dengan SVM One-vs-One                                    |