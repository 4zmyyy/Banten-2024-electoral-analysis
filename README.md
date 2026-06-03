# Banten 2024 Electoral Analysis 
**Pileg DPRD Provinsi + Pilgub Banten 2024 · Based On Real-Data KPU Provinsi Banten**
<img width="1300" height="700" alt="banten_2024_animated" src="https://github.com/user-attachments/assets/ecbed889-60c9-4d21-82d6-fefea07f2042" />


---

## Overview

*Analisis komprehensif hasil pemilu 2024 Provinsi Banten mencakup dua kontestasi:*

- **Pileg DPRD Provinsi Banten 2024** — 18 partai peserta, 12 dapil, 6.454.416 suara sah
- **Pilgub Banten 2024** — Airin-Ade vs Andra-Dimyati, 8 kab/kota di Provinsi Banten

**Golkar sebagai highlight utama** — partai dengan perolehan suara terbanyak di Banten 2024 dan perolehan suara terbanyak ke-2 dalam skala Nasional.

---

## Key Findings

### Pileg — Ranking Partai

| Rank | Partai | Total Suara | Share |
|------|--------|------------|-------|
| **1** | **Golkar** | **932.670** | **14.45%** |
| 2 | Gerindra | 886.432 | 13.73% |
| 3 | PDI Perjuangan | 853.565 | 13.22% |
| 4 | PKS | 762.154 | 11.81% |
| 5 | PKB | 566.720 | 8.78% |
| 6 | Demokrat | 530.362 | 8.22% |
| 7 | NasDem | 453.569 | 7.02% |
| 8 | PAN | 452.790 | 7.01% |

### Golkar — Analisis Per Dapil

| Dapil | Suara | Share | Keterangan |
|-------|-------|-------|------------|
| Banten 9 (Kab. Tangerang area) | 138.170 | 17.87% | **Tertinggi** |
| Banten 2 (Kab. Lebak) | 112.050 | 19.88% | Share tertinggi |
| Banten 10 | 74.992 | 9.73% | **Terendah** |
| Banten 5 | 116.706 | 19.16% | Basis kuat |

**Rata-rata share Golkar per dapil: 15.6%**

Top kandidat Golkar Banten 2024:
- Dapil 2: H. Fahmi Hakim — 71.374 suara
- Dapil 9: Ananda Trianh Salichan — 45.727 suara
- Dapil 11: H. Fitron Nur Ikhsan — 38.956 suara
- Dapil 5: H.A. Jaini — 43.940 suara

### Pilgub Banten 2024

| Paslon | Total Suara | Persentase |
|--------|------------|------------|
| Andra Soni – Dimyati Natakusumah | 3.102.501 | **55.9%** |
| Airin Rachmi Diany – Ade Sumardi | 2.449.183 | 44.1% |

**Pemenang: Andra-Dimyati**

Kab/kota yang dimenangkan Airin-Ade:
- Kota Tangerang Selatan (66.9%)
- Kota Cilegon (53.3%)

Kab/kota dengan margin terbesar Andra-Dimyati:
- Pandeglang (67.3%)
- Kabupaten Tangerang (60.6%)

---

## Data Sources

- KPU Provinsi Banten — Keputusan No. 30 Tahun 2024 tentang Penetapan Hasil Pileg DPRD Provinsi Banten
- KPU Provinsi Banten — Pengumuman No. 855/PL.02.6-Pu/36/2024 tentang Penetapan Hasil Pilgub Banten 2024

---

## Visualizations

### Ranking Semua Partai
<img width="1289" height="690" alt="gambar 1" src="https://github.com/user-attachments/assets/0bf399a2-77c7-4d8e-89af-b7d4e03177d6" />

### Golkar per Dapil
<img width="1389" height="590" alt="gambar 2" src="https://github.com/user-attachments/assets/25a3873c-d53f-4163-be22-553ea2559739" />

### Heatmap Top 8 Partai per Dapil
<img width="1273" height="590" alt="gambar 4" src="https://github.com/user-attachments/assets/95a19e2a-5572-4ce9-bb1a-bea30737d7e4" />

### Pilgub per Kab/Kota
<img width="1190" height="590" alt="gambar 3" src="https://github.com/user-attachments/assets/8471c0e6-2d29-4fe0-966c-73e8a45cc236" />

---

## Repository Structure

```
├── data/
│   ├── pileg_partai_per_dapil.csv     # Suara semua partai per dapil
│   ├── golkar_per_dapil.csv           # Detail Golkar per dapil + top kandidat
│   └── pilgub_per_kab_kota.csv        # Hasil Pilgub per kab/kota
├── analysis/
│   └── banten_2024_analysis.ipynb    # Notebook utama + 4 visualisasi
└── README.md
```

## Running the Analysis

```bash
pip install pandas matplotlib numpy jupyter
cd analysis
jupyter notebook banten_2024_analysis.ipynb
```

---

## Context

Banten adalah salah satu provinsi terbesar di Indonesia dengan 8 kab/kota dan 12 dapil DPRD Provinsi. Pemilu 2024 menunjukkan dominasi Golkar di tingkat suara partai, sementara di Pilgub terjadi split — urban Tangerang Selatan condong ke Airin, sementara daerah lain (Pandeglang, Lebak, Kab. Serang) menjadi basis kuat Andra-Dimyati.

Analisis ini merupakan bagian dari seri riset data pemilu Banten oleh [@4zmyyy](https://github.com/4zmyyy).
