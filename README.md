# MacroTrack

Aplikasi React + TypeScript untuk tracking kalori dan protein, dibuat dengan Vite, Tailwind CSS, Recharts, Framer Motion, dan Lucide.

## Jalankan secara lokal
1. Install Node.js versi LTS.
2. Ekstrak ZIP ini.
3. Buka terminal di folder project.
4. Jalankan:
   ```bash
   npm install
   npm run dev
   ```
5. Buka alamat lokal yang ditampilkan Vite (biasanya http://localhost:5173).

## Deploy publik dengan Netlify
Cara termudah:
1. Buat akun di https://www.netlify.com/
2. Upload folder project ke GitHub, lalu hubungkan repository di Netlify.
3. Build command: `npm run build`
4. Publish directory: `dist`
5. Klik Deploy. Netlify akan memberi URL publik.

Alternatif Vercel:
1. Import repository GitHub di https://vercel.com/
2. Framework preset: Vite
3. Build command: `npm run build`
4. Output directory: `dist`
5. Deploy.

## Fitur
- Onboarding 3 langkah dan kalkulator BMR/TDEE.
- Formula Mifflin-St Jeor dan Harris-Benedict.
- Target Cut / Maintain / Bulk dan protein g/kg.
- Dashboard kalori, protein, meal timeline.
- Quick add makanan Indonesia dan input manual.
- Progress charts, data tubuh, settings, dark/light mode.
- localStorage dan export CSV.

## Catatan penting
- Data tersimpan di browser masing-masing pengguna (localStorage). Data tidak tersinkron antar perangkat atau antar pengguna.
- Setiap pengunjung memiliki data lokal sendiri.
- Quick-add nutrisi adalah estimasi, bukan database makanan tervalidasi.
- Grafik historis masih memakai data contoh untuk ilustrasi. Integrasi backend/database diperlukan untuk sinkronisasi dan histori lintas perangkat.
- BMR/TDEE adalah estimasi, bukan pengukuran medis.
