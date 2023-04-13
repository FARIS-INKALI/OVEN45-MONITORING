# OVEN45-MONITORING
## Digitalization of monitoring oven 45C in DEVTECH INKALI

Ini adalah aplikasi web Streamlit yang untuk melacak dan mengelola sampel di oven stabilitas secara realtime. Aplikasi ini terhubung ke dokumen Google Sheets di mana data disimpan, sehingga memudahkan pengguna untuk mengakses dan memperbarui data secara bersamaan. Aplikasi ini memiliki fitur sebagai berikut:

- Menampilkan semua data sampel dari dokumen Google Sheets dalam tabel
- Menambahkan sampel baru ke dokumen Google Sheets menggunakan formulir
- Menghapus sampel dari dokumen Google Sheets menggunakan menu dropdown

### Penggunaan

1. Scan QR Code yang terletak di OVEN stabilitas atau buka aplikasi web di browser Anda dengan menavigasi ke `https://devtech-oven45.streamlit.app/`.

2. Aplikasi akan menampilkan semua data sampel dalam tabel.

3. Untuk menambahkan sampel baru, klik pada pengembang "Tambah sampel baru" dan isi formulir.

4. Untuk menghapus sampel, klik pada pengembang "Keluarkan sampel" dan pilih PIC dan sampel dari menu dropdown.

5. Klik pada tombol "Submit" untuk menghapus sampel dari dokumen Google Sheets.

Catatan: Aplikasi akan secara otomatis memperbarui tabel saat sampel baru ditambahkan atau dihapus.

### Pustaka yang Digunakan
- Streamlit
- Pandas
- Gspread
- Google OAuth2
- Numpy
