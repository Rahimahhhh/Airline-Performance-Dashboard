# Airline Performance Dashboard

## Tentang Proyek

Proyek ini bertujuan menganalisis performa maskapai penerbangan di Amerika Serikat berdasarkan data keterlambatan penerbangan (US Flight Delay). Dashboard dirancang untuk membantu manajemen maskapai memahami faktor utama penyebab keterlambatan, mengevaluasi performa setiap airline, serta mengidentifikasi bandara yang memiliki tingkat keterlambatan tertinggi.

Sebelum proses visualisasi dilakukan, dataset dibersihkan menggunakan Microsoft Excel dengan memastikan format data konsisten, menghapus data yang tidak valid, serta memvalidasi nilai pada setiap jenis keterlambatan. Selanjutnya dashboard dikembangkan menggunakan Tableau Public agar pengguna dapat melakukan eksplorasi data secara interaktif melalui filter airline.

## Temuan Utama

**Performa Maskapai:**
- Performa setiap maskapai berbeda secara signifikan. Beberapa maskapai memiliki rata-rata keterlambatan yang jauh lebih tinggi dibanding kompetitor.
- Komposisi penyebab keterlambatan juga berbeda pada setiap maskapai sehingga strategi perbaikannya tidak dapat disamaratakan.

**Performa Operasional Bandara:**
- Beberapa bandara besar secara konsisten memiliki rata-rata arrival delay yang lebih tinggi dibanding bandara lainnya.
- Tren keterlambatan berubah sepanjang tahun sehingga periode tertentu memerlukan perhatian operasional yang lebih besar.

## Dashboard

### Airline Performance Dashboard

Dashboard ini menyajikan ringkasan performa maskapai melalui visualisasi KPI, komposisi penyebab delay, peringkat maskapai, tren keterlambatan bulanan, peta persebaran bandara, serta Top 10 Airport dengan rata-rata arrival delay tertinggi.

![Airline Performance Dashboard](images/airline_performance_dashboard.png)

**Buka di Tableau Public:** *(https://public.tableau.com/shared/Y3R925DMP?:display_count=n&:origin=viz_share_link)*

## Insight & Recommendation

| Insight | Recommendation |
|----------|----------------|
| Komposisi penyebab delay berbeda pada setiap maskapai sehingga tidak semua airline memiliki masalah operasional yang sama. | Fokuskan strategi perbaikan berdasarkan penyebab delay dominan pada masing-masing airline, misalnya Carrier Delay atau Late Aircraft Delay. |
| Beberapa airport memiliki rata-rata arrival delay yang jauh lebih tinggi dibanding airport lainnya. | Prioritaskan evaluasi operasional pada airport dengan delay tertinggi untuk mengurangi dampak terhadap jaringan penerbangan. |
| Trend delay menunjukkan adanya kenaikan pada bulan-bulan tertentu. | Tingkatkan kesiapan operasional dan alokasi sumber daya pada periode dengan potensi keterlambatan tinggi. |
| Airline dengan rata-rata delay paling rendah dapat dijadikan benchmark bagi maskapai lain dalam meningkatkan performa layanan. | Lakukan benchmarking terhadap proses operasional maskapai dengan performa terbaik untuk menemukan best practice. |

## Alur Kerja

```
Raw Data (Excel)
    ↓
Data Cleaning & Validasi — Microsoft Excel
(memeriksa missing value, validasi format data, standardisasi data)
    ↓
Visualisasi & Analisis — Tableau Public
(Airline Performance Dashboard)
    ↓
Business Insight & Recommendation
```

## Tools

| Tahap | Tools |
|---|---|
| Data Cleaning | Microsoft Excel |
| Visualisasi | Tableau Public |

## Struktur Repositori

```
Airline-Performance-Dashboard/
├── dashboard/
│   └── Airline Performance Dashboard.twbx
├── dataset/
│   └── Flight Delay 2.xlsx
├── images/
│   └── airline_performance_dashboard.png
└── README.md
```
