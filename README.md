# pctrain

Web app latihan harian dasar panggul (kegel), adduktor dan hip flexor dengan panduan interaktif (animasi, hitung mundur, bunyi dan suara pemandu). Program berganti tiap hari, beban naik otomatis tiap 6 sesi. Bisa dipasang di layar utama HP (PWA) dan jalan tanpa internet.

## Struktur
- `public/` semua file web (index.html, manifest, service worker, ikon)
- `wrangler.jsonc` konfigurasi Cloudflare Pages

## Deploy
Cloudflare → Workers & Pages → Create → Pages → Import an existing Git repository → pilih repo ini. Build command dikosongkan, build output directory: `public`. Setiap push ke `main` otomatis ter-deploy ke pctrain.pages.dev.

Riwayat latihan tersimpan di browser HP masing-masing (localStorage).
