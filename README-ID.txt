AVS — ALVIS VOLLEYBALL SCOUTING
Paket siap deploy ke hosting statis (Netlify / Vercel).

CARA MENDAPATKAN LINK PUBLIK TETAP (TANPA CMD SAAT PEMAKAIAN):
1. Ekstrak ZIP ini.
2. Buat akun / masuk ke Netlify.
3. Buat repository GitHub baru, misalnya avs-volleyball-scouting.
4. Upload seluruh isi folder AVS-PUBLIC-WEB ke repository tersebut.
5. Di Netlify pilih Add new site > Import an existing project > GitHub.
6. Pilih repository AVS tersebut.
7. Build command: npm run build
   Publish directory: dist
8. Deploy. Netlify akan memberikan alamat publik seperti nama-situs.netlify.app.
9. Atur Site configuration > Change site name untuk memilih nama link yang tersedia.

Setelah deploy, AVS dapat dibuka melalui browser di HP/laptop/tablet dan jaringan operator internet mana pun selama ada koneksi internet.
Pengguna tidak perlu menjalankan CMD atau memasang Node.js.

CATATAN PENTING:
- Link publik permanen memerlukan akun hosting dan proses deploy. File ZIP saja tidak otomatis membuat URL publik.
- Nama subdomain yang diinginkan hanya bisa dipastikan tersedia saat diatur di layanan hosting.
- Data pertandingan pada aplikasi ini perlu diuji lintas perangkat. Jika masih menggunakan penyimpanan browser/localStorage, data yang tersimpan di satu perangkat/browser tidak otomatis tersinkron ke perangkat lain.
- Jangan menghapus data browser sebelum memastikan backup pertandingan tersedia.
