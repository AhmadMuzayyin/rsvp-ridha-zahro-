# Undangan Pernikahan Ahmad & Fatimah

Website undangan pernikahan yang responsif dengan desain premium menggunakan tema emas dan hijau.

## 📁 Struktur Folder

```
public/
├── hari-h/
│   └── index.html          (Undangan Akad Nikah)
├── pra-acara/
│   └── index.html          (Undangan Walimah/Resepsi)
├── music.mp3               (Musik latar belakang)
└── kartun.png              (Gambar dekoratif)
```

## 🌐 URL Setelah Deploy ke Vercel

- **Akad Nikah**: `https://domain-anda.vercel.app/hari-h`
- **Walimah**: `https://domain-anda.vercel.app/pra-acara`

## 🚀 Cara Deploy ke Vercel

### Step 1: Install Vercel CLI

```bash
npm install -g vercel
```

### Step 2: Login ke Akun Vercel

```bash
vercel login
```

Ikuti instruksi di terminal untuk login. Vercel akan membuka browser untuk autentikasi.

### Step 3: Deploy Project

```bash
cd /home/amd/Downloads/ridha
vercel --prod
```

Atau lebih sederhana, gunakan drag & drop:

1. Buka https://vercel.com
2. Login ke akun Anda
3. Klik "Add New" → "Project"
4. Upload folder `ridha` ini atau connect dari GitHub

### Step 4: Setelah Deploy Berhasil

- Vercel akan memberikan domain otomatis (contoh: `undangan-pernikahan.vercel.app`)
- Akses halaman dengan:
  - Akad Nikah: `https://undangan-pernikahan.vercel.app/hari-h`
  - Walimah: `https://undangan-pernikahan.vercel.app/pra-acara`

## 🎵 Asset Files

- `music.mp3` - File musik latar (ditempatkan di folder `public/`)
- `kartun.png` - Gambar dekoratif (ditempatkan di folder `public/`)

Pastikan kedua file ini ada di folder `public/` saat deploy agar bisa diakses dengan benar.

## 📱 Responsive Design

Website ini telah dioptimalkan untuk:

- Desktop (1920px+)
- Tablet (768px - 1024px)
- Mobile (320px - 767px)

## ✨ Fitur

- ✅ Desain premium dengan animasi smooth
- ✅ Support musik latar (on/off button)
- ✅ Scroll reveal animations
- ✅ Countdown timer
- ✅ Fully responsive
- ✅ Optimized untuk semua device

## 🔧 Custom Domain (Optional)

Jika ingin menggunakan custom domain:

1. Beli domain di registrar (contoh: Namecheap, GoDaddy, etc)
2. Di Vercel dashboard, masuk ke project settings
3. Pilih "Domains"
4. Tambahkan custom domain Anda
5. Update nameserver di registrar sesuai instruksi Vercel

## 📝 Edit Content

Untuk mengubah konten:

1. Edit `public/hari-h/index.html` untuk halaman Akad Nikah
2. Edit `public/pra-acara/index.html` untuk halaman Walimah
3. Update nama, tanggal, lokasi, dan informasi lainnya sesuai kebutuhan
4. Push ke repository dan Vercel akan auto-deploy

## 📞 Support

Jika ada pertanyaan tentang deployment atau perlu bantuan, silakan tanyakan!

---

Dibuat dengan ❤️ untuk Ahmad & Fatimah
