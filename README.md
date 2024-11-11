# Aplikasi Penghitung Kata

Aplikasi ini dirancang untuk membantu pengguna menghitung jumlah kata dan karakter dalam teks yang mereka masukkan. Aplikasi ini menggunakan GUI sederhana dan beberapa fitur yang memudahkan penggunaan serta analisis teks.

## Fitur

- **Penghitungan Kata dan Karakter:** Setelah teks dimasukkan dan tombol "Hitung" ditekan, aplikasi akan menampilkan jumlah kata dan karakter.
- **Penghitungan Real-time:** Menggunakan `DocumentListener`, aplikasi ini mampu menghitung kata dan karakter secara real-time saat pengguna mengetik.
- **Penghitungan Kalimat dan Paragraf:** Fitur tambahan untuk menghitung jumlah kalimat dan paragraf dalam teks.
- **Pencarian Kata:** Fungsi pencarian untuk menemukan kata tertentu dalam teks.
- **Penyimpanan Hasil:** Opsi untuk menyimpan teks dan hasil perhitungan ke dalam file.

## Komponen GUI

- **JFrame** sebagai window utama aplikasi.
- **JPanel** untuk menampung komponen lain.
- **JLabel** untuk menampilkan teks dan hasil.
- **JTextArea** dalam **JScrollPane** digunakan untuk input teks pengguna.
- **JButton** untuk memicu penghitungan.

## Logika Program

Menggunakan manipulasi string dan ekspresi reguler untuk menganalisis dan menghitung teks yang diinputkan oleh pengguna.

## Event Handling

- **ActionListener** pada tombol "Hitung" untuk menjalankan fungsi penghitungan.
- **DocumentListener** pada JTextArea untuk penghitungan real-time.
