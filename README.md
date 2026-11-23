# Prototype Operasional Toko — V1.3

Prototype awal berbasis HTML, CSS, dan JavaScript murni.

## Menjalankan lokal
Buka `index.html` di browser. Untuk pengalaman lebih baik, jalankan lewat server lokal (contoh VS Code Live Server).

## Saat ini
- Sidebar navigasi untuk blueprint modul
- Dashboard minimal: identitas toko dan ilustrasi counter BRILink, tanpa statistik
- Pengaturan identitas toko disimpan sementara di localStorage browser
- Placeholder halaman modul

## Tahapan integrasi berikutnya
1. Supabase Auth, PostgreSQL, Storage, dan Row Level Security
2. Master data dan migrasi pengaturan dari localStorage ke Supabase
3. Transaksi dan FIFO berbasis batch
4. OCR bukti transaksi
5. Printer / template dokumen
6. GitHub repository dan deployment Cloudflare Pages

Jangan letakkan Supabase service-role key di frontend. Gunakan anon/publishable key dengan Row Level Security.
