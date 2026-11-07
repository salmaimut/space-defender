# Space Defender — Nebula Assault

> Vertical arcade shooter: bertahan di nebula, hancurkan Void Mothership, dan isi POWER untuk mengaktifkan OVERDRIVE.

🌐 **Live Demo:** https://salmaimut.github.io/space-defender/

## Fitur Utama
- Arena vertikal 9:16 dengan nebula ungu/biru dinamis, starfield parallax, dan asteroid mengambang.
- Boss alien raksasa (Void Mothership) dengan health bar, formasi escort, dan pola serangan bertahap: aimed burst, fan, spiral, ring, serta laser beam.
- Efek ledakan partikel api/percikan, shockwave, screen shake, dan hit flash.
- Render internal 1440×2560 (supersampling 2x) agar tajam di layar HD/retina.
- **Hangar / Garasi 13 kapal** dengan 5 tier (Common sampai Legendary/Mythic), harga kristal, preview canvas, dan efek pasif yang benar-benar mengubah gameplay.
- **Ekonomi kristal free-to-play**: kristal didapat dari musuh dan boss, lalu tersimpan permanen di LocalStorage. Tidak ada pembayaran uang asli.
- **Stat scaling per skin**: damage, fire rate, hull/power, kecepatan, spread, dual/triple laser, kritikal boss, dan bonus kristal.
- Panel Hangar menampilkan nama kapal, nomor lambung, tier, harga, status efek pasif, serta tombol beli/pasang.
- Render pesawat di Canvas berubah bentuk, warna, nomor lambung, dan efek mesin sesuai skin yang di-equip.
- POWER bar yang terisi dari hit/kill membuka OVERDRIVE (laser pusat + spread shot); kapal tertentu mempercepat pengisian.
- UI HUD modern: skor, wave, hull, power meter, boss health, wallet kristal sesi, pause, dan mute.
- Leaderboard Top 10 tersimpan di LocalStorage, input call sign 1–15 karakter.
- Efek suara disintesis Web Audio API tanpa file eksternal.
- Satu file `index.html`, tanpa build tools atau dependensi.

## LocalStorage
- `arcade_crystals` — total kristal permanen.
- `arcade_ships_owned` — daftar ID skin yang sudah dibeli.
- `arcade_equipped_ship` — skin yang sedang di-equip.
- `arcade_leaderboard` dan `arcade_last_username` — leaderboard dan nama pilot.
- `arcade_muted` — preferensi audio.

## Kontrol
- **WASD / Arrow keys** — gerak
- **P** atau **Esc** — pause
- **M** — mute
- **H** — buka Hangar dari menu utama
- **Sentuh & seret** — gerak di perangkat mobile
- Tembakan otomatis; pola tembakan mengikuti skin yang di-equip. POWER penuh langsung memicu OVERDRIVE.

## Cara Menjalankan Secara Lokal
Buka `index.html` di browser, atau jalankan server statis:

```bash
python -m http.server 8000
```

Lalu buka `http://localhost:8000/`.
