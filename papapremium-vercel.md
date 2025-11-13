# Papapremium Bag Store — Deployment Guide (English)

## 1. Create a Vercel Account
1. Go to [https://vercel.com/signup](https://vercel.com/signup)
2. Sign up with **GitHub** or your **email**.
3. After logging in, you’ll see your Vercel dashboard.

## 2. Deploy the Project
1. Click **“Add New Project” → “Upload”** in your Vercel dashboard.
2. Upload the `papapremium-store.zip` file.
3. Select **Framework = Vite** when prompted.
4. Click **Deploy** — your site will go live at an address like:
   `https://papapremium.vercel.app`

## 3. Update Bank Info
In your project folder, open:
`src/App.jsx`  
Then find and replace the following section with your real details:

```jsx
bankName: "Maybank",
accountNumber: "1234 5678 9012",
accountHolder: "Your Name",
```

## 4. Replace Product Images
Add your bag images inside:
`public/images/`  
Update image paths in the `SAMPLE_PRODUCTS` list in `App.jsx`.

## 5. Optional: Connect Your Own Domain
1. Go to **Settings → Domains** in your Vercel project.
2. Click **Add Domain**, then enter your domain (e.g. `papapremium.com.my`).
3. Update your domain DNS to point to Vercel (instructions shown automatically).

## 6. Troubleshooting
- If deployment fails, check your ZIP file structure:
  - Root folder must contain `package.json` and `src/`
- Make sure your images are in `public/images/`
- Re-deploy by clicking **Redeploy** in the Vercel dashboard.

---

# Panduan Papapremium Bag Store (Bahasa Melayu)

## 1. Cipta Akaun Vercel
1. Layari [https://vercel.com/signup](https://vercel.com/signup)
2. Daftar menggunakan **GitHub** atau **email** anda.
3. Selepas log masuk, anda akan nampak paparan utama (dashboard) Vercel.

## 2. Muat Naik Projek ke Vercel
1. Klik **“Add New Project” → “Upload”** di dashboard Vercel.
2. Pilih fail `papapremium-store.zip` dan muat naik.
3. Bila diminta, pilih **Framework = Vite**.
4. Tekan **Deploy** — laman anda akan siap di pautan seperti:
   `https://papapremium.vercel.app`

## 3. Kemas Kini Maklumat Akaun Bank
Dalam folder projek, buka fail:
`src/App.jsx`  
Cari bahagian pembayaran dan tukar kepada maklumat sebenar anda:

```jsx
bankName: "Maybank",
accountNumber: "1234 5678 9012",
accountHolder: "Nama Anda",
```

## 4. Gantikan Gambar Produk
Letakkan gambar beg anda di dalam:
`public/images/`  
Kemas kini pautan gambar di senarai `SAMPLE_PRODUCTS` dalam fail `App.jsx`.

## 5. (Pilihan) Sambungkan Domain Sendiri
1. Di Vercel, pergi ke **Settings → Domains**.
2. Klik **Add Domain**, dan masukkan domain anda (contoh: `papapremium.com.my`).
3. Ikuti arahan DNS yang diberikan oleh Vercel untuk sambungan domain.

## 6. Jika Berlaku Masalah (Troubleshooting)
- Pastikan struktur fail ZIP betul: mesti ada `package.json` dan folder `src/`.
- Pastikan gambar berada dalam `public/images/`.
- Jika deploy gagal, tekan **Redeploy** dalam dashboard Vercel.

---
Made with ❤️ for **Papapremium Bag Store** — Modern. Functional. Malaysian Style.
