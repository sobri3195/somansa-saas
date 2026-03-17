# Somansa SaaS

Platform **SaaS berbasis Laravel + Inertia + React** untuk kebutuhan manajemen bisnis modern (CRM, HRM, keuangan, penjualan, inventori, helpdesk, dan modul operasional lainnya).

## 👤 Author

**Lettu Kes dr. Muhammad Sobri Maulana, S.Kom, CEH, OSCP, OSCE**  
GitHub: [github.com/sobri3195](https://github.com/sobri3195)  
Email: [muhammadsobrimaulana31@gmail.com](mailto:muhammadsobrimaulana31@gmail.com)

## 🌐 Kanal & Komunitas Resmi

- YouTube: <https://www.youtube.com/@muhammadsobrimaulana6013>
- Telegram: <https://t.me/winlin_exploit>
- TikTok: <https://www.tiktok.com/@dr.sobri>
- WhatsApp Group: <https://chat.whatsapp.com/B8nwRZOBMo64GjTwdXV8Bl>
- Website Personal: <https://muhammadsobrimaulana.netlify.app>
- Landing Page: <https://muhammad-sobri-maulana-kvr6a.sevalla.page/>
- Toko Online Sobri: <https://pegasus-shop.netlify.app>

## ❤️ Dukungan & Donasi

Jika project ini bermanfaat, Anda bisa mendukung melalui:

- Lynk.id: <https://lynk.id/muhsobrimaulana>
- Trakteer: <https://trakteer.id/g9mkave5gauns962u07t>
- Gumroad: <https://maulanasobri.gumroad.com/>
- KaryaKarsa: <https://karyakarsa.com/muhammadsobrimaulana>
- Nyawer: <https://nyawer.co/MuhammadSobriMaulana>

---

## 🚀 Tech Stack

- **Backend**: Laravel 12 (PHP 8.2+)
- **Frontend**: React + TypeScript + Inertia.js + Vite
- **Styling**: Tailwind CSS
- **Database**: MySQL/PostgreSQL/SQLite (konfigurasi via `.env`)
- **Realtime / Integrasi**: Pusher, Socialite, Google API, Stripe, PayPal, Twilio, dll.

## 📦 Fitur Umum

Project ini dirancang sebagai fondasi SaaS multi-modul dengan kemampuan seperti:

- Manajemen pengguna & role/permission
- Manajemen data bisnis (penjualan, inventori, keuangan, dsb.)
- Helpdesk & ticketing
- Integrasi pembayaran dan notifikasi
- Dukungan email provider dan layanan pihak ketiga
- Struktur siap scale untuk custom module

> Catatan: Modul aktif dapat berbeda tergantung konfigurasi environment, migrasi, seeder, serta lisensi/fitur tambahan yang diaktifkan.

## 🧰 Persyaratan Sistem

Sebelum instalasi, pastikan environment memiliki:

- PHP **8.2+**
- Composer **2+**
- Node.js **18+** dan npm
- Database server (MySQL/PostgreSQL) atau SQLite
- Ekstensi PHP yang umum untuk Laravel (bcmath, ctype, fileinfo, json, mbstring, openssl, pdo, tokenizer, xml, dll.)

## ⚙️ Instalasi

1. Clone repository

```bash
git clone <url-repository-anda>
cd somansa-saas
```

2. Install dependency backend

```bash
composer install
```

3. Install dependency frontend

```bash
npm install
```

4. Siapkan environment

```bash
cp .env.example .env
php artisan key:generate
```

5. Konfigurasi database di file `.env`, lalu jalankan migrasi

```bash
php artisan migrate
```

6. Jalankan aplikasi (2 terminal)

```bash
php artisan serve
npm run dev
```

Akses aplikasi di: <http://127.0.0.1:8000>

## 🧪 Menjalankan Test

```bash
php artisan test
```

## 🏗️ Build Production

```bash
npm run build
```

## 📁 Struktur Direktori Inti

- `app/` — logika utama aplikasi Laravel
- `config/` — konfigurasi service dan framework
- `database/` — migrasi, factory, seeders
- `resources/` — source frontend (React/TS), CSS, views
- `routes/` — routing web, API, auth, console, dll.
- `public/` — entrypoint web & aset publik
- `tests/` — automated tests

## 🔐 Keamanan

Untuk pelaporan celah keamanan, silakan hubungi langsung:

📧 **muhammadsobrimaulana31@gmail.com**

Mohon tidak mempublikasikan detail celah sebelum proses mitigasi selesai.

## 📄 Lisensi

Project ini menggunakan lisensi **MIT**. Lihat file [`LICENSE`](./LICENSE) untuk detail lengkap.

---

Terima kasih telah menggunakan dan mendukung pengembangan **Somansa SaaS** 🙏
