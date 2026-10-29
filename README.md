# Portofolio Profesional Umi Maharani

> **D4 Business Information Systems Student | Project Manager & Front-End Developer**  
> Politeknik Negeri Malang — Jurusan Teknologi Informasi

Portofolio web berbasis *Single Page Application* (SPA) dengan tema **Engineering Information Technology**, dirancang secara presisi menggunakan **HTML5**, **Tailwind CSS**, dan arsitektur responsif bertema terang (**Light Mode**). Siap di-deploy langsung ke **Vercel** untuk keperluan pendaftaran magang industri.

---

## 🚀 Fitur Unggulan
1. **Design System Engineering**: Palet warna terang (*clean white*, *slate/steel blue* `#1e40af` dan `#2563eb`), font modern (Poppins), tanpa tema gelap atau efek AI neon.
2. **Interactive Experience & Project Filter**: Filter kategori proyek (*All*, *Software Dev*, *Project Management*, *Kompetisi Nasional*).
3. **Interactive Project Specifications Modal**: Menampilkan rincian teknis, deliverable, dan tech stack tiap proyek (Jadwalin, Arenahub, KMHE 2026, Profil Lab JTI).
4. **Curriculum Vitae Quick Access**: Modal pratinjau CV terstruktur dengan fitur cetak instan (`window.print()`) dan tautan ke portofolio lengkap di Canva.
5. **Contact & Call-To-Action**: Integrasi tombol direct email, WhatsApp, serta copy-to-clipboard email address.
6. **Vercel-Ready**: Disertai file `vercel.json` dengan konfigurasi *clean URLs* dan *security headers* siap pakai.

---

## 📁 Struktur Direktori
```text
umi-maharani-portfolio/
├── assets/
│   ├── css/
│   │   └── style.css     # File CSS eksternal kustom
│   └── images/           # Seluruh aset dokumentasi & foto portofolio
├── index.html            # File utama SPA (HTML5 + Tailwind CSS + Logic JS)
├── vercel.json           # Konfigurasi deployment & security header untuk Vercel
└── README.md             # Petunjuk penggunaan dan panduan deployment
```

---

## 🌐 Cara Deploy ke Render (Static Site)

1. **Push Perubahan ke GitHub**:
   Pastikan kode terbaru sudah di-commit dan di-push ke repositori GitHub:
   ```bash
   git add .
   git commit -m "feat: pisahkan styling internal ke css eksternal"
   git push origin main
   ```
2. **Buka Dashboard Render**:
   - Kunjungi [dashboard.render.com](https://dashboard.render.com) dan login dengan akun GitHub Anda.
3. **Buat Static Site Baru**:
   - Klik tombol **"New +"** di pojok kanan atas, lalu pilih **"Static Site"**.
   - Pilih repositori portofolio GitHub Anda (misal: `portfolio-umi-maharani` atau repositori terkait).
4. **Konfigurasi Pengaturan**:
   - **Name**: Beri nama proyek (misal: `umi-maharani-portfolio`).
   - **Branch**: `main`
   - **Root Directory**: *(kosongkan / biarkan default)*
   - **Build Command**: *(kosongkan / biarkan default)*
   - **Publish Directory**: `.` (titik / root)
5. **Klik "Create Static Site"**:
   Render akan langsung men-deploy website Anda dan memberikan URL aktif (seperti `https://umi-maharani-portfolio.onrender.com`).

---

## 🌐 Cara Deploy ke Vercel

### Opsi A: Deploy via GitHub (Direkomendasikan)
1. Buat repositori baru di akun GitHub Anda: [github.com/new](https://github.com/new) (misal: `portfolio-umi-maharani`).
2. Masuk ke folder proyek dan upload kodenya:
   ```bash
   git init
   git add .
   git commit -m "feat: initial commit portfolio umi maharani"
   git branch -M main
   git remote add origin https://github.com/Maharaaniii/portfolio-umi-maharani.git
   git push -u origin main
   ```
3. Buka dashboard [Vercel](https://vercel.com) dan login menggunakan akun GitHub Anda.
4. Klik **"Add New..."** lalu pilih **"Project"**.
5. Pilih repositori `portfolio-umi-maharani`.
6. Pada bagian **Framework Preset**, pilih **"Other"** (atau biarkan default static).
7. Klik tombol **"Deploy"**. Dalam beberapa detik website portofolio Anda sudah aktif dengan domain gratis seperti `portfolio-umi-maharani.vercel.app`!

---

### Opsi B: Deploy via Vercel CLI (Langsung dari Terminal)
1. Buka PowerShell di folder `umi-maharani-portfolio`:
   ```bash
   npx vercel
   ```
2. Ikuti instruksi login dan pilih default opsi dengan menekan `Enter`.
3. Jalankan `npx vercel --prod` untuk merilis versi produksi.

---

## 💻 Cara Menjalankan Secara Lokal di Komputer
Anda dapat membuka file `index.html` langsung dengan browser apa pun (Google Chrome, Edge, dsb) atau menggunakan live-server:
```bash
# Menggunakan npx serve
npx serve .
```
Lalu buka alamat `http://localhost:3000` di browser Anda.

---

**© 2026 Umi Maharani — Engineered with Precision.**
