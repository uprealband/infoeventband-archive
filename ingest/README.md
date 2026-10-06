# IEB External Source Ingestion

Direktori ini adalah jembatan antara sumber eksternal yang berkaitan dengan sejarah IEB dan arsip kanonik IEB.

## Sumber yang dipantau

- Blog Uprealband: `https://www.uprealband.com/`
- GitHub Uprealband: `uprealband/perjalanan-band-indie`

## Aturan penting

Perubahan dari Uprealband **tidak otomatis dianggap sebagai fakta arsip IEB**.

Alurnya:

```
Uprealband blog / GitHub
        ↓
deteksi perubahan
        ↓
kandidat sumber
        ↓
review / kurasi
        ↓
claim + provenance
        ↓
IEB archive
        ↓
Blogger IEB membaca JSON terbaru
```

Dengan model ini, satu kejadian dapat muncul di beberapa timeline tanpa menggandakan fakta:

- Timeline Uprealband
- Timeline IEB
- Timeline Reflexion
- Timeline Brebeg Online Radio

Hubungan antar-entitas dicatat sebagai relasi, bukan dengan menggabungkan identitas.

## Status

`needs_review` berarti sumber terdeteksi relevan, tetapi belum boleh diperlakukan sebagai fakta arsip terverifikasi.
