# 🌾 Harvest Vale — 2D Top-Down Farming Game

Game web **2D top-down farming/RPG** ala Stardew Valley & Harvest Moon. Tanam, rawat, panen, dan jual hasil panenmu untuk membangun pertanian impian!

> 🎮 Mainkan langsung di: **https://kj564.github.io/lol564/**

## ✨ Fitur

- 🌍 **Dunia tile-based** dengan kamera follow & pixel-art (digambar via canvas — tanpa asset eksternal)
- 👨‍🌾 **Player 4-arah** dengan animasi berjalan & 4 arah hadir
- 🌱 **Siklus bertani lengkap**: cangkul → tanam benih → siram → tumbuh per hari → panen
- 💧 **Sistem air**: penyiram terbatas, isi ulang di kolam
- 🛒 **Toko**: beli 4 jenis benih, jual hasil panen, sistem gold
- 💬 **NPC dialog** dengan teks & name label
- 📅 **Siklus hari & musim** (Semi → Panas → Gugur → Dingin, 28 hari/musim)
- 🌙 **Day/night cycle** dengan layar menggelap saat malam
- 📦 **Inventory & gold** tersimpan otomatis di `localStorage`
- 📱 **Mobile-friendly**: D-pad on-screen + tombol Aksi (auto-deteksi touch)
- 💾 **Tanpa dependency** — single file HTML, vanilla JS, canvas murni

## 🎮 Kontrol

| Aksi | Keyboard | Mobile |
|------|----------|--------|
| Bergerak | `W A S D` / panah | D-pad on-screen |
| Pilih alat | `1` `2` `3` `4` `5` | Tap slot alat |
| Gunakan alat / interaksi | `Spasi` / `E` | Tombol Aksi |
| Buka toko (dekat toko) | `B` | — |
| Tidur (dekat rumah) | `T` | — |
| Bantuan | `H` / `?` | Tombol ? |

## 🌱 Cara Bertani

1. **Cangkul** (`1` + Spasi) — ubah rumput jadi tanah garapan
2. **Tanam benih** (`2` + Spasi) — pilih benih via toolbar (klik ulang untuk ganti jenis)
3. **Siram** (`3` + Spasi) — tiap hari, isi ulang air di kolam biru
4. **Panen** (`4` + Spasi) — saat tanaman matang (ada indikator ✨)
5. **Jual** — bawa hasil panen ke toko, tekan `B`, jual untuk dapat gold

## 🌾 Tanaman

| Tanaman | Tumbuh | Harga Benih | Harga Jual |
|---------|--------|-------------|-----------|
| 🥕 Parsnip | 3 hari | 20g | 35g |
| 🥔 Kentang | 4 hari | 50g | 80g |
| 🍅 Tomat | 5 hari | 80g | 120g |
| 🌽 Jagung | 6 hari | 100g | 150g |

## 🛠️ Teknologi

- HTML5 Canvas (pixel-perfect rendering)
- Vanilla JavaScript (tanpa framework)
- CSS3 (custom properties, animations, grid)
- Tanpa dependency eksternal — 100% self-contained

## 📦 Deploy

Game ini adalah file statis tunggal (`index.html`). Sudah otomatis di-deploy ke GitHub Pages setiap push ke branch `main` via GitHub Actions workflow (`.github/workflows/deploy.yml`).

## 📄 Lisensi

MIT — bebas digunakan, dimodifikasi, dan didistribusikan.
