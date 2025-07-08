# pratikum_uas

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Playwright](https://playwright.dev)

```sh
# Install browsers for the first run
npx playwright install

# When testing on CI, must build the project first
npm run build

# Runs the end-to-end tests
npm run test:e2e
# Runs the tests only on Chromium
npm run test:e2e -- --project=chromium
# Runs the tests of a specific file
npm run test:e2e -- tests/example.spec.ts
# Runs the tests in debug mode
npm run test:e2e -- --debug
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```


# 🏥 Klinik Sehat - Aplikasi Manajemen Klinik

Aplikasi **Klinik Sehat** adalah aplikasi berbasis **Vue.js** yang dirancang untuk membantu pengelolaan data di klinik, mulai dari pasien, dokter, pendaftaran, rekam medis hingga laporan.

---

## 📌 Fitur Utama

- **Dashboard**: Menampilkan ringkasan data penting seperti jumlah pasien, dokter, dan statistik kunjungan.
- **Manajemen Pasien**: Tambah, ubah, dan hapus data pasien.
- **Manajemen Dokter**: Kelola data dokter yang bertugas di klinik.
- **Pendaftaran Pasien**: Formulir untuk mendaftarkan pasien untuk pemeriksaan.
- **Rekam Medis**: Menyimpan riwayat pemeriksaan medis pasien.
- **Laporan**: Menampilkan laporan kunjungan dan aktivitas lainnya.
- **Login**: Autentikasi pengguna untuk membatasi akses halaman tertentu.

---

## 🛠️ Teknologi yang Digunakan

- [Vue.js 3](https://vuejs.org/)
- [Vue Router](https://router.vuejs.org/)
- [Font Awesome](https://fontawesome.com/) untuk ikon
- HTML & CSS dasar

---

## 🚀 Cara Menjalankan Proyek

### 1. Clone repositori

```bash
git clone https://github.com/username/klinik-sehat.git
cd klinik-sehat
