# Space Defender

> Game arcade top-down: pertahankan kapal dari serangan alien, kumpulkan skor, dan catat namamu di leaderboard.

🌐 **Live Demo:** https://salmaimut.github.io/space-defender/

## Fitur Utama
- Kapal pemain vs gelombang alien dengan sistem peluru dan tabrakan.
- Skor, nyawa, pause, dan game over dengan input nama pemain.
- Leaderboard tersimpan di LocalStorage (top 10).
- Efek suara disintesis dengan Web Audio API.
- Kontrol keyboard (WASD/Arrow + Space) dan sentuhan/mouse.
- Satu file `index.html`, tanpa build tools.

## Cara Menjalankan Secara Lokal
Buka `index.html` di browser, atau jalankan server statis:

```bash
python -m http.server 8000
```

Lalu buka `http://localhost:8000/`.
