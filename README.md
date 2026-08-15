# 🛰️ PT TerraByte Company (TBCP)

[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-3.x_Pure-06b6d4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![HTML5](https://img.shields.io/badge/HTML5-Modern_Semantic-e34f26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/Vanilla_JS-ES6+-f7df1e?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![BIG Compliance](https://img.shields.io/badge/Standar-BIG_(KUGI)_&_ESDM-10b981?style=for-the-badge)](https://tanahair.indonesia.go.id/)

> **PT TerraByte Company** adalah pelopor solusi teknologi pemetaan geografi presisi tinggi berbasis **Synthetic Aperture Radar (SAR)**, **InSAR Deformasi Sub-Milimeter**, **Airborne LiDAR**, **Ground Penetrating Radar (GPR)**, dan **AI Geospatial Analytics (TerraPulse AI)** di Indonesia.

---

## ✨ Fitur Utama Website

### 1. 🛰️ Live Orbital Telemetry Bar
- Status sinkronisasi real-time konstelasi satelit radar (SAR-SAT 4B).
- Indikator akurasi RTK deformasi fixed (±0.8 mm) dan lock 32 SVs GNSS.
- Jam UTC live dan koordinat geospasial dinamis.

### 2. 🎯 Interactive 360° Radar Canvas HUD Simulator
- Simulasi pemindaian radar berkecepatan 60 FPS menggunakan native **HTML5 Canvas 2D API**.
- Garis sapuan beam radial, cincin rentang jangkauan (range rings), polaritas sensor (VV+VH Quad), serta crosshairs.
- Titik target anomali interaktif yang dapat di-hover (*Open-Pit Mining Slope, Tailing Dam, Fault Line, Tol Corridor*).

### 3. 🔬 6 Modalitas Radar & Penginderaan Jauh
- **Spaceborne & Airborne SAR**: Penetrasi awan, kabut, dan kanopi hutan lebat 24/7.
- **InSAR Slope Displacement**: Deteksi pergerakan tanah sub-milimeter berbasis satelit multitemporal.
- **Airborne LiDAR & Bathymetry**: Pemodelan DTM/DSM 3D dan batimetri perairan dangkal.
- **Ground Penetrating Radar (GPR)**: Deteksi utilitas bawah tanah dan struktur geologi dangkal.
- **Real-Time Ground-Based SAR (GB-SAR)**: Sistem pemantauan lereng tambang kontinu per 2 menit dengan integrasi alarm.
- **TerraPulse AI**: Mesin kecerdasan buatan untuk segmentasi tutupan lahan dan deteksi perubahan otomatis.

### 4. ⚡ Interactive Modality Explorer
- Tab switcher dinamis untuk membandingkan spesifikasi sensor, frekuensi band (X/C/L-Band), interval akuisisi, dan tingkat akurasi secara instan.

### 5. 🧮 Smart Survey Estimator
- Kalkulator kebutuhan survei interaktif dengan slider luas area (100 - 100.000 Ha) dan pilihan kompleksitas medan (*Datar, Bergelombang, Hutan Kanopi Lebat, Urban Padat*).
- Kalkulasi otomatis estimasi sensor yang direkomendasikan, durasi kerja, akurasi RMSE, serta tombol integrasi proposal ke WhatsApp.

### 6. 💼 Portofolio & Studi Kasus Geospasial
- Dokumentasi proyek nyata: Monitoring lereng tambang nikel Morowali, DTM koridor IKN Nusantara, subsidensi pesisir Pantura, dan pemetaan utilitas bawah tanah Jakarta.

---

## 🛠️ Arsitektur & Teknologi

- **Frontend Core**: HTML5 Semantic & Vanilla JavaScript (ES6+).
- **Styling**: 100% **Pure Tailwind CSS** dengan konfigurasi tema khusus (Dark Obsidian Palette `#050814`, Electric Cyan `#06b6d4`, Neon Emerald `#10b981`).
- **Canvas Rendering**: Native 2D Canvas Context tanpa dependensi library eksternal.
- **Typography**: *Plus Jakarta Sans* (Body/UI), *Space Grotesk* (Display/Headings), *JetBrains Mono* (Telemetry/Code).
- **Glassmorphism**: Backdrop blur filter, border glow transparan, dan responsive layout.

---

## 📂 Struktur Repositori

```text
TBCP/
├── Comprof.html        # Single-page web application Company Profile lengkap
└── README.md           # Dokumentasi proyek
```

---

## 🚀 Cara Menjalankan

Website ini bersifat *standalone single-file* sehingga dapat langsung dijalankan tanpa proses build:

### Opsi 1: Langsung Buka di Browser
Cukup buka file `Comprof.html` langsung menggunakan browser modern (Chrome, Edge, Firefox, Safari).

### Opsi 2: Menggunakan Live Server / Local Web Server
Jika menggunakan VS Code / Antigravity IDE:
1. Buka file `Comprof.html`.
2. Klik kanan lalu pilih **Open with Live Server**, atau jalankan perintah CLI:
```bash
# Menggunakan npx serve
npx serve .

# Atau menggunakan Python built-in server
python -m http.server 3000
```
3. Buka browser pada alamat `http://localhost:3000/Comprof.html`.

---

## 📞 Kontak & Informasi Perusahaan

- **Perusahaan**: PT TerraByte Company
- **Head Office**: Jl. Raya Semplak No.52, RT.06/RW.01, Semplak, Kec. Bogor Bar., Kota Bogor, Jawa Barat 16114
- **Field Support & AI Hub**: Jakarta & Bandung
- **Email**: [info@lexterasurvey.com](mailto:info@lexterasurvey.com)
- **WhatsApp**: [+62 811-2233-4455](https://wa.me/6281122334455)
- **Kepatuhan & Sertifikasi**: Standar BIG (KUGI Compliant), ISO 9001:2015, ISO 27001

---

&copy; 2026 PT TerraByte Company. Hak Cipta Dilindungi Undang-Undang.
