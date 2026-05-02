# 📈 Trading Journal — Perpetual Futures

Web app rekapan trading perpetual futures. Simpel, cepat, dan bisa deploy ke Vercel gratis.

![preview](https://img.shields.io/badge/deploy-vercel-black?logo=vercel)
![license](https://img.shields.io/badge/license-MIT-blue)

---

## ✨ Fitur

- **Input lengkap** — tanggal, simbol, leverage, entry, TP1, TP2, SL, margin, PnL, catatan
- **Auto statistik** — Win Rate, Total PnL, ROI Margin, Avg Win/Loss otomatis terhitung
- **Risk:Reward** — dihitung otomatis dari entry / TP1 / SL
- **Filter & Search** — filter by status (WIN/LOSS/OPEN), bulan, dan simbol
- **Export CSV** — download semua data sebagai file CSV
- **Persistensi** — data disimpan di localStorage browser, tidak hilang saat refresh
- **Zero dependency** — murni HTML/CSS/JS, tidak butuh Node.js atau build step

---

## 🚀 Deploy ke Vercel

### Cara 1 — Via GitHub (direkomendasikan)

1. Fork atau clone repo ini
2. Push ke GitHub kamu
3. Buka [vercel.com](https://vercel.com) → **Add New Project**
4. Import repo → klik **Deploy**
5. Selesai! URL live langsung tersedia

### Cara 2 — Drag & Drop

1. Download repo ini sebagai ZIP
2. Ekstrak foldernya
3. Buka [vercel.com](https://vercel.com) → drag folder ke dashboard
4. Deploy otomatis

---

## 📁 Struktur Proyek

```
trading-journal/
├── index.html       # Seluruh aplikasi (UI + logic)
├── vercel.json      # Konfigurasi deploy Vercel
├── .gitignore       # File yang diabaikan Git
└── README.md        # Dokumentasi ini
```

---

## 🛠 Development Lokal

Tidak perlu install apapun. Cukup buka file langsung di browser:

```bash
# Clone repo
git clone https://github.com/username/trading-journal.git
cd trading-journal

# Buka di browser (pilih salah satu)
open index.html                    # macOS
start index.html                   # Windows
xdg-open index.html                # Linux

# Atau pakai live server (opsional)
npx serve .
```

---

## 📊 Cara Pakai

| Field | Keterangan |
|---|---|
| **Simbol** | Nama pair, contoh: `BTCUSDT`, `ETHUSDT` |
| **Leverage** | Leverage yang dipakai (1x–125x) |
| **Entry** | Harga masuk posisi |
| **TP1 / TP2** | Target profit 1 dan 2 |
| **SL** | Stop loss |
| **Margin** | Modal yang dialokasikan (USDT) |
| **PnL** | Profit/loss aktual setelah trade ditutup |
| **Status** | OPEN / WIN / LOSS |

---

## 💡 Tips

- Isi **Margin** dengan benar agar ROI terhitung akurat
- Gunakan filter **bulan** untuk review performa per periode
- Export CSV secara rutin sebagai backup data
- Data tersimpan di browser — jika pakai browser berbeda, data tidak sinkron

---

## 📝 License

MIT — bebas dipakai dan dimodifikasi.
