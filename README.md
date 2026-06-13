# 📊 Google Merchandise Store: Campaign Performance Analysis (GA4)

## 📌 Project Overview
Project ini bertujuan untuk mengevaluasi performa berbagai kampanye pemasaran (*marketing campaigns*) Google Merchandise Store selama periode Januari 2026 menggunakan data Google Analytics 4 (GA4)[cite: 3]. Melalui pendekatan *custom reporting* dan *anomaly detection*, analisis ini berfokus pada metrik akuisisi, interaksi, dan konversi untuk mengidentifikasi kampanye terbaik serta memberikan rekomendasi taktis bagi tim *Growth Marketing*[cite: 3].

### 🎯 Objectives
- Mengevaluasi tren harian *session* dan *user* untuk mendeteksi anomali performa[cite: 3].
- Menganalisis efektivitas kampanye berdasarkan *Engagement Rate*, *Bounce Rate*, dan *Conversion Rate*[cite: 3].
- Memberikan rekomendasi strategis untuk menurunkan *bounce rate* dan mengoptimalkan retensi pelanggan[cite: 3].

---

## 📂 Project Resources (Quick Links)
- 📄 **[View Full Presentation Deck (Google Campaign Performance Analysis)](./Campaign%20Performance%20Analysis.pdf)** *(Pastikan nama file PDF yang kamu upload disamakan/disesuaikan)*

---

## 🛠️ Tools & Methodology
- **Analytics Tool:** Google Analytics 4 (GA4)[cite: 3]
- **Feature Used:** GA4 Explore (Custom Reporting) untuk penggabungan dimensi dan metrik spesifik bisnis[cite: 3].
- **Data Period:** 1 Januari – 31 Januari 2026[cite: 3].
- **Data Cleansing:** Mengeliminasi data tidak valid seperti kampanye `(not set)` dan `bug`, serta memfilter kampanye dengan volume rendah (<10 sessions) untuk menjaga akurasi data[cite: 3].
- **Anomaly Detection:** Menggunakan masa pelatihan (*training period*) 60 hari dengan tingkat sensitivitas sedang (*medium sensitivity*)[cite: 3].

---

## 📈 Key Insights & Findings

### 🏃‍♂️ User & Session Trends
- **User Acquisition:** Trafik didominasi oleh *New Users* sebanyak **31.774**, berbanding terbalik dengan *Returning Users* yang hanya **11.990**[cite: 3]. Ini menunjukkan performa akuisisi yang kuat namun retensinya masih sangat terbatas[cite: 3].
- **Traffic Anomaly:** Terjadi lonjakan fluktuasi *sessions* yang signifikan pada minggu ketiga, dengan anomali puncak terpantau pada **22 Januari 2026**[cite: 3]. Hal ini mengindikasikan adanya aktivitas promosi atau kampanye dengan dampak yang sangat tinggi pada hari tersebut[cite: 3].

### 🏆 Campaign Performance Evaluation
- **Best Overall Performer:** Kampanye **`(cross-network)`** menduduki peringkat pertama karena performanya stabil dan konsisten tinggi di seluruh metrik utama (*engagement* tinggi dan penargetan efektif)[cite: 3].
- **Reliable Runner-Up:** Kampanye **`October 2025_ChromeDinoMagic_V1`** berada di posisi kedua dengan performa yang sangat seimbang dan stabil[cite: 3].
- **High Traffic, Low Engagement Case:** Kampanye **`Aug025_Noogler_V1`** mencatatkan *conversion rate* yang relatif tinggi, namun memiliki *bounce rate* yang tinggi pula[cite: 3]. Ini mengindikasikan adanya kesenjangan (*gap*) antara pesan iklan dengan ekspektasi pengguna di *landing page*[cite: 3].

---

## 💡 Strategic Recommendations
1. **Landing Page Optimization:** Memperbaiki relevansi konten pada *landing page* (terutama untuk kampanye sejenis `Aug025_Noogler_V1`) guna menekan *bounce rate* dan memberikan pengalaman pengguna yang mulus[cite: 3].
2. **Implement Retention Strategies:** Membangun strategi loyalitas pengguna seperti program *remarketing* iklan, atau *email marketing* untuk mendorong *Returning Users* agar kembali bertransaksi[cite: 3].
3. **Campaign Benchmarking:** Menjadikan pola taktis dari kampanye `(cross-network)` dan `October 2025_ChromeDinoMagic_V1` sebagai tolok ukur (*benchmark*) dalam merancang strategi *campaign* di masa mendatang[cite: 3].

---

## 🧠 Reflection: Why Custom Reporting?
Laporan standar analitik sering kali terlalu umum. *Custom reporting* melalui GA4 Explore sangat krusial karena memungkinkan fleksibilitas penuh untuk menggabungkan metrik dan dimensi unik sesuai kebutuhan bisnis[cite: 3]. Hal ini membantu menjembatani pemahaman mengapa kampanye dengan interaksi (*engagement*) tinggi belum tentu menghasilkan konversi (*conversion*), karena ketertarikan kasual audiens berbeda dengan niat murni untuk membeli produk[cite: 3].
