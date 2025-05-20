# DasarAlgoritmaDanPemrograman-BisDig
Muhammad Rizqy Ramadhan (24110310096) 2B Bisnis Digital

Manfaat Penggunaan Fungsi Fungsi dalam pemrograman memberikan banyak manfaat, di antaranya:

Modularitas: Memecah program menjadi bagian-bagian kecil yang lebih mudah dipahami dan dikelola.
Reusabilitas: Kode yang sama dapat digunakan berulang kali tanpa perlu menulis ulang.
Abstraksi: Menyembunyikan detail implementasi, sehingga pengguna fungsi hanya perlu tahu input dan output.
Pemeliharaan: Mempermudah proses debugging dan pembaruan kode karena perubahan hanya perlu dilakukan di satu tempat.
Keterbacaan: Meningkatkan keterbacaan kode dengan memberikan nama yang deskriptif untuk operasi tertentu.
Scope Variabel: Membantu mengelola ruang lingkup variabel, mencegah konflik nama variabel.
Pengujian: Memudahkan pengujian program karena fungsi dapat diuji secara terpisah. Cara Kerja Rekursi dalam Menghitung Faktorial Rekursi adalah teknik di mana suatu fungsi memanggil dirinya sendiri untuk menyelesaikan masalah. Untuk bekerja dengan benar, fungsi rekursif harus memiliki:
Kasus Basis: Kondisi yang menghentikan pemanggilan rekursif (mencegah infinite loop).
Kasus Rekursif: Kondisi dimana fungsi memanggil dirinya sendiri dengan parameter yang lebih sederhana. Dalam kasus faktorial:
Definisi matematika: n! = n × (n-1) × (n-2) × ... × 2 × 1
Definisi rekursif: n! = n × (n-1)!
Kasus basis: 0! = 1! =
Penggunaan Perulangan dan Array Perulangan Dalam program ini, perulangan digunakan untuk:

Mengumpulkan input nilai dari 5 siswa secara berurutan menggunakan perulangan for
Memungkinkan input ulang jika terjadi kesalahan input (error handling) Array (List) Array/list dalam Python digunakan untuk:
Menyimpan nilai kelima siswa dalam satu variabel (nilai = [])
Memudahkan pencarian nilai tertinggi dengan fungsi max()
Menentukan posisi/indeks siswa dengan nilai tertinggi menggunakan fungsi index() Struktur Kontrol Percabangan untuk Logika Diskon Struktur kontrol percabangan adalah komponen fundamental dalam pemrograman yang memungkinkan program untuk menjalankan blok kode tertentu berdasarkan kondisi yang dievaluasi. Penggunaan Percabangan dalam Kasus Diskon E-Commerce:
Kondisi yang Dievaluasi: o Apakah total belanja pelanggan > Rp500.000?
Jalur Eksekusi: o Jika kondisi bernilai TRUE (total belanja > Rp500.000):  Berikan diskon 10% dari total belanja  Tampilkan pesan selamat mendapatkan diskon o Jika kondisi bernilai FALSE (total belanja ≤ Rp500.000):  Tidak berikan diskon (diskon = 0)  Tampilkan pesan informasi syarat mendapatkan diskon
Perhitungan Akhir: o Total bayar = Total belanja - Nilai diskon
Langkah-langkah Algoritma untuk Sistem Kasir Toko Algoritma adalah urutan langkah-langkah yang terstruktur untuk menyelesaikan suatu masalah. Untuk sistem kasir sederhana yang menghitung total harga 3 barang, berikut langkah-langkahnya:

Tahap Persiapan • Mulai program • Inisialisasi variabel total_harga = 0 untuk menyimpan total harga pembelian
Tahap Input Data • Untuk setiap barang dari 3 barang: o Minta pengguna memasukkan harga barang o Validasi input:  Pastikan input berupa angka (bukan huruf atau karakter khusus)  Pastikan nilai tidak negatif (harga tidak mungkin negatif) o Jika validasi gagal, minta input ulang
Tahap Proses • Untuk setiap harga barang yang diinput: o Tambahkan ke variabel total_harga
Tahap Output • Tampilkan total harga pembelian dalam format yang sesuai • Selesai
Peran Tipe Data dalam Perhitungan Nilai Rata-Rata Tipe data adalah klasifikasi nilai yang menentukan jenis operasi yang dapat dilakukan dan penyimpanan memori yang dibutuhkan. Dalam program ini, beberapa tipe data yang berperan penting:

Float (Bilangan Pecahan) • Penggunaan: Menyimpan nilai mata pelajaran dan hasil perhitungan rata-rata • Peran: Memungkinkan presisi dalam perhitungan karena nilai ujian bisa berupa bilangan desimal • Contoh: nilai = float(input("Nilai Matematika: ")) dan rata_rata = total_nilai / jumlah_mata_pelajaran
List (Daftar) • Penggunaan: Menyimpan kumpulan nilai dari 3 mata pelajaran • Peran: Memudahkan penyimpanan dan pengolahan sekumpulan nilai yang sejenis • Contoh: nilai_mata_pelajaran = [] untuk menyimpan nilai-nilai mata pelajaran
String (Teks) • Penggunaan: Menyimpan nama mata pelajaran dan status kelulusan • Peran: Menyimpan dan menampilkan informasi teks • Contoh: status = "LULUS" atau status = "TIDAK LULUS"
Boolean (Nilai Logika) • Penggunaan: Hasil evaluasi kondisi dalam pernyataan if • Peran: Menentukan alur eksekusi program berdasarkan kondisi • Contoh: if rata_rata >= 75: menghasilkan nilai True atau False
