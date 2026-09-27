# Portfolio — Full Stack Web Developer

Struktur project ini dipisah supaya jelas, sama seperti project web pada umumnya:

```
portfolio/
├── index.html      -> struktur halaman & isi konten
├── css/
│   └── style.css    -> semua styling/tampilan (warna, font, layout)
├── js/
│   └── main.js       -> semua interaksi (menu mobile, tahun otomatis di footer)
├── assets/            -> taruh foto/gambar kamu di sini (kosong, isi sendiri)
└── README.md          -> file ini
```

## Cara pakai

1. Buka `index.html` langsung di browser untuk lihat hasilnya.
2. Edit teks dan data di `index.html` — cari tanda `GANTI:` di dalam file,
   itu bagian yang perlu diisi dengan data asli kamu (nama, email, project, dll).
3. Ganti warna, font, atau spacing di `css/style.css` — semua diatur lewat
   variabel di bagian `:root` paling atas file, jadi tinggal ubah satu tempat.
4. Kalau mau tambah interaksi baru (misalnya animasi scroll), tambahkan di `js/main.js`.
5. Taruh foto profil dan screenshot project di folder `assets/`, lalu update
   path-nya di `index.html` (misalnya `assets/foto-profil.jpg`).

## Publish gratis

Upload seluruh folder ini ke salah satu:
- **Netlify** — drag & drop folder ke netlify.com/drop
- **Vercel** — `vercel deploy` lewat CLI atau import dari GitHub
- **GitHub Pages** — push folder ini ke repo GitHub, aktifkan Pages di Settings

Tidak perlu build tool atau install apa pun — murni HTML, CSS, JS.
