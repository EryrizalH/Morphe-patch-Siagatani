# Morphe Patches - Siaga Tani

Morphe patches untuk aplikasi absensi **Siaga Tani** (`id.go.pertanian.epersonal`).

## Patches

| Patch | Deskripsi |
|-------|-----------|
| Disable mock location detection | Bypass deteksi fake GPS agar bisa menggunakan mock location tanpa root |
| Disable license check | Bypass verifikasi lisensi PairIP agar app tetap berjalan setelah di-patch |

## Cara Pakai

Klik link berikut untuk menambahkan patches ini ke Morphe:

https://morphe.software/add-source?github=EryrizalH/Morphe-patch-Siagatani

Jika link GitHub belum terbaca karena cache GitHub raw, tambahkan URL JSON ini secara manual sebagai patch source di Morphe Manager:

```
https://raw.githubusercontent.com/EryrizalH/Morphe-patch-Siagatani/HEAD/patches-bundle.json
```

Atau tambahkan URL repository ini secara manual sebagai patch source di Morphe Manager:

```
https://github.com/EryrizalH/Morphe-patch-Siagatani
```

## Kompatibilitas

- **App:** Siaga Tani
- **Package:** `id.go.pertanian.epersonal`
- **Versi:** 1.0.6

## Build

Untuk build patches ini, ikuti [dokumentasi Morphe](https://github.com/MorpheApp/morphe-documentation).

## Lisensi

Licensed under the [GNU General Public License v3.0](LICENSE)
