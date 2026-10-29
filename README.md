# Rumah Quran Kuningan - Dashboard

Aplikasi dashboard manajemen Rumah Quran Kuningan (HTML statis + Firebase).

## Deploy ke Vercel via GitHub

1. Buat repo GitHub baru.
2. Push folder ini (berisi `index.html` dan `vercel.json`).
3. Buka https://vercel.com → **Add New Project** → import repo.
4. Klik **Deploy**.
5. Akses URL yang diberikan Vercel.

## Catatan
- Pastikan config Firebase sudah diisi di `index.html`.
- Firestore Rules: allow read/write jika `request.auth != null`.
- Authentication: Anonymous enabled.