# Analisis Data Penumpang Titanic

## Deskripsi
Proyek ini merupakan analisis data eksploratif (Exploratory Data Analysis - EDA) pada dataset penumpang Kapal Titanic. Tujuannya adalah untuk menemukan pola dan faktor-faktor yang memengaruhi tingkat keselamatan penumpang dalam tragedi bersejarah tersebut. Proyek ini dibuat sebagai latihan dasar untuk pemula dalam bidang sains data menggunakan Python dan library-library utamanya.

## Latar Belakang
Tragedi tenggelamnya RMS Titanic pada tahun 1912 adalah salah satu peristiwa maritim paling terkenal dalam sejarah. Dataset ini menjadi salah satu dataset paling populer untuk pemula sains data karena datanya yang kaya akan cerita dan memungkinkan kita untuk berlatih membersihkan, memanipulasi, dan memvisualisasikan data untuk menarik kesimpulan yang bermakna.

## Pertanyaan Analisis
Proyek ini berusaha menjawab pertanyaan-pertanyaan berikut melalui analisis data:
1.  Berapa rasio penumpang yang selamat dibandingkan dengan yang tidak selamat?
2.  Apakah jenis kelamin (`Sex`) penumpang memengaruhi peluang mereka untuk selamat?
3.  Bagaimana pengaruh kelas tiket (`Pclass`) terhadap tingkat keselamatan?
4.  Bagaimana distribusi usia (`Age`) para penumpang di kapal?

## Dataset
* **Nama:** Titanic: Machine Learning from Disaster
* **Sumber:** Dataset ini bersumber dari kompetisi Kaggle dan tersedia secara publik. Dalam proyek ini, data dimuat langsung dari URL repositori [datasciencedojo](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv).
* **Kolom Utama yang Dianalisis:**
    * `Survived`: Status keselamatan (0 = Tidak Selamat, 1 = Selamat)
    * `Pclass`: Kelas tiket (1 = Kelas 1, 2 = Kelas 2, 3 = Kelas 3)
    * `Sex`: Jenis kelamin (male, female)
    * `Age`: Usia penumpang

## Teknologi dan Library yang Digunakan
* **Lingkungan:** Google Colaboratory
* **Bahasa:** Python 3
* **Libraries:**
    * `pandas`: Untuk manipulasi dan analisis data.
    * `matplotlib`: Untuk membuat visualisasi data dasar.
    * `seaborn`: Untuk membuat visualisasi data statistik yang lebih menarik.

## Cara Menjalankan Proyek
1.  Buka file notebook `.ipynb` di Google Colaboratory.
2.  Pastikan Anda memiliki koneksi internet agar notebook dapat mengunduh dataset dari URL.
3.  Jalankan setiap sel kode secara berurutan dari atas ke bawah. Anda juga bisa menggunakan opsi `Runtime > Run all` di menu bar Google Colab.

## Temuan Utama
Analisis ini menghasilkan beberapa temuan kunci:
* **Tingkat Keselamatan Rendah:** Secara keseluruhan, jumlah penumpang yang tidak selamat jauh lebih banyak daripada yang selamat.
* **Prioritas Keselamatan Berdasarkan Jenis Kelamin:** Penumpang perempuan memiliki tingkat keselamatan yang secara signifikan lebih tinggi dibandingkan penumpang laki-laki. Hal ini sejalan dengan protokol "wanita dan anak-anak dulu".
* **Pengaruh Status Sosial-Ekonomi:** Ada korelasi kuat antara kelas tiket dan keselamatan. Penumpang di `Pclass 1` (kelas atas) memiliki tingkat keselamatan tertinggi, sedangkan penumpang di `Pclass 3` (kelas ekonomi) memiliki tingkat keselamatan terendah.

## Contoh Visualisasi
Berikut adalah beberapa contoh visualisasi yang dihasilkan dari analisis ini:

**Grafik Keselamatan Berdasarkan Jenis Kelamin**
*(Di sini Anda bisa memasukkan screenshot dari grafik yang membandingkan keselamatan pria vs. wanita)*

**Grafik Keselamatan Berdasarkan Kelas Tiket**
*(Di sini Anda bisa memasukkan screenshot dari grafik yang membandingkan keselamatan Pclass 1, 2, dan 3)*

## Kontributor
* [Nama Anda] - [Link ke profil GitHub atau LinkedIn Anda (opsional)]
