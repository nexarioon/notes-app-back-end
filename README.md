# Notes App — Back End

REST API untuk aplikasi catatan (notes), dibuat sebagai submission kelas **Dicoding: Belajar Membuat Aplikasi Back-End untuk Pemula**.

## Isi Proyek

```
src/
├── server.js     # bootstrap server (Hapi/Express handler)
├── routes.js     # definisi endpoint
├── handler.js    # logika request/response
└── notes.js      # data notes
```

## Menjalankan

```bash
npm install
npm run start
```

## Lint

```bash
npm run lint
```

## Catatan

Proyek latihan — data masih disimpan in-memory, tanpa database.
