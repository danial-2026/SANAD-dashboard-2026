# SANAD Integrated Dashboard

Prototipe dashboard riset dan audit konten keagamaan berbasis HTML statis.

## Struktur
```text
SANAD/
├── index.html
├── README.md
└── assets/
    ├── logo-uin-bandung.png
    └── logo-kemenag.png
```

## Menjalankan secara lokal
Buka `index.html` di browser modern. Untuk pengujian yang lebih konsisten, jalankan server statis lokal dari folder ini, misalnya:

```bash
python -m http.server 8000
```

Lalu buka `http://localhost:8000`.

## Deploy ke GitHub Pages
1. Upload seluruh isi folder ini ke root repository GitHub.
2. Buka **Settings → Pages**.
3. Pilih branch yang digunakan dan folder `/ (root)`.
4. Simpan dan tunggu proses deploy selesai.

## Logo
Logo UIN Sunan Gunung Djati Bandung dan Kementerian Agama berada di `assets/`.
Nama file dan jalur logo telah disesuaikan dengan referensi pada `index.html`.

## Catatan prototipe
- Aplikasi merupakan frontend statis; belum terhubung ke backend atau database bersama.
- Hasil kalkulasi SANAD adalah simulasi berbasis indikator, bukti, dan sumber yang diinput pengguna.
- Penilaian dan keputusan substantif tetap memerlukan verifikasi manusia.
- Data audit lokal disimpan pada browser/perangkat yang digunakan.
