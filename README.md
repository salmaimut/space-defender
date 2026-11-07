# Space Defender — Nebula Assault

> Vertical arcade shooter: bertahan di nebula, hancurkan Void Mothership, dan isi POWER untuk mengaktifkan OVERDRIVE.

🌐 **Live Demo:** https://salmaimut.github.io/space-defender/

## Fitur Utama
- Arena vertikal 9:16 dengan nebula ungu/biru dinamis, starfield parallax, dan asteroid mengambang.
- Boss alien raksasa (Void Mothership) dengan health bar, formasi escort, dan pola serangan bertahap: aimed burst, fan, spiral, ring, serta laser beam.
- Efek ledakan partikel api/percikan, shockwave, screen shake, dan hit flash.
- Render internal 1440×2560 (supersampling 2x) agar tajam di layar HD/retina.
- Pemain menembak otomatis dengan dual cannon; POWER bar yang terisi dari hit/kill membuka OVERDRIVE (twin laser + spread shot).
- UI HUD modern: skor, wave, hull, power meter, boss health, pause, dan mute.
- Leaderboard Top 10 tersimpan di LocalStorage, input call sign 1–15 karakter.
- Efek suara disintesis Web Audio API tanpa file eksternal.
- Satu file `index.html`, tanpa build tools atau dependensi.

## Kontrol
- **WASD / Arrow keys** — gerak
- **P** atau **Esc** — pause
- **M** — mute
- **Sentuh & seret** — gerak di perangkat mobile
- Tembakan otomatis; POWER penuh langsung memicu OVERDRIVE.

## Cara Menjalankan Secara Lokal
Buka `index.html` di browser, atau jalankan server statis:

```bash
python -m http.server 8000
```

Lalu buka `http://localhost:8000/`.
