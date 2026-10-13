# Sentiment Analysis for Melolo App Reviews

> **TL;DR** — Proyek NLP untuk menganalisis sentimen ulasan pengguna aplikasi "Melolo" menggunakan teknik scraping data dan pemodelan Machine Learning (Lexicon-based & Supervised Learning).

---

## 🔬 Project Overview

Proyek ini mencakup alur kerja lengkap Data Science dalam bidang Natural Language Processing (NLP):
1.  **Data Acquisition**: Scraping ulasan aplikasi dari Google Play Store/sumber lain.
2.  **Data Preprocessing**: Cleaning, Case Folding, Tokenizing, Stopword Removal, dan Stemming pada teks Bahasa Indonesia.
3.  **Labeling**: Menggunakan Lexicon Indonesia (Positive/Negative) untuk pelabelan otomatis.
4.  **Modeling**: Membangun model klasifikasi sentimen untuk memprediksi emosi pengguna.

## 📁 Repository Structure

- `Kode_Scraping_...`: Notebook untuk proses pengambilan data ulasan.
- `Model_Machine_Learning_...`: Notebook utama untuk preprocessing, labeling, dan pemodelan ML.
- `ulasan_aplikasi_melolo.csv`: Dataset ulasan mentah yang berhasil di-scrape.
- `lexicon_...`: Kamus kata positif dan negatif dalam Bahasa Indonesia untuk pelabelan.

## 🛠️ Tech Stack

- **Python**
- **Pandas & NumPy** (Data Manipulation)
- **Scikit-learn** (Machine Learning)
- **NLTK / Sastrawi** (Indonesian NLP Library)
- **BeautifulSoup / Selenium** (Scraping)

## 🚀 Cara Menjalankan

1.  Clone repository ini.
2.  Pastikan library yang dibutuhkan terinstall (`pip install pandas scikit-learn sastrawi`).
3.  Jalankan `Model_Machine_Learning_...ipynb` untuk melihat proses analisis lengkap.

---

## 📜 License

Project ini dilisensikan di bawah [MIT License](LICENSE).

---

## 📊 Model Performance

| Metric | Value |
|---|---|
| Accuracy | TBD |
| Precision | TBD |
| Recall | TBD |
| F1-Score | TBD |

### Confusion Matrix

![Confusion Matrix](reports/figures/confusion-matrix.png)

_Add confusion matrix image from model evaluation to reports/figures/confusion-matrix.png_

### Key Insights

- Dominant sentiment & distribution
- Top terms contributing to positive/negative sentiment
