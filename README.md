# profile

## ✨ Fitur
- Desain responsif dan ringan
- Navigasi tab dinamis untuk memperkenalkan diri, keahlian, proyek, dan kontak
- Formulir kontak dengan dukungan **EmailJS** dan auto-reply
- Dapat dihosting langsung melalui GitHub Pages

## 🚀 Cara Menggunakan
1. Clone repository ini atau unduh sebagai zip.
2. Buka `index.html` di browser untuk melihat secara lokal.
3. Untuk mengaktifkan formulir kontak:
   - Daftar akun di [EmailJS](https://www.emailjs.com/)
   - Buat Service ID dan Template ID
   - Ganti nilai berikut di `script.js`:
     ```js
     emailjs.init("YOUR_USER_ID");
     emailjs.send("YOUR_SERVICE_ID", "YOUR_TEMPLATE_ID", {
        ...
     });
     ```

## 🖥️ Deploy ke GitHub Pages
1. Push folder ini ke repository GitHub
2. Masuk ke **Settings > Pages**
3. Pilih source: `main` branch, folder `/ (root)`
4. GitHub akan memberikan URL portofolio kamu
