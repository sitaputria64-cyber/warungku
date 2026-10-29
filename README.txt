WARUNGKU ANDROID v1.1

Isi:
- Login admin (awal admin / 1234)
- Kasir + keranjang + pembayaran tunai + kembalian
- Struk transaksi dengan tanggal, waktu, nomor transaksi, tunai, kembalian
- Produk & stok
- Laporan omzet, modal, pengeluaran, laba bersih
- Riwayat transaksi
- Notifikasi stok menipis/habis
- Pengaturan identitas warung dan akun admin
- Backup/restore JSON
- Data tersimpan lokal di perangkat (localStorage)

CARA MEMAKAI DENGAN SKETCHWARE PRO
1. Buat project baru, nama WarungKu, package misalnya com.warungku.kasir.
2. Gunakan 1 Activity utama.
3. Tambahkan WebView memenuhi layar.
4. Masukkan file app/src/main/assets/index.html sebagai asset index.html.
5. Aktifkan JavaScript dan DOM storage pada WebView.
6. Load: file:///android_asset/index.html
7. Run untuk build/install. Dokumentasi resmi Sketchware Pro menjelaskan proses Run/build dan install APK.

CATATAN
Paket ini adalah source project, bukan APK siap install. Build APK membutuhkan toolchain Android/Sketchware Pro.
