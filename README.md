# Form Login — Kasir Warung

Portal masuk shift & kasir untuk aplikasi **Kasir Warung** dengan tata letak ringkas satu kolom yang adaptif untuk desktop dan layar ponsel (*single-focus layout*, tanpa panel hero bertumpuk).

## Fitur Utama
- **Header Konsisten & Jam WIB**: Logo **Kasir Warung**, indikator status *Siap Luring*, dan jam WIB langsung tetap terlihat di desktop maupun ponsel.
- **Petugas Cepat 1-Klik**: Pilih petugas shift (**Pak Warung**, **Mbak Sri**, **Budi**) untuk mengisi kredensial demo secara otomatis.
- **Dua Mode Masuk**:
  - **Akun & Sandi** (`autocomplete` & autofill standar peramban + tombol tampilkan sandi yang aksesibel).
  - **PIN 6-Digit** (`input` numerik tunggal dengan meter visual 6-strip dan keypad sentuh ringkas).
- **Dialog Bantuan Demo Native**: Informasi akun dan PIN demo tampil lewat elemen `<dialog>` native (tanpa popup `alert()`).
- **Sinkronisasi Shift Lokal**: Menyimpan nama warung & kasir aktif ke `kw_meta_v1` (`localStorage`) sebelum masuk ke **Kasir Warung**.
- **Tema Terang & Gelap Otomatis**: Mengikuti preferensi sistem (`prefers-color-scheme`) serta mendukung mode kontras tinggi (`forced-colors`).
