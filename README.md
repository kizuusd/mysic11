# Mysic - Website Playlist Musik Indonesia

Mysic adalah platform web simpel untuk playlist musik yang dibuat dengan HTML, CSS, dan JavaScript. Website ini menggunakan API Deezer untuk mencari dan memutar lagu.

## Fitur

- Desain responsif untuk berbagai perangkat
- Player musik dengan kontrol play, pause, next, dan previous
- Progress bar dan kontrol volume
- Pencarian lagu dan artis lewat API Deezer
- Tampilan dalam Bahasa Indonesia

## Penting: Mengakses Website

**Perhatian**: Untuk melihat website yang sesungguhnya, buka file `index.html` di browser Anda, BUKAN readme ini.

Jika Anda melihat dokumen ini di GitHub Pages, silakan klik link berikut untuk melihat website: [Lihat Website Mysic](./index.html)

## Cara Menggunakan Lokal

1. Download atau clone repository ini
2. Buka file `index.html` di browser Anda

## Cara Deploy

Untuk langkah-langkah detail cara men-deploy website ini, silakan lihat:
- [Panduan Deploy ke GitHub Pages](./GITHUB_PAGES.md)

## Struktur File

```
/
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   ├── deezer-api.js
│   │   ├── playlist.js
│   │   └── image-error-handler.js
│   └── images/
│       └── fallback.svg
├── .github/
│   └── workflows/
│       └── deploy.yml
├── index.html
├── 404.html
├── .nojekyll
├── robots.txt
├── sitemap.xml
└── README.md
```

## Teknologi yang Digunakan

- HTML5 & CSS3
- JavaScript (vanilla)
- API Deezer untuk data musik
- Font Awesome untuk ikon
- GitHub Pages untuk hosting

## Lisensi

MIT License 