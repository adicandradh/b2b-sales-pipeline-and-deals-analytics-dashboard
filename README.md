# B2B Sales Pipeline and Deals Analytics Dashboard

## 📌 Project Type
Personal Project

## 📊 Overview
Project ini merupakan dashboard interaktif berbasis Microsoft Power BI yang dikembangkan untuk menganalisis performa sales pipeline, aktivitas penjualan, dan hasil penjualan pada perusahaan B2B yang bergerak di bidang Software as a Service (SaaS) dan Professional Services.

Fokus utama dari project ini adalah mengolah data sales pipeline menjadi informasi yang terstruktur, konsisten, dan mudah dianalisis untuk mendukung proses monitoring operasional maupun pengambilan keputusan strategis. Proses yang dilakukan mencakup data modeling, pembuatan calculated columns dan measures menggunakan DAX, serta visualisasi data untuk memantau perkembangan pipeline, aktivitas sales, performa penjualan, dan kesehatan pipeline secara menyeluruh.

## 🎯 Objectives
- Menyajikan ringkasan kondisi sales pipeline melalui KPI utama, meliputi Open Pipeline Value, Weighted Pipeline Value, dan Open Deal Count.
- Memantau perkembangan pipeline value dan open deal secara periodik untuk mengidentifikasi tren penjualan.
- Mengevaluasi distribusi pipeline berdasarkan Sales Stage, Win Probability, dan Country.
- Menganalisis aktivitas sales melalui Total Activities, Average Activities per Deal, dan High-Risk Open Deal Count.
- Mengidentifikasi tingkat engagement pelanggan berdasarkan jenis aktivitas, durasi aktivitas, dan tahapan sales.
- Mengidentifikasi open deal yang berpotensi mengalami stagnasi menggunakan indikator Deal Health.
- Mengevaluasi performa penjualan melalui Overall Win Rate, Average Won Deal Value, dan Average Sales Cycle.
- Membandingkan performa penjualan berdasarkan Industry, Product Category, dan Company Size.
- Menganalisis performa masing-masing Sales Representative berdasarkan metrik utama penjualan.

## ⚙️ Data Processing
- Data cleaning untuk memastikan konsistensi dan kualitas data.
- Data transformation untuk menyesuaikan struktur data agar siap dianalisis.
- Data modeling untuk membangun hubungan antar tabel dan mendukung analisis multidimensi.
- Pembuatan calculated columns dan measures untuk menghasilkan KPI serta business metrics.
- Pengelompokan (grouping) variabel numerik menjadi kategori analisis untuk mempermudah visualisasi.
- Perancangan dashboard interaktif menggunakan filter, navigasi halaman, dan visual analytics.

## 🧠 Business Logic
- Open Pipeline Value dihitung berdasarkan total nilai seluruh deal yang masih berada dalam pipeline.
- Weighted Pipeline Value dihitung menggunakan nilai deal yang dikalikan dengan probabilitas kemenangan (Win Probability) untuk menghasilkan estimasi nilai pipeline.
- Open Deal Count dihitung berdasarkan jumlah deal dengan status Open.
- Won Deal Value dihitung berdasarkan total nilai deal dengan status Won.
- Average Win Probability dihitung menggunakan rata-rata probabilitas kemenangan seluruh deal dalam pipeline.
- Total Activities dihitung berdasarkan jumlah seluruh aktivitas sales yang dilakukan pada setiap deal.
- Average Activities per Deal dihitung menggunakan rata-rata jumlah aktivitas pada setiap deal.
- Average Activity Duration dihitung menggunakan rata-rata durasi aktivitas sales.
- High-Risk Open Deal Count dihitung berdasarkan jumlah open deal dengan probabilitas kemenangan rendah yang memerlukan perhatian lebih lanjut.
- High-Risk Pipeline Value dihitung berdasarkan total nilai pipeline dari seluruh high-risk open deal.
- Deal Health dikategorikan menjadi Fresh, Aging, dan Stuck berdasarkan usia deal sejak aktivitas terakhir.
- Overall Win Rate dihitung berdasarkan proporsi Won Deal terhadap seluruh Closed Deal (Won dan Lost).
- Average Won Deal Value dihitung menggunakan rata-rata nilai deal yang berhasil dimenangkan.
- Sales Cycle dihitung sebagai selisih waktu antara Created Date dan Last Activity Date pada deal yang telah Closed (Won/Lost).
- Sales Representative Performance dihitung berdasarkan kombinasi jumlah Won Deal, Lost Deal, Win Rate, Won Deal Value, dan Average Sales Cycle pada masing-masing sales representative.

## 🛠️ Tools & Skills
- Microsoft Power BI
- Data modeling
- Star schema
- DAX (Data Analysis Expressions)
- Calculated columns & measures
- Business intelligence
- Sales analytics
- Data visualization & dashboard design
- Business analysis

## 📊 Preview & Insights
### Sales Pipeline Overview
Dashboard untuk memantau kondisi pipeline aktif, distribusi pipeline, serta perkembangan nilai pipeline dan open deal.
<img width="4100" height="2350" alt="b2b-sales-pipeline-and-deals-analytics-1" src="https://github.com/user-attachments/assets/aec680b2-7762-4a39-8927-f5036114603b" />
### Insights
- Secara keseluruhan, nilai Open Pipeline mencapai €606 juta yang berasal dari sekitar 7 ribu open deals dengan Average Deal Value sebesar €90 ribu. Setelah mempertimbangkan probabilitas kemenangan pada setiap deal, estimasi Weighted Pipeline Value mencapai €252 juta, sedangkan total Won Deal Value telah mencapai €241 juta.
- Perkembangan Open Pipeline Value dan Open Deal Count memperlihatkan tren peningkatan yang cukup signifikan sejak tahun 2025 hingga Q1 2026. Pada Q1 2026, nilai pipeline aktif mencapai sekitar €153,18 juta dengan 1.474 open deals, mengindikasikan meningkatnya aktivitas penjualan pada periode tersebut.
- Distribusi pipeline berdasarkan Sales Stage menunjukkan bahwa nilai pipeline terbesar masih berada pada tahap Lead In sebesar €175,36 juta, kemudian menurun secara bertahap hingga tersisa €21,23 juta pada tahap Closing. Nilai pipeline pada tahap Closing hanya sekitar 12,11% dibandingkan tahap awal, mencerminkan proses penyaringan peluang penjualan sepanjang pipeline.
- Berdasarkan Win Probability, sebagian besar nilai pipeline masih terkonsentrasi pada kategori Very Low dengan total sekitar €178,06 juta, sedangkan kategori Very High hanya mencapai sekitar €80,55 juta. Kondisi ini mengindikasikan bahwa mayoritas nilai pipeline masih berasal dari peluang yang memiliki probabilitas kemenangan relatif rendah.
- Weighted Pipeline Value didominasi oleh deal pada tahap Negotiation dengan estimasi nilai sekitar €78,95 juta, diikuti tahap Proposal sebesar sekitar €60 juta. Sebaliknya, tahap Lead In hanya berkontribusi sekitar €17,55 juta, menunjukkan bahwa deal pada tahap akhir memberikan kontribusi forecast pendapatan yang jauh lebih besar dibandingkan deal pada tahap awal.
- Secara geografis, France menjadi negara dengan Open Pipeline Value terbesar yaitu sekitar €73,79 juta yang berasal dari 732 open deals dengan Average Open Deal Value sebesar €100,8 ribu. Sementara itu, Singapore memiliki Open Pipeline Value sebesar €45,61 juta dari 467 open deals dengan Average Open Deal Value sekitar €97,7 ribu, sehingga perbedaan nilai pipeline lebih dipengaruhi oleh jumlah deal dibandingkan nilai rata-rata per deal.

### Sales Execution Overview
Dashboard untuk memonitor aktivitas sales, engagement pelanggan, serta kesehatan pipeline berdasarkan aktivitas dan deal health.
<img width="4100" height="2350" alt="b2b-sales-pipeline-and-deals-analytics-2" src="https://github.com/user-attachments/assets/c0647354-7cf5-422d-bfe0-2efd809ef03b" />
### Insights


### Sales Performance Overview
Dashboard untuk mengevaluasi hasil penjualan, efisiensi proses sales, serta performa sales representative berdasarkan berbagai metrik utama.
<img width="4100" height="2350" alt="b2b-sales-pipeline-and-deals-analytics-3" src="https://github.com/user-attachments/assets/dff4762f-62bb-4c19-848c-4ea6204356cc" />
### Insights

