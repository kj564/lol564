# 📦 Asset Packs

Repo ini berisi 2 asset pack gratis untuk game Harvest Vale.

## 1. 🌻 Sunnyside World (`/assets/`)

Asset pack utama dari **Daniel Diggle**.

- **Halaman**: https://danieldiggle.itch.io/sunnyside
- **Versi**: V2.1
- **Lisensi**: Free (bebas dipakai untuk game komersial/non-komersial)
- **Ukuran**: 5.5MB, 430 file PNG

### Struktur

```
assets/
├── Characters/Human/    # Sprite karakter (walk/idle/run/dig/water/axe, 8-9 frame strips)
├── Elements/
│   ├── Crops/           # 11 tanaman × 6 tahap tumbuh + soil/seed tiles
│   ├── Plants/          # Pohon, jamur dekorasi
│   ├── Animals/
│   └── VFX/
├── Tileset/             # Tileset utama 16px (1024×1024) + forest 32px
├── UI/                  # Ikon alat, 9-slice panel, indikator
└── Sunnyside_World_ExampleScene.png   # Scene contoh 4434×2470
```

## 2. 🥷 Ninja Adventure (`/assets/ninja-adventure/`)

**FULL pack** dari Ninja Adventure by Pixel-boy (CC0).

- **Halaman**: https://pixel-boy.itch.io/ninja-adventure-asset-pack
- **Lisensi**: CC0 1.0 Universal (bebas komersial, tanpa atribusi wajib)
- **Ukuran**: 112MB, 2234 file

### Struktur lengkap

```
assets/ninja-adventure/
├── Actor/                       # 7.8MB - karakter & musuh
│   ├── Character/              # 95 karakter unik (Boy, Ninja, Knight, Princess, dll)
│   │   └── <Name>/SpriteSheet.png + SeparateAnim/ (Walk, Idle, Attack, Jump, dll)
│   ├── CharacterAnimated/      # Versi animated karakter
│   ├── Animal/                # Hewan (cat, dog, chicken, dll)
│   ├── Boss/                   # Boss sprites
│   └── Monster/                # Musuh biasa (slime, goblin, skeleton, dll)
├── Audio/                       # 96MB - audio
│   ├── Musics/                 # Background music tracks
│   ├── Sounds/                 # SFX (footsteps, hits, UI, dll)
│   └── Jingles/                # Short musical stings
├── Backgrounds/                 # 596KB
│   ├── Tilesets/               # 20 tileset (Field, Floor, Desert, Dungeon, Interior, dll)
│   ├── Animated/               # Background elements beranimasi
│   └── Vehicles/               # Cart, boat sprites
├── Characters/                  # RENAMED sprites (used by current game code)
│   ├── Boy_walk.png, Boy_idle.png, Boy_faceset.png
│   ├── Princess_walk.png, Princess_idle.png, Princess_faceset.png
│   └── OldMan_walk.png, OldMan_idle.png, OldMan_faceset.png
├── FX/                          # 736KB - visual effects (hits, magic, explosions)
├── Items/                       # 736KB
│   ├── Food/, Tool/, Weapons/, Potion/, Scroll/
│   ├── Resource/, Treasure/, Action/, Object/, Other/
├── Ui/                          # 1.9MB - UI elements, buttons, icons, panels, themes
├── Palette.png                  # Palet warna referensi
├── preview-part-1.png          # Preview 1
├── preview-part-2.png          # Preview 2
├── Example 1-4.gif              # Example scene animations
├── README-ninja.md             # Credit asli
└── LICENSE-ninja.txt           # CC0 legal text
```

## Credit

- **Sunnyside World** © Daniel Diggle — https://danieldiggle.itch.io/sunnyside
- **Ninja Adventure** © Pixel-boy / AAA — https://pixel-boy.itch.io/ninja-adventure-asset-pack

Kedua pack bebas dipakai untuk proyek komersial & non-komersial. Atribusi tidak wajib namun diapresiasi.
