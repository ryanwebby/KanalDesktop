
# Kanal Desktop

**Kanal Desktop** adalah aplikasi desktop yang memungkinkan pengguna untuk mengakses layanan dari [Kanal](https://app.kanal.work) melalui antarmuka desktop yang lebih efisien dan mudah diakses. Aplikasi ini dibangun menggunakan [Electron](https://www.electronjs.org/) dan memungkinkan pengalaman pengguna yang mulus baik secara online maupun offline.

## Fitur
- **Akses penuh ke kanal**: Mengakses semua fitur dari [Kanal](https://app.kanal.work).
- **Mode Fullscreen**: Aplikasi berjalan dalam mode fullscreen untuk pengalaman lebih baik.
- **Pembaruan otomatis**: Aplikasi akan secara otomatis memeriksa dan mengunduh pembaruan terbaru.
  
## Prasyarat
- **Node.js** versi 16 atau lebih tinggi.
- **npm** (Node Package Manager) yang terinstal bersama Node.js.

## Cara Menjalankan Aplikasi

### 1. **Instalasi Dependensi**
   Setelah meng-clone repository ini, jalankan perintah berikut untuk menginstal dependensi yang diperlukan:
   ```bash
   npm install
   ```

### 2. **Menjalankan Aplikasi Secara Lokal**
   Untuk menjalankan aplikasi dalam mode pengembangan, gunakan perintah:
   ```bash
   npm start
   ```

   Aplikasi akan terbuka di jendela desktop dan terhubung ke [https://app.kanal.work](https://app.kanal.work).

### 3. **Membuat Build untuk Distribusi**
   Jika Anda ingin membuat build untuk distribusi, jalankan perintah berikut:
   ```bash
   npm run build
   ```

   Ini akan menghasilkan file installer untuk platform Windows, macOS, atau Linux di folder `dist/`.

## Auto-Update
Aplikasi ini menggunakan **Electron Builder** dan **GitHub Releases** untuk fitur auto-update. Setiap kali pembaruan tersedia, aplikasi akan memberi tahu pengguna dan melakukan pembaruan otomatis saat aplikasi dijalankan kembali.

Untuk melihat pembaruan terbaru atau untuk mengunduh versi baru, kunjungi [GitHub Releases](https://github.com/YOUR_GITHUB_USERNAME/kanal-desktop/releases).

## Contributing
Jika Anda ingin berkontribusi, silakan fork repository ini dan buat pull request. Pastikan untuk menguji perubahan Anda sebelum mengajukan pull request.

1. Fork repository ini.
2. Buat cabang (`git checkout -b fitur-anda`).
3. Commit perubahan Anda (`git commit -m 'Tambah fitur baru'`).
4. Push ke cabang (`git push origin fitur-anda`).
5. Buat pull request ke `main` branch.

## Lisensi
Aplikasi ini dilisensikan di bawah **MIT License**. Lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.

## Kontak
Jika Anda memiliki pertanyaan atau masukan, jangan ragu untuk menghubungi kami melalui [GitHub Issues](https://github.com/YOUR_GITHUB_USERNAME/kanal-desktop/issues) atau email kami di **support@kanal.work**.
