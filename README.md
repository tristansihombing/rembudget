# RemBudget — proyek APK Android

Aplikasi pencatatan pengeluaran bertema ungu/pink Rem-inspired. Data tersimpan lokal pada perangkat (localStorage WebView).

## Cara paling mudah membuat APK gratis dari HP (tanpa laptop)
1. Unduh ZIP proyek ini.
2. Masuk ke https://github.com dan buat akun / login.
3. Buat repository baru bernama `RemBudget` (Public atau Private).
4. Upload seluruh isi ZIP ini ke repository (ekstrak ZIP dahulu; folder `.github` juga harus ikut terunggah).
5. Buka tab **Actions** pada repository. Jika diminta, aktifkan Actions.
6. Pilih workflow **Build RemBudget APK**, tekan **Run workflow**.
7. Tunggu sampai proses selesai (tanda centang hijau).
8. Buka hasil workflow, bagian **Artifacts**, unduh `RemBudget-APK`.
9. Ekstrak file ZIP artifact, lalu instal `app-debug.apk` di Android. Izinkan instalasi dari sumber tersebut jika Android meminta.

## Catatan
- APK dibuat otomatis oleh GitHub Actions; tidak perlu Android Studio atau laptop.
- Ekspor CSV bekerja offline. Ekspor Excel `.xlsx` memakai pustaka SheetJS dari CDN sehingga memerlukan internet saat fitur ekspor digunakan.
- Catatan disimpan di penyimpanan aplikasi. Hapus data aplikasi dapat menghapus catatan; ekspor CSV berkala sebagai cadangan.
- APK ini adalah versi debug untuk penggunaan pribadi, bukan rilis Play Store.
