# manifesting-house

Visualisasi interaktif rumah modern 2 lantai di tanah 10 x 20 m. Halaman utama ada di `index.html`; situs ini menggunakan HTML, CSS, dan JavaScript tanpa proses build.

## Deploy ke Vercel

1. Import repository `kaound3rage/manifesting-house` di [Vercel](https://vercel.com/new).
2. Pilih preset **Other** dan biarkan **Root Directory** di root repository.
3. Kosongkan **Build Command**. Jika Vercel meminta **Output Directory**, gunakan `.`.
4. Klik **Deploy**. Setiap push ke `main` selanjutnya akan memicu deployment otomatis.

Three.js dimuat dari CDN cdnjs, jadi visualisasi 3D membutuhkan koneksi internet saat halaman dibuka.
