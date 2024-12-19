
<h1 align="center">GoMealSaver</h1>
<p align="center">GoMealSaver is a web-based application for selling leftover / unsold food.</p>

<br />
<p align="center">
    <img  src="./imagess.png">
</p>

# Capstone Project Dicoding X Kampus Merdeka Batch 7

<h4> Kelompok: CS7-F004 </h4>
<h4> Tema: Green Economy dan Green Jobs. </h4>
<h4> Nama Aplikasi: GoMealSaver </h4>
<p> Durasi Pengerjaan Projek: 19 November 2024 - 19 November 2024 </p>

### Latar Belakang:
Latar belakang dari proyek ini berangkat dari tingginya tingkat food wasteglobal yang mencapai 931 juta ton setiap tahunnya, padahal sebagian besarmakanan tersebut masih bisa dikonsumsi. Penjual seringkali tidak memiliki saluranuntuk menjual makanan sisa mereka, sementara banyak konsumen yangsebenarnya berminat untuk membelinya dengan harga lebih murah. Kami memilihproyek ini karena percaya bahwa platform digital dapat menjadi solusi untukmasalah food waste dengan menghubungkan konsumen dan penjual secaralangsung.

Website ini diharapkan dapat menjadi "painkiller" dengan memberikanmanfaat nyata kepada para penjual dalam mengurangi food waste sekaligusmemberikan keuntungan finansial dan lingkungan. Bagi konsumen, platform inimenawarkan akses ke makanan yang lebih terjangkau, sehingga dapatberkontribusi dalam mengurangi dampak food waste secara kolektif. Kamimengadopsi metode design thinking untuk memastikan bahwa platform iniberorientasi pada kebutuhan pengguna dan memberikan dampak yang maksimal.

## Fitur Pada GoMealSaver

Berikut adalah beberapa fitur terkini yang dimiliki GoMealSaver:

- [x] Autentikasi pengguna dengan Google & Next Auth
- [x] Registrasi Akun 
- [x] ke amanan recaptcha 
- [x] Otorisasi pengguna
- [x] Perlindungan rute
- [x] Profil pengguna dengan daftar pengguna
- [x] Daftar makanan CRUD
- [x] Unggahan gambar makanan 
- [x] Pencarian makanan
- [x] Pesan internal dengan notifikasi 'belum dibaca'
- [x] Order Makanan (User)
- [x] Bukti Trankaksi (Pemilik / penjual)
- [x] Prosess  / Batalkan pesanan (pemilik / penjual)
- [x] Halaman About
- [x] Galeri gambar dengan penghapusan foto
- [x] Peta kotak peta
- [x] Penandaan makanan / makanan yang disimpan
- [x] Berbagi makanan ke media sosial
- [x] Desain responsif (Tailwind)
- [x] Halaman 404 khusus
- [x] Next.js Action


## GoMealSaver menggunakan teknologi berikut:

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
- [NextAuth.js](https://next-auth.js.org/)
- [React Icons](https://react-icons.github.io/react-icons/)
- [Cloudinary](https://cloudinary.com/)
- [Mapbox](https://www.mapbox.com/)
- [OpenCage](https://opencagedata.com/)
- [Maptiler](https://www.maptiler.com/)
- [React Spinners](https://www.npmjs.com/package/react-spinners)
- [React Toastify](https://fkhadra.github.io/react-toastify/)
- [React Share](https://www.npmjs.com/package/react-share)
- [reCAPTCHA](https://www.google.com/recaptcha/about/)
- [bcryptjs](https://www.npmjs.com/package/bcryptjs)
- [framer-motion](https://motion.dev/)
- [typed.js](https://mattboldt.com/demos/typed-js/)


## Deployment
 
- [GoMealSaver](https://gomealsaver.store)



## Cara Installasi di Local

- Git
- Node.js
- npm (Node Package Manager)

```bash
https://github.com/Go-Meal-Saver/GoMealSaver.git cd GoMealSaver
```

Installation

Instal dependensi proyek menggunakan npm:

```bash
npm run dev
```

Set Up Environment Variables
Buat berkas baru bernama .env di root proyek Anda dan tambahkan konten berikut:

```bash
MONGODB_URL =
NEXT_PUBLIC_DOMAIN =
NEXT_PUBLIC_API_DOMAIN =
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
NEXTAUTH_URL=
NEXTAUTH_URL_INTERNAL=
NEXTAUTH_SECRET=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
NEXT_PUBLIC_OPENCAGE_API_KEY=
NEXT_PUBLIC_MAPTILER_API_KEY=
NEXT_PUBLIC_RECAPTCHA_SITE_KEY=
RECAPTCHA_SECRET_KEY=
```

### `.env` File

Ubah nama `env.example` file ke `.env` dan isi env berikut ini:

- Dapatkan string koneksi MongoDB Anda dari klaster MongoDB Atlas Anda dan tambahkan ke `MONGODB_URI`.
- Dapatkan ID dan rahasia klien Google Anda dari akun konsol Google dan tambahkan ke `GOOGLE_CLIENT_ID` dan `GOOGLE_CLIENT_SECRET`.
- Tambahkan rahasia ke `NEXTAUTH_SECRET`. Anda dapat membuat dengan perintah berikut ini:
  ```bash
  openssl rand -base64 32
  ```
- Dapatkan nama cloud Cloudinary, kunci API, dan rahasia API dari akun Cloudinary Anda dan tambahkan ke `CLOUDINARY_CLOUD_NAME`, `CLOUDINARY_API_KEY`, dan `CLOUDINARY_API_SECRET`.
- Dapatkan token OPENCAGE Anda dari akun OPENCAGE Anda dan tambahkan ke `NEXT_PUBLIC_OPENCAGE_API_KEY`.
- Dapatkan kunci API Google MAPTILER Anda dari MAPTILER Anda dan tambahkan ke`NEXT_PUBLIC_MAPTILER_API_KEY`.
- Dapatkan kunci API Google RECAPTCHA Anda dari RECAPTCHA Anda dan tambahkan ke`RECAPTCHA_SECRET_KEY`.

Menjalankan Proyek

```bash
npm run dev
```

Buka http://localhost:3000 di browser Anda untuk melihat proyek



## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
