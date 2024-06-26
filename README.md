# TUGAS ANALISIS SISTEM INFORMASI DAYCARE BERBASIS OBJEK 

## Latar Belakang

Daycare adalah layanan yang menyediakan perawatan dan pengawasan bagi anak-anak usia bayi hingga pra sekolah saat orang tua atau wali mereka bekerja ataupun memiliki keperluan lain.  Layanan utama daycare secara garis besar meliputi penyediaan kebutuhan anak makan, minum,  tidur siang, dan mengganti popok. Menawarkan aktivitas bermain dan belajar yang sesuai dengan  usia anak untuk mendukung perkembangan kognitif, fisik, sosial, dan emosional. Memastikan  lingkungan yang aman dan terlindungi bagi anak-anak. Menyediakan makanan dan minuman yang  sehat dan bergizi. Menjaga kebersihan lingkungan dan menerapkan praktik kesehatan yang baik  untuk mencegah penyebaran penyakit. 

## Aktor Yang Terlibat

1. Admin : Mengelola data pengguna, jadwal, kehadiran, dan laporan.
2. Orang Tua/Wali : Mendaftarkan anak, melihat informasi anak, melakukan pembayaran, dan berkomunikasi dengan staf.
3. Staf : Mengisi data kehadiran anak, mencatat aktivitas anak, dan berkomunikasi dengan orang tua.

## Use Case

![use case](https://github.com/NurAdamMahfudh/APBO-Analisis-Sistem/assets/167945633/5d06a4db-16d0-4941-9956-300a7fa06aaf)

1. Pendaftaran Anak : Orang tua/wali mendaftarkan anak, mengisi data diri anak dan orang tua, dan memilih paket layanan.
2. Pengelolaan Data Pengguna : Admin menambahkan, mengedit, dan menghapus data anak, orang tua/wali, dan staf.
3. Penjadwalan : Admin membuat jadwal kegiatan, mengatur waktu masuk dan keluar anak, dan menugaskan staf.
4. Pencatatan Kehadiran : Staf mencatat kehadiran anak, menandai waktu masuk dan keluar, dan alasan ketidakhadiran.
5. Pencatatan Aktivitas Anak : Staf mencatat aktivitas anak, seperti bermain, belajar, makan, dan tidur.
6. Laporan : Admin menghasilkan laporan kehadiran anak, aktivitas anak, dan keuangan.

## Class Diagram 

![Class Diagram Daycare](https://github.com/NurAdamMahfudh/APBO-Analisis-Sistem/assets/167945633/7d5102c4-27bd-4561-be25-f73fab994d7e)

## ERD (Entity Relationship Diagram)

![ERD](https://github.com/NurAdamMahfudh/APBO-Analisis-Sistem/assets/167945633/10f9e0c3-2051-4168-bace-7bdb64e5937e)

### Relasi :

1. Anak (1) --> OrangTua (1):
   * Satu anak memiliki satu orang tua.
   * Satu orang tua dapat memiliki banyak anak.
2. Jadwal (1) --> Staf (1):
   * Satu jadwal ditugaskan kepada satu staf.
   * Satu staf dapat menangani banyak jadwal.
3. Anak () --> Kehadiran ():
   * Satu anak dapat memiliki banyak catatan kehadiran dalam berbagai jadwal.
   * Satu jadwal dapat memiliki catatan kehadiran untuk banyak anak.
