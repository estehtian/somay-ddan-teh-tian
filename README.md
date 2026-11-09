# SOMAY & ESTEH TIAN 3000 — GitHub Pages

Website statis multi-halaman dengan desain futuristic modern profesional.

## Isi paket
- Beranda, Somay, Esteh Tian, Paket Hemat, Promo, Galeri, Tentang, Kontak
- Pemesanan dengan keranjang dan ringkasan WhatsApp
- Halaman admin demo untuk tambah/edit/nonaktifkan/hapus produk
- Responsif untuk ponsel, tablet, dan desktop
- Tidak memerlukan build system atau biaya hosting tambahan untuk GitHub Pages

## Cara memasang ke GitHub
1. Unduh dan ekstrak ZIP ini di komputer.
2. Buka repository GitHub tujuan.
3. Pilih **Add file → Upload files**.
4. Unggah seluruh isi folder hasil ekstrak (pastikan `index.html` berada di root repository, bukan di dalam folder tambahan).
5. Isi pesan commit, misalnya `Upload website Somay Esteh Tian 3000`, lalu klik **Commit changes**.
6. Buka **Settings → Pages**.
7. Pada **Build and deployment**, pilih **Deploy from a branch**.
8. Pilih branch `main` dan folder `/ (root)`, lalu **Save**.
9. Tunggu proses publikasi selesai. Buka alamat GitHub Pages yang ditampilkan di halaman Settings → Pages.

## Mengatur WhatsApp bisnis
1. Buka folder `assets`.
2. Edit file `config.js`.
3. Ganti `628XXXXXXXXXX` dengan nomor WhatsApp bisnis, menggunakan format kode negara tanpa `+`, spasi, atau tanda baca. Contoh format: `62812XXXXXXXX`.
4. Simpan dan unggah perubahan ke GitHub.

## Mengelola menu
Buka halaman `admin.html` pada website. Fitur admin versi ini menyimpan perubahan di browser perangkat yang sedang digunakan melalui localStorage. Ini adalah panel demo sederhana, **bukan sistem admin aman** dan bukan database online. Pengunjung yang membuka website dari perangkat lain tidak otomatis melihat perubahan tersebut.

Untuk pengelolaan produk sungguhan lintas perangkat, autentikasi admin, penyimpanan foto, stok, dan database permanen, integrasikan Supabase atau backend lain. Jangan menaruh password, secret key, atau service-role key di file JavaScript publik.

## Mengganti visual emoji menjadi foto produk asli
Saat foto produk asli sudah tersedia, ganti elemen visual emoji pada `index.html` dan data `emoji` di `assets/app.js` dengan elemen gambar / URL foto yang sesuai. Gunakan foto produk milik sendiri atau yang memiliki izin penggunaan.

## Catatan
- Harga contoh dapat diedit di halaman Admin atau di `DEFAULT_PRODUCTS` dalam `assets/app.js`.
- Promo, alamat, jam operasional, dan akun media sosial masih berupa konten awal yang perlu disesuaikan.
- Pastikan nomor WhatsApp dan seluruh informasi bisnis benar sebelum website dipublikasikan.
