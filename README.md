# ⚡ IDMFlix - Multi-Cloud Storage SaaS
**IDMFlix** adalah platform penyimpanan awan modern yang menggabungkan estetika *Baby Blue* yang minimalis dengan teknologi *Multi-Cloud Storage*. Proyek ini dirancang untuk memberikan kapasitas besar secara gratis dengan memanfaatkan infrastruktur Cloudflare R2 dan Backblaze B2.
## ✨ Fitur Utama
 * ✅ **Multi-Node Storage**: Terhubung ke Cloudflare R2 (10GB) dan Backblaze B2 (10GB).
 * ✅ **Zero-Knowledge Encryption**: File dienkripsi menggunakan AES-256 secara lokal sebelum dikirim ke server.
 * ✅ **SaaS Ready**: Dilengkapi dengan UI sistem langganan (Free vs Pro).
 * ✅ **Serverless**: Berjalan sepenuhnya tanpa VPS menggunakan Firebase dan Cloudflare Workers.
 * ✅ **Modern UI**: Desain responsif dengan Tailwind CSS dan Phosphor/Lucide Icons.
## 🛠️ Stack Teknologi
 * **Frontend**: HTML5, Tailwind CSS, JavaScript (ES6+)
 * **Hosting**: Vercel
 * **Database & Auth**: Firebase Firestore & Auth
 * **Storage Node**: Cloudflare R2 & Backblaze B2
 * **Bridge Backend**: Cloudflare Workers
## 🚀 Cara Instalasi (Deployment)
### 1. Persiapan Firebase
 * Buat proyek di Firebase Console.
 * Aktifkan **Anonymous Auth**, **Firestore**, dan **Storage**.
 * Salin konfigurasi Firebase ke dalam file index.html.
### 2. Persiapan Cloudflare (Opsional untuk Upload Nyata)
 * Buat Bucket di Cloudflare R2.
 * Deploy Worker menggunakan kode worker.js (lihat dokumentasi internal).
### 3. Deploy ke Vercel
 1. Push kode ini ke repositori GitHub Anda.
 2. Masuk ke Vercel.
 3. Klik **"Add New Project"** dan pilih repositori ini.
 4. Klik **Deploy**.
## 🛡️ Keamanan
Aplikasi ini menerapkan privasi tingkat tinggi di mana kunci enkripsi tidak pernah dikirim ke server. Hanya pemilik akun yang dapat mendekripsi dan melihat isi file mereka sendiri.
Dikembangkan dengan ❤️ oleh IDMFlix Team.
