# Personal Financial Records

> Project pribadi untuk pencatatan keuangan harian.

Aplikasi pencatatan keuangan sederhana berbasis web. Data dikirim langsung ke **Google Forms** dan disimpan di **localStorage** untuk riwayat cepat.

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
- Google Forms sebagai backend

## Cara Pakai

1. Buka `index.html` di browser
2. Isi form pencatatan
3. Submit → data masuk ke Google Forms + localStorage
4. Riwayat muncul otomatis di bawah form

## Google Forms

Form action sudah diarahkan ke Google Forms ID:
[https://docs.google.com/forms/u/0/d/e/1FAIpQLSc0NULD8JRnpXHVtR4WwTxAWka0FaCB0NDahfFIOymbGoYUFg/formResponse](https://docs.google.com/forms/u/0/d/e/1FAIpQLSc0NULD8JRnpXHVtR4WwTxAWka0FaCB0NDahfFIOymbGoYUFg/formResponse)
