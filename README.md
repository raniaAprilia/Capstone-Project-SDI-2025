# Capstone-Project-SDI-2025
Nama: Rania Aprilia Dwi Setya Putri

Batch: 4
## Analisis Sentimen Review Hotel 
### Project Overview
Proyek ini bertujuan untuk menganalisis customer sentimen berdasarkan review hotel yang dilakukan pada aplikasi TripAdvisor dan memberikan insight baru untuk manajemen hotel. Analisa menggunakan model LLM berupa IBM Granite-8b-instruct. Hasil dari proyek ini berupa kata kunci aspek yang disebutkan oleh customer dan rekomendasi untuk manajemen hotel. 
### Dataset
Dataset raw tersedia pada Kaggle: Trip Advisor Hotel Reviews https://www.kaggle.com/datasets/andrewmvd/trip-advisor-hotel-reviews
### Insight & Findings
Untuk setiap review, akan didapatkan:
1. 3 aspek utama - Key element fokus pelanggan
2. 2 primary sentiment - Sentimen dominan (positif atau negatif)
3. 2 rekomendasi - Rekoemndasi untuk memperbaiki negatif review
### AI Support 
Analysis:
1. Langchain - Untuk membangun struktur dan memproses natural language data
2. Replicate - Untuk menjalankan LLM model untuk sentimen analisis 
3. Custom Preprocessing - text cleaning dan normalisasi
4. Visualization Tools - Matplotlib, Seaborn, Wordcloud

Alur Pengerjaan:
1. Preprocessing
2. Klasifikasi Sentimen (Positive, Neutral, Negative)
3. Extraksi kata kunci
4. Generate prompt
5. Visualisai persebaran sentimen
