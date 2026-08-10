# ProjectStok - Sistem Informasi Manajemen Stok Barang

Aplikasi Android untuk manajemen stok barang berbasis mobile. Aplikasi ini dirancang untuk mempermudah pemantauan arus barang masuk, keluar, serta pengelolaan data master barang di perusahaan atau gudang.

## 🚀 Fitur Utama

- **Master Stok Barang**: Pengelolaan data barang (Tambah, Edit, Hapus) dan pembuatan QR Code untuk identifikasi barang.
- **Mutasi Stok (Transaksi)**: Pencatatan barang masuk dan keluar dengan antarmuka yang intuitif.
- **Kartu Stok**: Pelaporan riwayat transaksi barang berdasarkan periode tanggal yang dapat difilter.
- **Manajemen Pesanan**: Pengelolaan pesanan barang untuk pengguna.
- **Manajemen User**: Pengaturan hak akses pengguna (Admin/User).
- **Scan QR Code**: Integrasi pemindaian QR Code untuk input data barang secara cepat.

## 🛠 Teknologi yang Digunakan

*   **Bahasa**: Kotlin
*   **Arsitektur**: Fragment-based, View Binding
*   **Database**: SQLite (via `DBHelper`)
*   **Library**:
    *   `ZXing` (untuk QR Code)
    *   `RecyclerView` (untuk list tampilan data)
    *   `DatePicker/TimePicker` (untuk pemilihan periode transaksi)

## 📁 Struktur Fragment Utama

Aplikasi ini terdiri dari beberapa modul fragment utama:
1.  `CardStokFragment`: Untuk melihat laporan riwayat stok.
2.  `DataFragment`: Dashboard navigasi fitur berdasarkan role user.
3.  `HomeFragment`: Halaman utama aplikasi.
4.  `MasterStokFragment`: Pengelolaan master data barang dan QR Code.
5.  `MutasiStokFragment`: Pencatatan transaksi mutasi (Masuk/Keluar).
6.  `PesananUserFragment`: Pengelolaan pesanan barang.
7.  `ProfileFragment`: Pengaturan profil pengguna.
8.  `UsersFragment`: Manajemen akun pengguna (Admin).

## 📥 Cara Instalasi

1.  **Clone Repository**:
    ```bash
    git clone [https://github.com/USERNAME/ProjectStok.git](https://github.com/USERNAME/ProjectStok.git)
    ```
2.  **Buka di Android Studio**:
    *   Pilih `File > Open`, lalu arahkan ke folder `ProjectStok`.
3.  **Build**:
    *   Tunggu Gradle melakukan sinkronisasi hingga selesai.
4.  **Run**:
    *   Sambungkan perangkat Android atau gunakan Emulator, lalu tekan tombol `Run` (Shift+F10).

## 🤝 Kontribusi
Jika Anda ingin berkontribusi pada proyek ini, silakan buat *Pull Request* atau *Open Issue* untuk mendiskusikan perubahan yang ingin dilakukan.

---
Dibuat dengan ❤️ untuk kebutuhan manajemen stok yang lebih efisien.
