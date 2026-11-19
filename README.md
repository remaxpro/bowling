# Landing Page Catering Jogja – Bowl-Ling

Landing page statis untuk iklan Google Ads dan SEO dengan keyword **catering jogja**, **nasi box jogja**, dan **nasi dus jogja**.

## Isi
- `index.html`: halaman lengkap (HTML + CSS inline), siap dipasang di hosting mana pun atau GitHub Pages.
- `assets/`: foto (WebP) dan logo Bowl-Ling.
- `google-ads-sitelinks.csv`: 8 aset sitelink (teks ≤25, deskripsi ≤35 karakter), siap diinput ke Google Ads / Google Ads Editor.

## Sudah termasuk
- Title, meta description, canonical, Open Graph.
- Schema JSON-LD `FoodEstablishment` + `FAQPage`.
- Anchor section untuk sitelink: `#nasibox`, `#prasmanan`, `#acara`, `#carapesan`, `#galeri`, `#testimoni`, `#faq`, `#kontak`.
- Event `wa_click` ke `dataLayer` setiap tombol WhatsApp diklik. Di GTM: buat trigger Custom Event `wa_click` → tag Google Ads Conversion.

## Sebelum live
1. Ganti URL `https://bowllingfruit.com/catering-jogja` (canonical, og:image, schema, CSV) jika alamat final berbeda.
2. Tempel snippet Google Tag Manager di tempat yang ditandai di `<head>` (dan bagian `<noscript>` setelah `<body>`).
3. Isi semua placeholder bertanda `[ ... ]`: isi menu nasi box, minimal order, DP, area antar/ongkir, jam operasional, layanan prasmanan, dan 3 testimoni asli.
4. Konfirmasi nomor WhatsApp (dipakai: 0878-3990-0065, Ocha).
5. Pasang sitelink #6 (FAQ) dan #8 (Testimoni) setelah konten aslinya terisi.
