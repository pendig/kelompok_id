# Kelompok.id Landing Page

Landing page resmi [Kelompok.id](https://kelompok.id), dibangun dengan [Astro](https://astro.build/).

> **Coming soon:** platform Kelompok masih dalam tahap pengembangan dan belum dirilis.

Kelompok disiapkan untuk membantu organisasi dan komunitas membangun profil publik, membagikan kegiatan, membuka donasi secara transparan, dan melaporkan dampak.

## Uji coba dan waitlist

Organisasi atau komunitas yang ingin mengikuti uji coba dan masuk waitlist dapat mengirim DM ke Instagram [@kelompok_id](https://www.instagram.com/kelompok_id).

## Menjalankan secara lokal

Persyaratan:

- Node.js 22
- npm

```sh
npm install
npm run dev
```

Server pengembangan tersedia di `http://localhost:4321`.

## Build produksi

```sh
npm run build
```

Hasil build statis tersedia di direktori `dist/`.

## Deployment

Repository ini disiapkan untuk deployment otomatis melalui Cloudflare Pages:

- Production branch: `main`
- Build command: `npm run build`
- Build output directory: `dist`

Setiap push ke `main` akan memicu deployment produksi setelah integrasi GitHub di Cloudflare Pages diaktifkan.

## Struktur utama

```text
public/             Aset statis dan identitas visual
src/pages/          Halaman Astro
astro.config.mjs    Konfigurasi Astro
```

## Instagram

Ikuti perkembangan Kelompok di [instagram.com/kelompok_id](https://www.instagram.com/kelompok_id).
