# Presensi Cloud Landing Page

Folder ini siap dipakai untuk deploy landing page ke GitHub dan Vercel.

## File Penting

- `index.html` - halaman landing page utama.
- `assets/fingerprint.svg` - logo sidik jari untuk favicon/browser tab.
- `assets/fingerprint-192.png` dan `assets/fingerprint-512.png` - ikon PWA/install app.
- `assets/product-preview.png` - visual utama landing page.
- `site.webmanifest` - metadata PWA sederhana.
- `vercel.json` - konfigurasi Vercel.

## Deploy ke GitHub

1. Buat repository baru di GitHub.
2. Upload seluruh folder project, atau minimal upload isi folder `landing`.
3. Jika memakai GitHub Pages:
   - Repository Settings.
   - Pages.
   - Source: Deploy from branch.
   - Pilih branch `main`.
   - Pilih folder `/root` jika isi folder `landing` diupload sebagai root repository.

## Deploy ke Vercel

1. Login ke Vercel.
2. Add New Project.
3. Import repository GitHub.
4. Pada bagian Root Directory, pilih:

   ```text
   landing
   ```

5. Framework Preset pilih:

   ```text
   Other
   ```

6. Build Command kosongkan.
7. Output Directory kosongkan.
8. Klik Deploy.

Setelah deploy, link Vercel bisa langsung dibagikan ke customer.
