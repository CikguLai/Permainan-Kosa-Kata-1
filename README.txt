CARA 1 — words.json sebagai sumber data
1) Buka index.html dengan #edit → ubah.
2) Klik ⬇ words.json dan ganti words.json di folder/hosting.
3) Refresh pada semua peranti.

Tanpa hosting, jalankan server tempatan:
- Windows:  py -m http.server 8000
- Mac/Linux: python3 -m http.server 8000
URL: http://localhost:8000/index.html#edit

Nota: words.json akan override data dalam HTML jika wujud.
