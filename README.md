# NEON LAB — Three.js 3D Explorer

Website project for a Three.js assignment. Responsive landing page with an interactive low-poly robot built from Three.js geometry, orbit/zoom controls, auto-rotate, color customization, and wireframe mode.

## Cara menjalankan
1. Extract folder `threejs_robot_project`.
2. Buka folder di VS Code.
3. Jalankan dengan extension **Live Server** (klik kanan `index.html` → Open with Live Server).
   - Alternatif: buka folder di terminal dan jalankan `python -m http.server 8000`, lalu buka `http://localhost:8000`.
4. Koneksi internet dibutuhkan untuk memuat library Three.js dari CDN dan Google Fonts.

## Isi folder
- `index.html` — website utama.
- `README.md` — petunjuk penggunaan.

## Catatan tugas Sketchfab
Versi ini memakai robot low-poly prosedural yang dibangun langsung dari geometri Three.js agar project langsung bisa dijalankan. Agar benar-benar sesuai instruksi slide tentang memilih model Sketchfab, pilih dan unduh model berlisensi yang mengizinkan penggunaan, lalu tambahkan atribusi kreator. Salah satu referensi model gratis: https://sketchfab.com/3d-models/robot-93c9ff1cac014cc382e8666c873cdd70
Setelah file `.glb` diunduh, model bisa diintegrasikan memakai `GLTFLoader` dari Three.js. Jangan mengklaim model Sketchfab sudah terpasang sebelum file GLB-nya benar-benar ditambahkan.

## Deploy
- GitHub: buat repository baru, upload isi folder ini (jangan upload ZIP-nya saja).
- Vercel: import repository GitHub tersebut, framework preset pilih **Other**, lalu Deploy.
- Pengumpulan: tautan GitHub, tautan Vercel, dan file `.glb` dari model pilihan di Google Drive sesuai format `Absen_Nama`.

## Kredit referensi
Robot model referensi: “Robot” by DJMaesen, Sketchfab, CC Attribution. https://sketchfab.com/3d-models/robot-93c9ff1cac014cc382e8666c873cdd70

## Asset tambahan
`assets/neon-robot.glb` adalah model robot orisinal sederhana untuk dicoba di software 3D. File ini **bukan** model unduhan Sketchfab; untuk syarat pengumpulan dari dosen, unduh `.glb` model Sketchfab yang kamu pilih dan kumpulkan file aslinya beserta atribusi yang sesuai.
