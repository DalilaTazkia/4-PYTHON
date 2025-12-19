<<<<<<< HEAD
# 4-PYTHON
UAS SCRAPPING PYTHON SEMESTER 4
=======
# 📊 UAS Web Scraping Python — Semester 4

## 📌 Deskripsi Proyek

Proyek ini merupakan **Ujian Akhir Semester (UAS)** mata kuliah **Python**, yang berfokus pada penerapan teknik **Web Scraping** untuk mengambil data dari website publik dan mengolahnya menjadi dataset terstruktur.

Pada proyek ini, saya melakukan pengambilan data daftar **100 Best Books versi The New York Times**, kemudian membersihkan, menyimpan, dan memvisualisasikan data menggunakan Python.

Proyek ini menunjukkan kemampuan saya dalam:

* Pemrograman Python
* Pengambilan data dari web (web scraping)
* Pengolahan dan analisis data
* Visualisasi data sederhana

---

## 🎯 Tujuan Proyek

* Memahami struktur HTML dari sebuah website
* Mengambil data menggunakan teknik web scraping
* Mengolah data mentah menjadi dataset terstruktur
* Menyimpan data dalam format CSV
* Menyajikan data dalam bentuk visualisasi agar mudah dipahami

---

## 🛠️ Tools & Teknologi

Proyek ini dikembangkan menggunakan:

* 🐍 **Python 3**
* 📓 **Jupyter Notebook**
* 🌐 **Requests** – untuk mengambil halaman web
* 🥣 **BeautifulSoup** – untuk parsing HTML
* 📊 **Pandas** – untuk pengolahan data
* 📈 **Matplotlib / Seaborn** – untuk visualisasi data
* 📁 **CSV** – format penyimpanan data

---

## 📂 Struktur Repository

```
4-PYTHON/
│
├── UASSCRAPPING.ipynb
├── TheNewYorkTimes100BestBooks.csv
└── README.md
```

---

## 🔄 Alur Proses Web Scraping

Berikut tahapan yang dilakukan dalam notebook:

1. **Import Library**

   * Mengimpor library Python yang dibutuhkan

2. **Request ke Website**

   * Mengambil halaman web target menggunakan HTTP request

3. **Parsing HTML**

   * Membaca dan mengekstrak data dari tag HTML tertentu

4. **Pengambilan Data**

   * Mengambil informasi seperti:

     * Judul buku
     * Penulis
     * Tahun / kategori (sesuai data yang tersedia)

5. **Pembersihan Data**

   * Menghilangkan data kosong atau tidak valid

6. **Penyimpanan Data**

   * Menyimpan hasil scraping ke file CSV

7. **Visualisasi Data**

   * Menampilkan data dalam bentuk grafik

---

## 📊 Dataset

Hasil scraping disimpan dalam file:

📁 **TheNewYorkTimes100BestBooks.csv**

Dataset ini berisi daftar **100 buku terbaik versi The New York Times** yang telah diolah dan siap digunakan untuk analisis lanjutan.

---

## 📈 Visualisasi Data

Hasil visualisasi data menunjukkan bahwa mayoritas buku dalam daftar 100 Best Books versi The New York Times diterbitkan pada era modern (2000–2022) dan didominasi oleh genre Fiction, diikuti oleh Non-fiction. Buku-buku tersebut umumnya memiliki panjang 250–500 halaman, dengan beberapa karya non-fiksi dan biografi yang cenderung lebih panjang. Tidak ditemukan hubungan langsung antara tahun publikasi dan jumlah halaman, namun genre terbukti memengaruhi panjang buku. Daftar ini juga menampilkan keragaman penulis dan penerbit, tanpa dominasi ekstrem dari satu pihak, sehingga mencerminkan keberagaman karya literatur berkualitas.

---

## 🚀 Cara Menjalankan Proyek

1. Clone repository:

```bash
git clone https://github.com/DalilaTazkia/4-PYTHON.git
```

2. Masuk ke folder project:

```bash
cd 4-PYTHON
```

3. Jalankan Jupyter Notebook:

```bash
jupyter notebook
```

4. Buka file `UASSCRAPPING.ipynb` dan jalankan cell secara berurutan

---

## 📌 Insight & Kesimpulan

* Web scraping memungkinkan pengambilan data publik secara otomatis
* Data mentah dari web perlu dibersihkan sebelum dianalisis
* Visualisasi membantu memahami pola dan distribusi data
* Python sangat efektif untuk pengolahan data berbasis web

---

## 👩‍💻 Author

**Dalila Tazkia**
Mahasiswa Semester 4
Project UAS Python — Web Scraping
>>>>>>> 7f434397202fdad886a1e9b71b8ca300bc0eaa7e
