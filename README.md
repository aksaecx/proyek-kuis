# proyek-kuis
CodePlay Arena - Kuis Interaktif

Deskripsi
CodePlay Arena adalah aplikasi kuis interaktif yang menguji pengetahuan pengguna tentang berbagai topik teknologi. Aplikasi berbasis web ini menampilkan fitur pertanyaan berbatas waktu, perhitungan skor berdasarkan kecepatan menjawab, dan antarmuka yang elegan dan modern. Proyek ini dikembangkan untuk mendemonstrasikan bagaimana AI dapat membantu dalam proses pengembangan perangkat lunak.

Teknologi yang Digunakan

Frontend: HTML5, CSS3, JavaScript

Styling: Gradien CSS, Flexbox, Desain Responsif

Deployment: Netlify (Hosting Situs Statis)

Alat Pengembangan: Visual Studio Code, Git

Fitur Utama

Pertanyaan Berbatas Waktu: Setiap pertanyaan memiliki waktu 30 detik

Skor Dinamis: Poin diberikan berdasarkan kecepatan menjawab

Desain Responsif: Dapat digunakan di desktop maupun perangkat mobile

Pelacakan Progress: Bar progress visual menampilkan penyelesaian kuis

Feedback Instan: Jawaban ditandai hijau (benar) atau merah (salah)

Ringkasan Hasil: Skor akhir dengan pesan personalisasi berdasarkan performa

Demo Langsung
Aplikasi ini telah di-deploy di Netlify dan dapat diakses di:

https://musical-panda-7c5611.netlify.app/

Penjelasan Dukungan AI
IBM Granite AI digunakan dalam beberapa aspek pengembangan:

1. Pembuatan Kode Awal
AI membantu dalam:
Membuat struktur dasar HTML/CSS
Menyusun logika kuis dan fungsi timer di JavaScript
Menulis kode untuk sistem penilaian otomatis

2. Bantuan Desain
AI memberikan:
Rekomendasi palet warna modern dan kombinasi gradien
Saran tata letak yang responsif
Ide untuk efek visual dan transisi

3. Debugging dan Optimasi
AI membantu:
Mengidentifikasi bug dalam event listeners
Menyarankan perbaikan untuk masalah kompatibilitas browser
Mengoptimalkan algoritma penghitungan skor

4. Dokumentasi
AI membantu dalam:
Membuat template README.md yang komprehensif
Menulis komentar kode yang jelas
Merumuskan dokumentasi fitur

Dampak Penggunaan AI:
Percepatan Pengembangan: Waktu pengembangan berkurang hingga 40% berkat bantuan AI
Peningkatan Kualitas: AI membantu mengidentifikasi potensi bug sejak dini
Inspirasi Fitur: Beberapa fitur seperti sistem skor dinamis terinspirasi dari saran AI
Konsistensi Kode: AI membantu menjaga konsistensi gaya penulisan kode

Screenshot

Tampilan awal dengan informasi kuis
<img width="1920" height="1080" alt="Cuplikan layar 2025-08-17 212923" src="https://github.com/user-attachments/assets/c5d3eff6-b8f7-4602-a3fa-92126af057f6" />

Tampilan pertanyaan dengan timer dan pilihan jawaban
<img width="1920" height="1080" alt="Cuplikan layar 2025-08-17 212941" src="https://github.com/user-attachments/assets/8bae3faa-ea26-43b6-95ab-6035bf7917e9" />

<img width="1920" height="1080" alt="Cuplikan layar 2025-08-17 213017" src="https://github.com/user-attachments/assets/2a61d58d-e299-4146-8dcf-203f2f27e4d6" />

Tampilan hasil akhir dengan skor dan feedback
<img width="1920" height="1080" alt="Cuplikan layar 2025-08-17 213030" src="https://github.com/user-attachments/assets/732e1b27-caea-409a-b6e4-3efd43f6f93b" />


Pengembangan Selanjutnya
Sistem autentikasi pengguna untuk menyimpan highscore
Kategori kuis yang lebih beragam
Tingkat kesulitan yang dapat disesuaikan
Efek suara dan animasi tambahan
Sistem leaderboard online
Fitur berbagi hasil ke media sosial

Lisensi
Proyek ini menggunakan lisensi MIT - lihat file LICENSE untuk detail lebih lanjut.

Kontribusi terbuka untuk:

Terjemahan ke bahasa lain

Penambahan pertanyaan baru

Perbaikan antarmuka pengguna

Optimasi performa

FAQ

Q: Apakah kuis ini bisa diakses offline?

A: Ya, setelah di-download atau di-clone, aplikasi bisa berjalan sepenuhnya offline.

Q: Bisakah menambahkan pertanyaan sendiri?

A: Ya, dengan memodifikasi array quizData di file JavaScript.

Q: Bagaimana cara menyesuaikan waktu per pertanyaan?

A: Ubah nilai timeLeft di fungsi loadQuestion() dan startTimer().
