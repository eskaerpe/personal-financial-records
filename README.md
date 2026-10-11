# Personal Financial Records

> ⚠️ **PERINGATAN: PROJECT PRIBADI** — Repository ini dibuat khusus untuk pencatatan keuangan pribadi. TIDAK untuk digunakan ulang, di-clone, atau dijadikan referensi oleh pihak lain. Kode, konfigurasi form, dan ID Web App Google Apps Script bersifat privat.

> ⚠️ **WARNING: PERSONAL PROJECT** — This repository is built for personal financial tracking only. NOT intended for reuse, cloning, or reference by others. Code, form configuration, and Google Apps Script Web App ID are private.

Aplikasi pencatatan keuangan sederhana berbasis web. Data dikirim langsung ke backend Google Apps Script Web App dan disimpan di localStorage untuk riwayat cepat.

## Fitur

- **Input transaksi**: Tanggal, kategori (12 kategori dengan ikon), detail, dan nominal
- **Format Rupiah otomatis**: Input nominal otomatis terformat (mis: `25000` → `25.000`)
- **Validasi frontend**: Required field, min 3 karakter, format angka
- **Dark/Light mode**: Toggle dengan persist ke localStorage
- **Riwayat lokal**: 50 entri terakhir tersimpan di browser
- **Responsive**: Mobile-first, aman di 375px+

## Tech Stack

- HTML5 + CSS3 (custom, no framework)
- Phosphor Icons via CDN
- Vanilla JavaScript (ES6)
- Google Apps Script Web App sebagai backend

## Cara Pakai

1. Buka `index.html` di browser
2. Isi form pencatatan
3. Submit → data masuk ke Google Apps Script + localStorage
4. Riwayat muncul otomatis di bawah form
