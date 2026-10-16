# Survei Evaluasi Layanan Transportasi Online

Aplikasi web survei untuk mengevaluasi layanan transportasi online dari tiga aspek: **tarif**, **keamanan**, dan **kecepatan**. Dibuat sebagai pengembangan dari survei Google Form menjadi aplikasi web.

**Pembuat:** Laila Azahra (Elzy), NIM 240103056
**Program Studi:** Teknik Informatika, Universitas Dumai

## Fitur

- Formulir data responden (nama/inisial, usia, aplikasi yang dipakai, frekuensi pemakaian)
- 12 pernyataan skala Likert 1-5 (4 pernyataan per aspek)
- Validasi kelengkapan isian sebelum jawaban dikirim
- Jawaban tersimpan di browser (localStorage)
- Halaman hasil: jumlah responden, rata-rata per aspek (dengan grafik batang), rata-rata per pernyataan
- Unduh data jawaban dalam format CSV
- Tampilan responsif untuk HP dan laptop

## Teknologi

- HTML5, CSS3, dan JavaScript (tanpa framework dan tanpa library tambahan)
- Satu file: `index.html`

## Cara Menjalankan

**Di komputer sendiri:** buka file `index.html` dengan browser (klik dua kali).

**Lewat GitHub Pages:**

1. Buat repository baru di GitHub, misalnya `survei-transportasi`.
2. Upload `index.html` dan `README.md`.
3. Buka **Settings → Pages**, pada *Source* pilih branch `main` dan folder `/ (root)`, lalu **Save**.
4. Tunggu 1-2 menit. Alamat web akan muncul, biasanya berbentuk `https://<username>.github.io/survei-transportasi/`.

## Cara Memakai

1. Isi data responden dan seluruh pernyataan (skala 1 = Sangat Tidak Setuju sampai 5 = Sangat Setuju).
2. Klik **Kirim Jawaban**.
3. Klik **Lihat Hasil** untuk melihat rata-rata per aspek dan per pernyataan.
4. Klik **Unduh CSV** untuk menyimpan data jawaban.

## Mengubah Pernyataan

Daftar pernyataan ada di bagian atas script pada `index.html`, di dalam variabel `ASPEK`. Ubah teks pada `item` untuk menyesuaikan dengan kuesioner.

## Catatan

Jawaban disimpan di browser masing-masing pengguna (localStorage), sehingga data dari perangkat berbeda tidak otomatis terkumpul di satu tempat. Untuk mengumpulkan data dari banyak responden, gunakan Google Form sebagai penampung utama dan aplikasi ini sebagai demonstrasi hasil pengembangan.
