Soal 1
1.Penamaan path file gambar assets/twilght sparkle.jpg yang mengandung spasi berisiko saat di-deploy ke server web publik karena sistem rawan tidak dapat membaca file gambar yang memiliki spasi di namanya, sehingga nantinya yang muncul adalah alt text, yaitu text yang muncul menggantikan gambar yang tidak dapat terbaca. Untuk nama file yang direkomendasikan seperti contoh assets/twilight-sparkle.jpg, alias menggunakan - untuk menggantikan spasi.

2.Tautan ke GitHub dan Instagram tidak memiliki atribut target="_blank" maupun rel"=noopenernoreferrer", yang berdampak pada navigasi pengguna yang kurang efisien. Kedua atribut ini penting untuk tautan eksternal agar memudahkan navigasi dan mengurangi resiko link tidak dapat dibuka dan menjadi salah alamat link.

Soal 2
1.Konfigurasi @theme pada Tailwind CSS v4 adalah fitur bawaan dari Tailwind CSS v4, yang dapat mengenali jenis warna yang digunakan dengan perintah --color--(warna): (kode hex warna). Saat sudah, kita tinggal memanggil warna yang sudah didefinisikan di awal dan sistem dapat mengenali secara langsung.
2.Warna gelap untuk state hover lebih direkomendasikan karena readibilitynya yang baik, serta kemudahannya dalam kustomisasi apabila ingin adjust warna di perintah hover, daripada opacity yang harus diatur berulang kali yang memakan lebih banyak waktu.

Soal 3
1.Untuk tata letak 3 kartu proyek di tampilan ponsel dan tablet/desktop diatur oleh perintah grid-cols-1 sm:grid-cols 3, dimana jika web dibuka dengan ponsel, ia akan menampilkan 3 kartu secara menurun (grid-cols-1), dan apabila web dibuka dengan ponsel/tablet, ia akan menampilkan 3 kartu secara menyamping (sm:grid-cols-3).
2.Masalah yang muncul ketika section-section di bawahnya tidak memiliki scroll-mt-(angka) adalah saat kita klik untuk navigasinya, tampilannya akan tertutup sebagian oleh header yang berstatus sticky, yang mengurangi readibility web. Solusi dari masalah tersebut adalah di bagian tiap section, di classnya diberikan perintah scroll-mt-* (misal di sini adalah scroll-mt-20), agar saat diklik untuk navigasinya, tampilan header tidak akan menutupi sebagian layar dan mendarat di bagian yang pas untuk dibaca.