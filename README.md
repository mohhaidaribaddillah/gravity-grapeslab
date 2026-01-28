# Grapeslab Co-Working Space Website

Website modern dan responsif untuk Grapeslab, sebuah co-working space dengan desain geometris yang inovatif.

## 📋 Daftar Halaman

Website ini terdiri dari 5 halaman utama:

1. **index.html** - Halaman utama dengan hero section, statistik, fitur, workspace populer, pricing, dan testimonial
2. **about.html** - Halaman Tentang Kami dengan cerita perusahaan, visi, misi, nilai-nilai, tim, dan pencapaian
3. **workspace.html** - Halaman katalog workspace dengan filter kategori (Hot Desk, Dedicated Desk, Private Office, Meeting Room)
4. **blog.html** - Halaman blog dengan fitur pencarian dan 6 artikel
5. **contact.html** - Halaman kontak dengan form, informasi kontak, FAQ, dan peta lokasi

## 🎨 Fitur Utama

### Responsive Design
- ✅ Fully responsive untuk desktop, tablet, dan mobile
- ✅ Mobile menu yang smooth tanpa glitch
- ✅ Tidak ada horizontal scroll di mobile
- ✅ Semua elemen proporsional di semua ukuran layar

### Interaktivitas
- ✅ Mobile hamburger menu
- ✅ Scroll to top button (muncul setelah scroll 300px)
- ✅ Floating WhatsApp button di semua halaman
- ✅ Search functionality di halaman blog
- ✅ Filter workspace berdasarkan kategori
- ✅ FAQ accordion di halaman contact
- ✅ Form yang terintegrasi dengan WhatsApp

### Integrasi WhatsApp
Semua fitur kontak dan booking terintegrasi dengan WhatsApp:
- Floating WhatsApp button di pojok kanan bawah
- Booking workspace langsung via WhatsApp
- Contact form mengirim pesan via WhatsApp
- Newsletter subscription via WhatsApp
- Share artikel blog ke WhatsApp

## 🚀 Cara Menggunakan

1. **Download/Clone** semua file ke folder yang sama
2. **Simpan logo** yang telah di-generate sebagai `logo.png` di folder yang sama
3. **Buka** file `index.html` di browser untuk melihat website
4. **Ganti nomor WhatsApp** di semua halaman:
   - Cari `1234567890` dan ganti dengan nomor WhatsApp Anda (format: 628xxxxxxxxxx untuk Indonesia)

## 📱 Nomor WhatsApp

Untuk mengaktifkan fitur WhatsApp, ganti nomor `1234567890` dengan nomor WhatsApp bisnis Anda di semua file HTML:

```html
<!-- Contoh: -->
href="https://wa.me/1234567890?text=..."

<!-- Ganti menjadi (contoh untuk Indonesia): -->
href="https://wa.me/628123456789?text=..."
```

## 🎯 Teknologi yang Digunakan

- **HTML5** - Struktur website
- **Tailwind CSS** - Framework CSS via CDN
- **JavaScript Vanilla** - Interaktivitas
- **Google Fonts** - Font Manrope
- **Material Symbols** - Icon set
- **Unsplash** - Placeholder images

## 📝 Customization

### Mengubah Warna Primary
Edit bagian `tailwind.config` di setiap file HTML:

```javascript
colors: {
    "primary": "#ec6d13", // Ganti dengan warna pilihan Anda
    ...
}
```

### Mengubah Gambar
Semua gambar menggunakan Unsplash. Anda bisa mengganti URL gambar dengan:
- Gambar dari Unsplash lainnya
- Upload gambar sendiri dan ganti path-nya
- Gunakan layanan image hosting

### Mengubah Konten
Semua konten dalam bahasa Indonesia dan dapat diubah langsung di file HTML sesuai kebutuhan bisnis Anda.

## 🌐 Browser Support

Website ini kompatibel dengan:
- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📦 File Structure

```
grapeslab/
│
├── index.html          # Halaman utama
├── about.html          # Tentang Kami
├── workspace.html      # Katalog Workspace
├── blog.html           # Blog
├── contact.html        # Contact Us
├── logo.png            # Logo Grapeslab
└── README.md           # Dokumentasi ini
```

## ⚡ Performance Tips

1. **Optimize Images**: Compress semua gambar sebelum upload
2. **Use CDN**: Tailwind CSS dan fonts sudah menggunakan CDN
3. **Lazy Loading**: Tambahkan `loading="lazy"` pada tag `<img>` untuk performa lebih baik
4. **Minify**: Minify HTML, CSS, dan JS sebelum production

## 🔧 Troubleshooting

### Logo tidak muncul
- Pastikan file `logo.png` ada di folder yang sama dengan file HTML
- Atau gunakan logo SVG default yang sudah ada di kode

### WhatsApp tidak berfungsi
- Pastikan nomor WhatsApp sudah diganti dengan format yang benar
- Format: `628xxxxxxxxxx` (untuk Indonesia, tanpa tanda +)

### Mobile menu tidak smooth
- Pastikan JavaScript sudah diload dengan benar
- Check console browser untuk error

## 📄 License

Website ini dibuat untuk Grapeslab Co-Working Space. Silakan customize sesuai kebutuhan bisnis Anda.

## 💡 Tips Pengembangan Lebih Lanjut

1. **Tambahkan Backend**: Integrasikan dengan backend untuk menyimpan data booking
2. **Payment Gateway**: Tambahkan sistem pembayaran online
3. **Member Dashboard**: Buat dashboard untuk member yang sudah terdaftar
4. **Booking System**: Implementasi sistem booking real-time
5. **Analytics**: Tambahkan Google Analytics untuk tracking visitor
6. **SEO**: Optimize meta tags dan structured data untuk SEO

## 📞 Support

Jika ada pertanyaan atau butuh bantuan, hubungi:
- Email: hello@grapeslab.com
- WhatsApp: +1 (555) 123-4567

---

**Dibuat dengan ❤️ untuk Grapeslab Co-Working Space**
