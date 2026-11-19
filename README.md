# Data Warehouse Publikasi Riset UMN (2020–2025)

Proyek kelompok (5 orang) mata kuliah Data Warehouse (2025), Universitas Multimedia Nusantara.
Peran saya: perancangan skema, visualisasi dashboard, dan laporan.

**Tools:** Power BI · DAX · Power Query

## Latar Belakang
Data publikasi riset UMN tersebar di berbagai format, sehingga sulit membandingkan kinerja riset antar fakultas dan program studi. Data warehouse dibangun untuk menyatukan data tersebut dan mendukung keputusan berbasis data.

## Yang Dikerjakan
- **Skema data warehouse** dengan fact table publikasi (601 baris, satu baris per publikasi), bridge table publikasi–dosen untuk relasi many-to-many, dan dimensi dosen, program studi, fakultas, tipe publikasi, venue, waktu, serta peringkat CiteScore (Q1–Q4).
- **DAX measures:** PublicationCount, AuthorCount, Publications_Q1–Q4, dan Q1_Share.
- **Power Query** untuk pembersihan dan transformasi data.
- **Halaman dashboard** analitik, termasuk kolaborasi lintas program studi dan halaman kualitas data.

*Dataset dosen dan file .pbix tidak dipublikasikan karena berisi data internal kampus.*
