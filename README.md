# Iki Ads
[![npm version](https://img.shields.io/npm/v/iki-ad-engine.svg)](https://www.npmjs.com/package/iki-ad-engine)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![documentation](assets/doc.png)

### *Turn your CLI tools into a dynamic communication channel.*

Bosan dengan aplikasi CLI yang statis? **IKI Ad Engine** memungkinkan kamu menyisipkan pesan dinamis, promosi projek, atau pengumuman penting langsung ke terminal user tanpa perlu melakukan update versi NPM.

---

## Kenapa Kamu Butuh IKI Ads?

* **📢 Real-Time Updates:** Ganti pesan atau promosi kapan saja melalui dashboard Cloudflare. User akan melihat update-nya saat itu juga.
* **⚡ Zero Latency Impact:** Berjalan di *Edge Network* Cloudflare. Iklan diambil secara asinkron, sehingga tidak akan memperlambat logika utama aplikasimu.
* **🛡️ Fail-Safe Protection:** Internet user mati? Library ini akan *silent* dan memastikan aplikasi utamamu tetap berjalan tanpa error.
* **🎨 Terminal-Native UI:** Desain yang cantik dengan border otomatis dan link yang bisa diklik langsung dari terminal.

---

## Instalasi & Implementasi (Hanya 30 Detik)

Cukup satu baris kode untuk membuat CLI kamu lebih interaktif.

### 1. Install

```bash
npm install iki-ad-engine

```

### 2. Pasang

```javascript
import { showAd } from 'iki-ad-engine';

// Munculkan iklan dengan probabilitas 70% agar tidak mengganggu user
await showAd(0.7);

// Jalankan logika aplikasimu di sini...

```

---

## Bagaimana Cara Kerjanya?

Library ini memisahkan antara **Logika Aplikasi** dan **Konten Pesan**. Konten dikelola di Cloudflare Workers, dipilih secara acak di sisi server, dan dikirimkan ke terminal user dalam format yang sudah teroptimasi.

## 🤝 Ayo Berkolaborasi!

Projek ini dibangun untuk membantu komunitas developer CLI agar bisa saling mempromosikan karya mereka. Punya ide fitur baru? Langsung *Open Issue* atau *Pull Request* ya!

---
