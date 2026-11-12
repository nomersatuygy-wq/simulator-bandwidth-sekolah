# NetSchool — Simulator Bandwidth Sekolah

Aplikasi simulasi bandwidth untuk pembelajaran TJKT. Dibangun dengan HTML5, CSS3, JavaScript ES6, Chart.js, Lucide, dan LocalStorage. Tidak memerlukan framework, backend, atau database.

## Menjalankan
1. Ekstrak folder `simulator-bandwidth-sekolah`.
2. Buka `index.html` di browser (Chrome/Edge/Firefox).
3. Pastikan koneksi internet aktif agar Chart.js, Lucide, dan Google Fonts dari CDN dapat dimuat.
4. Semua data simulasi tersimpan di LocalStorage browser yang digunakan.

## 8 modul
1. Dashboard — ringkasan bandwidth, pengguna, grafik.
2. Pengguna — tambah, aktif/nonaktif, hapus pengguna; validasi alokasi.
3. Alokasi Bandwidth — kapasitas dan total alokasi.
4. Simulasi Trafik — beban, estimasi latensi dan packet loss.
5. QoS — pembagian persentase layanan, total wajib 100%.
6. Perangkat Jaringan — inventaris perangkat dan status.
7. Laporan — ringkasan dan ekspor CSV.
8. Pengaturan — reset data demo.

## Catatan
Aplikasi ini adalah simulator edukasi lokal, bukan alat ukur jaringan nyata. Perubahan data hanya tersimpan di browser/perangkat yang sama.
