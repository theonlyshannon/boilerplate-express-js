# Express.js TypeScript Boilerplate with CRUD Generator

Boilerplate Express.js yang dibangun dengan TypeScript dan dilengkapi dengan CRUD generator untuk mempercepat pengembangan aplikasi.

## Fitur Utama

- 🚀 Express.js dengan TypeScript
- 📦 CRUD Generator otomatis
- 🔐 JWT Authentication
- 📝 Swagger Documentation
- 🛠️ ESLint & Prettier
- 📊 PostgreSQL Database
- 🔄 TypeORM
- 🧪 Jest Testing
- 🔄 Hot Reload

## Prasyarat

- Node.js (v14 atau lebih baru)
- npm atau yarn
- PostgreSQL

## Instalasi

1. Clone repository
```bash
git clone [url-repository]
```

2. Install dependencies
```bash
npm install
# atau
yarn install
```

3. Buat file `.env` berdasarkan `.env.example`
```bash
cp .env.example .env
```

4. Konfigurasi database di file `.env`

5. Jalankan migrasi database
```bash
npm run migration:run
# atau
yarn migration:run
```

6. Jalankan aplikasi
```bash
npm run dev
# atau
yarn dev
```

## Penggunaan CRUD Generator

Untuk membuat CRUD baru, jalankan perintah:

```bash
npm run generate:crud [nama-modul]
# atau
yarn generate:crud [nama-modul]
```

Generator akan membuat:
- Entity
- Controller
- Service
- Repository
- Routes
- DTOs
- Unit Tests

## Struktur Proyek

```
src/
├── config/         # Konfigurasi aplikasi
├── controllers/    # Controller
├── entities/       # TypeORM entities
├── middlewares/    # Custom middlewares
├── repositories/   # Database repositories
├── routes/         # API routes
├── services/       # Business logic
├── types/          # TypeScript types
└── utils/          # Utility functions
```

## Testing

Jalankan test dengan perintah:

```bash
npm test
# atau
yarn test
```

## Dokumentasi API

Dokumentasi API tersedia di `/api-docs` setelah menjalankan aplikasi.

## Kontribusi

1. Fork repository
2. Buat branch fitur (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## Lisensi

[MIT](LICENSE)
