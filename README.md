Siap 👍 ini langsung aku kasih dalam format **Markdown** biar bisa kamu push ke repo:

# 🌐 Website Profil Padukuhan Ngelo

Proyek ini merupakan bagian dari **Program Kerja KKN UII Angkatan 71 Unit 134**.  
Tujuannya adalah membuat **website profil Padukuhan Ngelo** sebagai media informasi digital yang mudah diakses masyarakat maupun perangkat padukuhan.

Website ini masih berupa **prototype statis** dan di-host menggunakan **Vercel**.

---

## 📍 Lokasi
- **Padukuhan Ngelo**  
- Kalurahan **Petir**  
- Kapanewon **Rongkop**  
- Kabupaten **Gunung Kidul**, DIY

---

## ✨ Fitur Prototype
- **Landing Page**: Informasi umum, sejarah, potensi, dan landmark Padukuhan Ngelo.  
- **Galeri Placeholder**: Ruang untuk dokumentasi kegiatan dan foto padukuhan.  
- **Form Kontak**: Simulasi pengiriman pesan dari masyarakat.  
- **Halaman Login Admin**: Akses menuju sistem internal (dummy login).  
- **Dashboard Prototype**: Menampilkan data JSON sederhana:  
  - Populasi dan tren penduduk  
  - Data bantuan sosial  
  - Kehadiran perangkat padukuhan  
  - Administrasi surat  
  - Inventaris fasilitas  
  - Pengumuman kegiatan  

---

## 🗂 Struktur Project
```

├── index.html        # Halaman utama (profil, landmark, potensi, galeri, kontak)
├── gateway.html      # Halaman login admin
├── dashboard.html    # Halaman dashboard (data dummy dari data.json)
├── data.json         # Data statis padukuhan (populasi, bantuan, pengumuman, dll.)
└── README.md

````

---

## 🚀 Cara Menjalankan
1. Clone repository ini:
   ```bash
   git clone https://github.com/username/profil-padukuhan-ngelo.git
   cd profil-padukuhan-ngelo


2. Jalankan secara lokal dengan browser:

   * Klik **index.html** untuk membuka landing page.
   * Klik **gateway.html** untuk halaman login.
   * Login dummy:

     * Username: `admin`
     * Password: `password123`
   * Setelah login, akan diarahkan ke **dashboard.html**.

3. Deploy ke **Vercel** atau hosting statis lain.

---

## ⚠️ Keterbatasan Prototype

* **Belum ada galeri foto asli**, masih menggunakan placeholder.
* **Login & dashboard** hanya simulasi (belum ada sistem autentikasi dan database).
* **Form kontak** tidak mengirim data nyata (hanya menampilkan pesan sukses).

---

## 📌 Catatan

* Proyek ini dibuat untuk kebutuhan **KKN**, sehingga konten dapat dikembangkan lebih lanjut oleh perangkat desa/padukuhan.
* Untuk pengembangan ke depan, bisa ditambahkan:

  * Galeri foto asli kegiatan warga
  * Integrasi database untuk surat dan inventaris
  * Sistem autentikasi admin yang lebih aman
  * Desain responsif lebih lanjut

---

👨‍💻 Dibuat oleh: **Rian Nur Ikhsan**
KKN UII Angkatan 71 Unit 134 – 2025
