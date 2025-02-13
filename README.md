# Website Pengaduan Masyarakat

Website ini dibuat untuk memudahkan masyarakat dalam menyampaikan pengaduan terkait berbagai permasalahan di lingkungan mereka. Dibangun menggunakan **Laravel** sebagai backend dan **Bootstrap** untuk tampilan antarmuka yang responsif.

## Fitur Utama
- **Registrasi & Login:** Masyarakat dapat mendaftar dan masuk untuk mengirim pengaduan.
- **Kelola Pengaduan:** Pengguna dapat membuat, melihat, dan mengedit pengaduan mereka.
- **Tanggapan dari Admin:** Admin dapat memberikan tanggapan terhadap setiap pengaduan yang masuk.
- **Manajemen Data:** Admin dapat mengelola pengguna dan laporan pengaduan.
- **Notifikasi:** Memberikan update status pengaduan kepada pelapor.
- **UI Responsif:** Menggunakan Bootstrap untuk tampilan yang ramah pengguna di berbagai perangkat.

## Teknologi yang Digunakan
- **Framework Backend:** Laravel
- **Frontend:** Blade Template, Bootstrap
- **Database:** MySQL
- **Autentikasi:** Laravel Breeze atau Laravel Jetstream

## Instalasi
1. **Clone repositori:**
   ```bash
   git clone https://github.com/username/pengaduan-masyarakat.git
   cd pengaduan-masyarakat
   ```
2. **Install dependencies:**
   ```bash
   composer install
   npm install
   ```
3. **Konfigurasi file .env:**
   - Duplikat file `.env.example` dan ubah namanya menjadi `.env`
   - Sesuaikan konfigurasi database
4. **Generate key dan migrasi database:**
   ```bash
   php artisan key:generate
   php artisan migrate --seed
   ```
5. **Jalankan server aplikasi:**
   ```bash
   php artisan serve
   ```
6. **Jalankan frontend build (opsional):**
   ```bash
   npm run dev
   ```

## Cara Penggunaan
1. **Masyarakat** dapat mendaftar dan masuk untuk mengirim pengaduan.
2. **Admin** dapat melihat daftar pengaduan dan memberikan tanggapan.
3. Setiap pengaduan yang dikirim akan mendapat status yang dapat diperbarui oleh admin.

## Kontribusi
Jika ingin berkontribusi, silakan fork repositori ini dan buat pull request dengan perubahan yang diusulkan.

## Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---
Dibuat dengan ❤️ menggunakan Laravel & Bootstrap.
author Ahmad Nur Mu'minin
