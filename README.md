# 📊 What's Trending on Youtube
**Proyek Sprint 11 Data Analyst TripleTen**

## 📌 Deskripsi
Proyek kali ini membuat sebuah dashboard untuk sebuah agensi periklanan yaitu Sterling & Draper meminta untuk menganalisis video yang sedang trending di YouTube guna menentukan jenis konten yang menarik bagi tim pemasaran. Setiap video tentunya punya beberapa kategori seperti Hiburan, Musik, Berita & Politik, lalu wilayah, dan tanggal trending yang spesifik. Suatu video bisa saja berada di jajaran segmen trending selama beberapa hari berturut-turut.

## 🛠️ Pedoman Teknis
- Tujuan bisnis: menganalisis riwayat video yang sedang trending di YouTube
- Frekuensi penggunaan dashboard: minimal sekali sehari
- Pengguna dashboard yang ditargetkan: para manajer perencanaan video ads
- Signifikansi: semua grafik sama pentingnya
- Interval pembaruan data: setiap 24 jam sekali, pada tengah malam waktu UTC
- Parameter yang digunakan untuk mengelompokkan data yaitu: tanggal dan waktu trending, kategori video, dan negara
- Sumber data untuk dashboard: data engineer akan membuat tabel agregat yang dinamai trending_by_time dan disimpan di database youtube yang dibuat khusus
- Data: riwayat trending yaitu nilai absolut yang dibagi berdasarkan hari (dua grafik: nilai absolut dan rasio persentase), sesi yang dikelompokkan berdasarkan negara — nilai relatif (% sesi), dan hubungan antara kategori dan negara — nilai absolut (tabel)

## 📑 Struktur Data
Data:
- Riwayat trending — nilai absolut yang dibagi berdasarkan hari (dua grafik: nilai absolut dan rasio persentase)
- Sesi, dikelompokkan berdasarkan negara — nilai relatif (% sesi)
- Hubungan antara kategori dan negara — nilai absolut (tabel)

Berikut adalah struktur datanya:
- `record_id` — kunci primer
- `region` — negara/wilayah geografis
- `trending_date` — tanggal dan waktu
- `category_title` — kategori video
- `videos_count` —jumlah video pada segmen trending

## 📊 Konten Dashboard
Konten data dashboard:
- Video yang pernah trending, dikelompokkan berdasarkan hari dan kategori
- Video yang sedang trending, dikelompokkan berdasarkan negara
- Tabel yang menghubungkan kategori dan negara
- Grafik, kontrol dashboard, dan susunannya:
![image](https://github.com/user-attachments/assets/16812db2-8575-4558-8b19-1299e909d4f2)

## 🎯 Tujuan Dashboard
- Menampilkan kategori video apa saja yang trending minggu lalu.
- Menampilkan penyebarannya di setiap wilayah.
- Menampilkan apa yang paling populer di Amerika Serikat.

## 🔄 Tahapan Analisis
1. **Persiapan Dataset** 🛠️
2. **Pembuatan Dashboard** 🔍
3. **Kesimpulan & Rekomendasi** ✅

## 📂 File Repository
📁 [Dataset](https://github.com/AdamGustiAndito/What-s-Trending-on-Youtube/blob/main/trending_by_time.csv) → Dataset yang digunakan  

## 📊 Dashboard Tableau
🔗 [Lihat di sini](https://public.tableau.com/views/YoutubeTrendsDashboard_16998582075760/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## 📄 Laporan & Presentasi
📥 [Download laporan & presentasi](https://github.com/AdamGustiAndito/What-s-Trending-on-Youtube/blob/main/What's%20trending%20on%20Youtube.pdf)

## 📌 Teknologi yang Digunakan
- **Tableau** (Visualisasi dashboard)

---
💡 **Dibuat oleh:** Adam Gusti Andito  
📧 **Hubungi saya:** [LinkedIn](https://www.linkedin.com/in/adam-gusti-andito-1b04721b0/)


