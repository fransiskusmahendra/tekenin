# 🚀 Panduan Deploy Web App "TandaTangan.my.id" (Biaya Hosting Rp 0)

Web app ini dibangun menggunakan **100% Client-Side JavaScript (HTML5 Canvas)**, yang berarti:
- **Biaya Server / Hosting:** **Rp 0 (Gratis Selamanya)**
- **Kapasitas Pengunjung:** Mampu menampung 100.000+ pengunjung per hari tanpa pernah *down*, karena pemrosesan gambar berjalan di HP/laptop pengguna masing-masing.
- **Biaya Domain:** Hanya **~Rp 12.000 – Rp 14.000 per tahun** untuk ekstensi `.my.id`.

---

## 🛠️ Langkah 1: Uji Coba di Komputer Anda Sekarang

1. Buka File Explorer di Windows Anda.
2. Masuk ke folder: `C:\Users\2913\.gemini\antigravity\scratch\tandatangan-png`
3. Klik ganda file **`index.html`** untuk langsung membukanya di browser Google Chrome / Edge.
4. **Coba fitur-fiturnya:**
   - Coret tanda tangan dengan mouse/touchpad di tab *"Gambar di Layar"*.
   - Ubah warna tinta (Hitam / Biru Resmi / Merah) dan tebal garis.
   - Klik **"Unduh PNG Transparan"** atau **"Salin ke Clipboard"** lalu coba *paste* (Ctrl+V) langsung ke dokumen Word.
   - Pindah ke tab *"Scan Foto Kertas"*, coba upload foto tanda tangan di atas kertas, lalu geser slider *Threshold* untuk melihat latar kertasnya hilang menjadi bening!

---

## 🌐 Langkah 2: Beli Domain Murah di Domainesia (~Rp 12.000/tahun)

1. Buka situs [Domainesia.com](https://www.domainesia.com).
2. Di kolom pencarian domain, cari nama yang Anda sukai dengan akhiran `.my.id`, contohnya:
   - `tandatangan.my.id`
   - `tandatanganku.my.id`
   - `paraf.my.id`
   - `ttdonline.my.id`
3. Harga resmi domain `.my.id` biasanya berkisar antara **Rp 12.000 – Rp 14.000**.
4. Bayar menggunakan **QRIS (GoPay/OVO/Dana/BCA)** dan upload foto KTP Anda untuk aktivasi instan dari PANDI.

---

## ☁️ Langkah 3: Deploy Gratis ke Cloudflare Pages (Hosting Bebas Biaya)

1. Buka [pages.cloudflare.com](https://pages.cloudflare.com) lalu daftar akun gratis.
2. Pilih menu **Pages** > **Upload Assets** (Unggah langsung tanpa perlu GitHub jika belum mau pakai git).
3. Seret (*drag-and-drop*) file `index.html` dari folder komputer Anda ke Cloudflare.
4. Beri nama project (misal: `tandatangan-png`).
5. Klik **Deploy**. Website Anda langsung aktif dan memiliki link HTTPS gratis dalam 10 detik!
6. **Hubungkan Domain Anda:**
   - Di dashboard Cloudflare Pages, buka tab **Custom Domains**.
   - Masukkan domain `.my.id` yang Anda beli dari Domainesia.
   - Ubah DNS Nameserver di Domainesia sesuai arahan Cloudflare. Selesai!

---

## 💰 Cara Mengaktifkan Monetisasi

1. **Donasi / Saweria QRIS:**
   - Buka akun gratis di [Saweria.co](https://saweria.co) atau generate QRIS Mayar Anda.
   - Ganti teks `[QRIS / Saweria]` di dalam modal file `index.html` dengan gambar barcode QRIS Anda.
2. **Google AdSense:**
   - Setelah website aktif selama 2–3 minggu dan mulai memiliki 50–100 pengunjung per hari, daftarkan domain Anda ke Google AdSense.
   - Tempel kode skrip iklan dari AdSense ke bagian atas atau bawah kanvas tanda tangan.
