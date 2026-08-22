# Snake Android — Build APK via GitHub

## 1. Buat repository GitHub
Buat repository baru, misalnya `snake-android`.

## 2. Upload seluruh isi project ini
Upload folder dan file project, termasuk:
- `app/`
- `.github/workflows/build-apk.yml`
- `build.gradle`
- `settings.gradle`

## 3. Jalankan build
Setelah upload, buka tab **Actions** di repository.
Pilih workflow **Build Snake APK**, lalu tekan **Run workflow** jika belum otomatis berjalan.

## 4. Ambil APK
Setelah proses selesai:
Actions → pilih workflow yang selesai → bagian **Artifacts** → `Snake-debug-APK`.

File di dalam artifact tersebut adalah:
`app-debug.apk`

## Catatan
APK yang dihasilkan adalah debug APK untuk pengujian. Untuk rilis Play Store, APK perlu signing/release configuration.
