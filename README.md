# pctrain

Web app latihan harian dasar panggul (kegel), adduktor dan hip flexor dengan panduan interaktif (animasi, hitung mundur, bunyi dan suara pemandu). Program berganti tiap hari, beban naik otomatis tiap 6 sesi. Bisa dipasang di layar utama HP (PWA) dan jalan tanpa internet.

## Struktur
- `public/` semua file web (index.html, manifest, service worker, ikon)
- `wrangler.jsonc` konfigurasi Cloudflare Worker (static assets)

## Deploy
Cloudflare → Workers & Pages → Create → Import a repository → pilih repo ini. Setiap push ke `main` otomatis ter-deploy.

Riwayat latihan tersimpan di browser HP masing-masing (localStorage).
