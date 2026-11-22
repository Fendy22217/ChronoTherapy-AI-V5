# ChronoTherapy AI — Premium v5

Prototipe aplikasi penelitian prediksi kronoterapi untuk penentuan waktu pemberian obat antihipertensi.

**Pengembang:** apt. Fendy Prasetyawan, S.Farm., M.Farm.

**Judul disertasi:** Pengembangan Model Prediksi Kronoterapi Berbasis Machine Learning untuk Penentuan Waktu Pemberian Obat Antihipertensi.

## Pembaruan v5
- Keterangan jumlah dan jenis data sintetis dihilangkan dari tampilan aplikasi.
- Identitas visual diperbarui: palet emerald, midnight teal, indigo, lavender, champagne, dan ivory.
- Logo aplikasi diperbarui dan ikon PWA dibuat seragam.
- Kartu, tombol, tipografi, ilustrasi, navigasi, dan layar hasil dipoles untuk kesan lebih premium.
- Navigasi multi-screen tetap tersedia: Beranda, Analisis, Hasil, Panduan, dan Tentang.

## Status dan batasan model
Aplikasi ini masih merupakan prototipe eksperimental dan belum tervalidasi secara klinis. Model yang tertanam di browser merupakan demonstrasi teknis berbasis data sintetis, bukan model yang telah dibuktikan pada data pasien nyata. Jangan gunakan hasil untuk menentukan atau mengubah jadwal maupun dosis obat. Pengembangan klinis memerlukan data penelitian yang diperoleh secara etis, definisi label yang sahih, pengujian, dan validasi eksternal.

## Mengunggah ke GitHub Pages
1. Ekstrak ZIP dan unggah seluruh isi folder `ChronoTherapy_AI` ke root repository GitHub.
2. Pastikan `index.html` berada langsung di root.
3. Buka **Settings → Pages → Deploy from a branch → main → /(root) → Save**.
4. Buka URL GitHub Pages. HTTPS diperlukan agar service worker dan instalasi PWA aktif.

## Privasi
Aplikasi frontend ini memproses input di browser dan tidak mengirimkannya ke server. Jangan memasukkan identitas pasien atau data rekam medis yang dapat mengidentifikasi seseorang.
