# 🎮 Steam Games Revenue Analysis (2024)

Analisis data mandiri untuk mengeksplorasi performa finansial dari 1.500 game teratas di platform Steam berdasarkan data per September 2024. Proyek ini dibuat untuk mempertajam kemampuan *data cleaning*, manipulasi data menggunakan Python (Pandas), serta visualisasi data tingkat lanjut (Matplotlib).

---

## 📌 Pertanyaan Analisis
> Game apa saja yang berhasil meraup pendapatan (*revenue*) terbesar di Steam?

---

## 🛠️ Tech Stack & Library
* **Python** 
* **Pandas** (Data Cleaning & Manipulation)
* **Matplotlib & Matplotlib.ticker** (Data Visualization)

---

## 📂 Alur Pengerjaan (Workflow)
1. **Data Loading:** Memuat dataset 1.500 game Steam.
2. **Data Cleaning:** Menangani *missing values* pada kolom `publishers` dan `developers` dengan mengisinya menjadi `"Unknown"`, serta mengubah format kolom `releaseDate` menjadi `datetime`.
3. **Data Sorting:** Mengurutkan data berdasarkan total *revenue* tertinggi untuk mencari 5 game teratas.
4. **Data Visualization:** Membuat *bar chart* kustom dengan anotasi angka otomatis (format juta/miliar USD) serta styling grafik yang bersih (*clean-look*).

---

## 📊 Hasil Analisis Utama (Top 5 Game)
1. **Black Myth: Wukong** — `$837.8 M`
2. **HELLDIVERS™ 2** — `$435.6 M`
3. **Palworld** — `$392.3 M`
4. **Sons Of The Forest** — `$217.0 M`
5. **Dragon's Dogma 2** — `$111.5 M`

*Insight:* *Black Myth: Wukong* mendominasi pasar secara signifikan dengan perolehan pendapatan yang jauh melampaui game-game lainnya di posisi 5 besar.

---

## 🚀 Cara Menjalankan Kode
1. Download file notebook (`.ipynb`) dari repository ini.
2. Dataset Didapatkan dari: https://www.kaggle.com/datasets/alicemtopcu/top-1500-games-on-steam-by-revenue-09-09-2024
3. Jalankan sel kode secara berurutan.
