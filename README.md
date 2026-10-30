# Studi Ablasi RNN, LSTM, GRU vs ANN untuk Prediksi Trafik Seluler Milan

Tugas Workshop Deep Learning — Teknik Telekomunikasi ITERA.


## Kelompok

| Peran | Nama | NIM |
|---|---|---|
| Ketua | Muhammad Rizki Akbar P. | 124400046 |
| Anggota | Muhammad Prayoga | 124400028 |
| Anggota | Asrofi T Insani Siregar | 124400064 |

- **Kelas:** [RB]
- **Lokasi kelompok:** 4 — [duomo] (4)
- **Laporan:** [`laporan-latex/main.pdf]

## Cara Menjalankan

```bash
uv sync
uv run jupyter lab
```

Buka `tugas_ablasi.ipynb`, isi `LOKASI_KELOMPOK`, lalu jalankan semua sel. Semua run tercatat di `hasil/ablasi.csv`.

Perangkat yang kami pakai: [Laptop CPU Ryzen 3 3250U], total waktu training: [15] menit.

## Ringkasan Hasil

[2–4 kalimat temuan utama, beserta angka test MAE terbaik per model.]

## Struktur

```
tugas_ablasi.ipynb      notebook eksperimen (di-commit beserta output)
data/                   data trafik per jam (Duomo + 10 lokasi tugas)
hasil/                  CSV seluruh run, tabel, dan grafik
laporan-latex/ atau laporan-typst/   sumber laporan + PDF
```

## Data

Telecom Italia Big Data Challenge (Barlacchi dkk., 2015, *Scientific Data*, lisensi ODbL), versi per jam dari Zhang dkk. (INFOCOM 2021). Disiapkan oleh pengajar di repo [mctosima/dl-workshop](https://github.com/mctosima/dl-workshop).
