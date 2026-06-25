FITUR QR ABSEN + DETEKSI LOKASI

Fitur baru:
- Admin bisa membuat sesi QR absen.
- Admin mengisi latitude, longitude sekolah, radius, dan batas waktu.
- Admin bisa klik "Pakai Lokasi Sekarang" untuk mengisi titik sekolah.
- QR ditampilkan otomatis.
- Siswa bisa scan QR memakai kamera jika browser mendukung BarcodeDetector.
- Jika kamera/scan tidak support, siswa bisa tempel kode manual.
- Web minta izin lokasi siswa.
- Sistem hitung jarak siswa dari titik sekolah.
- Jika di luar radius, absen ditolak.
- Jika di dalam radius, status absen menjadi Hadir.
- Sakit dan izin tetap lewat menu Pengajuan, bukan QR.

Catatan:
- Di Chrome Android, scanner QR biasanya bisa jalan.
- Kalau scanner tidak support, pakai kode manual dari QR.
- Untuk fitur baru ini, pasang juga firestore.rules terbaru jika file rules tersedia.
