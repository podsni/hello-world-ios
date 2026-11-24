# Hello World untuk iPhone

Repo ini berisi dua cara menjalankan app Hello World.

- Versi web (PWA) bisa langsung dibuka di iPhone lewat Safari, lalu ditambahkan ke Layar Utama.
- Versi Xcode (SwiftUI) bisa dibuka dan dijalankan di Mac tanpa mengubah kode.

## Buka di iPhone (tanpa Xcode)

1. Buka tautan ini di Safari di iPhone: https://hello-world-ios.vercel.app
2. Ketuk tombol Bagikan (kotak dengan panah ke atas).
3. Pilih Tambahkan ke Layar Utama.
4. Ketuk Tambah.

Ikon Hello World akan muncul di Layar Utama. Saat dibuka, app tampil penuh seperti app biasa.

## Jalankan project Xcode

Kamu butuh Mac dengan Xcode (disarankan Xcode 15 atau yang lebih baru). Target iOS minimum adalah 16.0.

1. Unduh repo ini, atau klon dengan `git clone https://github.com/podsni/hello-world-ios.git`.
2. Buka file `ios/HelloWorld.xcodeproj` di Xcode.
3. Pilih simulator iPhone, atau iPhone yang tersambung ke Mac.
4. Tekan tombol Run (segitiga), atau tekan Command-R.

Layar akan menampilkan ikon globe dan tulisan "Hello, World!".

## Isi repo

- `web/` — app web Hello World (PWA) yang di-deploy ke Vercel.
- `ios/` — project Xcode SwiftUI yang siap dibuka.
- `.github/workflows/ios-build.yml` — pemeriksaan build untuk simulator iOS.

## Catatan

Komputer Linux tidak bisa membangun app iOS asli. Karena itu, versi yang bisa langsung dipakai di iPhone adalah tautan web di atas.
