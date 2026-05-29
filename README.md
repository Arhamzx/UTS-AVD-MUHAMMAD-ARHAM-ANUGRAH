# UTS-AVD

Nama: Muhammad Arham Anugrah

NIM: 2509116044

Kelas: Sistem Informasi B 25

# Deskripsi

Dataset Air Quality Index (AQI) digunakan untuk menganalisis kondisi kualitas udara pada berbagai negara berdasarkan nilai indeks kualitas udara atau Air Quality Index. Analisis ini bertujuan untuk memahami distribusi kualitas udara, mengidentifikasi negara dengan tingkat AQI tertinggi, serta memperoleh insight mengenai pola persebaran data kualitas udara melalui visualisasi data.

Dataset terdiri dari beberapa atribut utama seperti negara, status kualitas udara, dan nilai AQI yang digunakan untuk menggambarkan tingkat pencemaran udara pada suatu wilayah. Analisis dilakukan menggunakan Python dengan bantuan library Pandas, Matplotlib, dan Seaborn untuk mendukung proses Exploratory Data Analysis (EDA).

# Latar Belakang

Kualitas udara merupakan salah satu indikator penting dalam menentukan kondisi lingkungan dan kesehatan masyarakat. Tingginya tingkat pencemaran udara dapat menyebabkan berbagai dampak negatif seperti gangguan pernapasan, penurunan kualitas hidup, hingga peningkatan risiko penyakit kronis.

Air Quality Index (AQI) digunakan sebagai standar untuk mengukur tingkat kualitas udara berdasarkan konsentrasi polutan tertentu. Semakin tinggi nilai AQI, maka semakin buruk kualitas udara pada wilayah tersebut.

Melalui analisis data AQI, dapat diketahui pola distribusi kualitas udara pada berbagai negara serta mengidentifikasi wilayah dengan tingkat pencemaran udara yang tinggi. Hasil analisis ini diharapkan dapat memberikan gambaran mengenai kondisi kualitas udara secara umum dan membantu proses pengambilan keputusan berbasis data terkait pengelolaan lingkungan.

# Dataset

Sumber Dataset: Kaggle – Air Quality Index Dataset

Kolom utama:

* Country
* AQI Value
* AQI Category
* Date
* Status

# Tahapan Proses

## Business Understanding

Menentukan tujuan analisis yaitu memahami pola kualitas udara berdasarkan nilai AQI, mengidentifikasi negara dengan tingkat AQI tertinggi, serta menganalisis distribusi data kualitas udara menggunakan teknik visualisasi data.

## Data Understanding

Dataset dimuat ke dalam Python menggunakan Pandas dan dilakukan eksplorasi awal untuk memahami struktur data, tipe data, jumlah data, serta statistik deskriptif pada setiap kolom.

## Verifikasi Kualitas Data

* Pengecekan tipe data: seluruh tipe data sesuai
* Missing value: tidak ditemukan missing value yang signifikan
* Duplicate data: tidak ditemukan data duplikat yang signifikan
* Outlier: ditemukan beberapa nilai ekstrem pada kolom AQI Value

# Hasil & Insight

* Nilai AQI menunjukkan distribusi yang tidak merata dengan beberapa data ekstrem bernilai sangat tinggi.
* Negara dengan AQI tertinggi memiliki tingkat pencemaran udara yang jauh lebih tinggi dibanding negara lainnya.
* Distribusi AQI cenderung mengalami right skewness, yaitu sebagian besar data berada pada rentang tertentu namun terdapat sejumlah kecil data dengan nilai sangat tinggi.
* Pie chart top 3 negara dengan AQI tertinggi menunjukkan adanya dominasi kontribusi AQI dari beberapa negara tertentu.
* Visualisasi histogram menunjukkan bahwa sebagian besar kualitas udara berada pada kategori tertentu, namun terdapat sejumlah kondisi pencemaran udara ekstrem.
* Keberadaan outlier mengindikasikan adanya wilayah dengan kondisi kualitas udara yang sangat buruk dibanding mayoritas data lainnya.

# Exploratory Data Analysis (EDA)

EDA dilakukan untuk memahami pola dan karakteristik data kualitas udara menggunakan beberapa pendekatan visualisasi data. Analisis distribusi dilakukan menggunakan histogram untuk melihat persebaran nilai AQI pada dataset. Analisis outlier dilakukan menggunakan boxplot guna mengidentifikasi nilai ekstrem pada data kualitas udara.

Selain itu, dilakukan analisis komposisi menggunakan pie chart untuk menampilkan kontribusi top 3 negara dengan AQI tertinggi. Analisis perbandingan juga dilakukan menggunakan visualisasi bar chart untuk membandingkan tingkat kualitas udara antar negara.

Melalui proses EDA, diperoleh insight bahwa distribusi data AQI tidak sepenuhnya normal dan terdapat beberapa negara dengan tingkat pencemaran udara yang jauh lebih tinggi dibanding negara lain.

# Kesimpulan

Berdasarkan hasil Exploratory Data Analysis (EDA) yang telah dilakukan, dapat disimpulkan bahwa dataset AQI memiliki kualitas data yang cukup baik karena tidak ditemukan missing value maupun duplicate data dalam jumlah signifikan. Namun demikian, ditemukan beberapa outlier pada kolom AQI Value yang menunjukkan adanya kondisi pencemaran udara ekstrem pada beberapa negara.

Distribusi data AQI menunjukkan pola right skewness, di mana sebagian besar data berada pada rentang nilai tertentu namun terdapat sejumlah kecil data dengan nilai AQI sangat tinggi. Hal ini menunjukkan bahwa kualitas udara antar negara memiliki perbedaan yang cukup signifikan.

Hasil visualisasi pie chart dan bar chart menunjukkan bahwa beberapa negara mendominasi tingkat AQI tertinggi, yang mengindikasikan kondisi kualitas udara yang lebih buruk dibanding negara lainnya. Selain itu, histogram memperlihatkan bahwa distribusi kualitas udara tidak merata dan masih terdapat wilayah dengan tingkat pencemaran udara yang tinggi.

Secara keseluruhan, analisis ini menunjukkan bahwa teknik Exploratory Data Analysis (EDA) dan visualisasi data mampu membantu memahami pola kualitas udara secara lebih efektif, mengidentifikasi kondisi ekstrem, serta memberikan insight yang dapat digunakan sebagai dasar analisis lingkungan berbasis data.
