# AI Video Generator with InceptionLabs

Bikin video AI dari Teks & Gambar. Ada Login, History, Sistem Credit.

### Fitur
- Login Google
- Text to Video & Image to Video  
- Pilih Rasio 9:16, 16:9, 1:1
- History Video
- 5 Credit Gratis / user

### Cara Deploy 1 Klik

#### 1. Backend - Railway
Klik tombol di bawah → Add Env `INCEPTION_API_KEY`
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/pyz24/ai-video-generator&rootDirectory=backend)

Copy URL Railway setelah deploy. Contoh: `https://backend.up.railway.app`

#### 2. Frontend - Vercel
Klik tombol di bawah → Add Env `NEXT_PUBLIC_API_URL=url_railway_kamu`
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/pyz24/ai-video-generator&project-name=ai-video-frontend&root-directory=frontend&env=NEXT_PUBLIC_API_URL)

### Env yang dibutuhkan
Backend: `INCEPTION_API_KEY`
Frontend: `NEXT_PUBLIC_API_URL`, `NEXTAUTH_SECRET`, `GOOGLE_CLIENT_ID`, `GOOGLE_CLIENT_SECRET`
