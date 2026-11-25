# Flash Merek ⚡

**Urusan merek, tanpa ribet.** Prototipe web app (mobile-first + layout web/desktop) untuk pendaftaran merek ke DJKI: asesmen kesiapan, cek kelas SKM, Logo Studio in-app, formulir 9 tab DJKI, tanda tangan digital, billing, dan tracking sampai sertifikat.

> Prototipe statis (single-file HTML). Semua data — PDKI, SKM, OTP, billing, email — **simulasi**, belum terhubung ke sistem DJKI/OSS.

## Jalankan
Buka `index.html` di browser. Lebar < 900px = tampilan mobile, ≥ 900px = tampilan web dengan sidebar.

Demo OTP: `123456`

## Alur
1. **Landing** → Asesmen kesiapan (skor + kirim ke email) → Cek kelas SKM → Paket Umum Rp4.799.000
2. **Individu** → nama + email → OTP → Merek Saya (Daftar Merek Baru · Pilih logo · tabel tracking)
3. **Konsultan KI** → beranda klien, tenggat, tracking
4. **Formulir**: General → Pemohon → Kuasa → Prioritas → Merek → Kelas → Lampiran (TTD auto-save) → Review → Billing

## Struktur
```
index.html   # app (HTML + CSS + JS, tanpa dependency)
README.md
```

## Status
Prototype v4 · 25 Nov 2026 · by Probo Nogoya (IP Consultant)
