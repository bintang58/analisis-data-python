# 📊 Submission - Belajar Analisis Data dengan Python

Repositori ini berisi proyek akhir dari modul **Belajar Analisis Data dengan Python** (Laskar AI). Proyek ini berfokus pada pembuatan dashboard interaktif menggunakan **Streamlit** untuk menganalisis data penyewaan sepeda.

---

## Bike Sharing Analysis Dashboard 🚲

Dashboard interaktif ini dibuat menggunakan Streamlit untuk menganalisis data penyewaan sepeda berdasarkan dataset Bike Sharing Dataset. Dashboard ini memberikan wawasan tentang pola penggunaan berdasarkan musim, tren penyewaan sepeda harian, serta analisis RFM.

---

## 📌 Fitur Dashboard

- **Analisis Harian**: Menampilkan jumlah penyewaan sepeda oleh pengguna casual dan registered.
- **Musim dengan Penyewaan Tertinggi**: Visualisasi tren penyewaan berdasarkan musim.
- **Jam dengan Penyewaan Tertinggi & Terendah**: Mengidentifikasi jam sibuk dan sepi.
- **Analisis RFM**: Mengkategorikan pelanggan berdasarkan Recency, Frequency, dan Monetary.

---

## 📂 Struktur Folder

```plaintext
📂 analisis-data-python
├── 📂 dashboard
│   ├── dashboard.py          # File utama Streamlit
│   ├── day_clean.csv         # Data harian yang sudah dibersihkan
│   ├── hour_clean.csv        # Data per jam yang sudah dibersihkan
│   └── logo.png              # Logo tampilan dashboard
├── 📂 data
│   ├── Readme.txt            # Keterangan dataset mentah
│   ├── day.csv               # Data mentah harian
│   └── hour.csv              # Data mentah per jam
├── notebook.ipynb            # Notebook eksplorasi awal dan cleaning
├── requirements.txt          # Daftar pustaka yang dibutuhkan
├── url.txt                   # Link referensi atau dokumentasi
└── README.md                 # Dokumentasi proyek
```

---

## 🚀 Menjalankan Dashboard

### 🔁 1. Clone Repository

```bash
git clone https://github.com/bintang58/analisis-data-python
cd analisis-data-python
```

### 📦 Install Dependency

Pastikan sudah menginstal semua pustaka yang diperlukan dengan menjalankan perintah:

```bash
pip install -r requirements.txt
```

### ▶️ Jalankan Streamlit App

Jalankan Streamlit untuk menampilkan dashboard:

```bash
streamlit run dashboard/dashboard.py
```

---

## 🌐 Akses Online

📍 Kamu juga bisa melihat versi online dari dashboard melalui:  
🔗 [Bike Sharing Dashboard (Streamlit Cloud)](https://bike-sharing-dashboards.streamlit.app/)

---

## 📊 Dataset

Dataset digunakan berasal dari:  
🔗 [UCI Machine Learning Repository - Bike Sharing Dataset](https://drive.google.com/file/d/1RaBmV6Q6FYWU4HWZs80Suqd7KQC34diQ/view)

---

## 🛠️ Teknologi

- **Python**:
  - `numpy` – Untuk operasi numerik dasar.
  - `pandas` – Untuk manipulasi dan analisis data.
  - `matplotlib` & `seaborn` – Untuk membuat visualisasi data.
- **Streamlit** – Untuk membangun dashboard web interaktif.
- **Google Colab** / Jupyter Notebook – Digunakan dalam eksplorasi data dan pembersihan data.


---

## 📝 Catatan

- Proyek ini mencakup data preprocessing, visualisasi eksploratif, hingga pembuatan dashboard.
- Data yang digunakan telah melalui proses cleaning agar siap dianalisis dalam dashboard.

---

> Proyek ini dibuat sebagai bagian dari pelatihan **Laskar AI - Belajar Analisis Data dengan Python**
