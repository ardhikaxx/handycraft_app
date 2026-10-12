# 🛠️ Aplikasi Keuangan UMKM - Rahmad HandyCraft

[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](./LICENSE)
[![Author](https://img.shields.io/badge/Author-Yanuar%20Ardhika%20Rahmadhani%20Ubaidillah-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ardhikaxx)

Aplikasi mobile **Rahmad HandyCraft** (Flutter + Firebase) adalah aplikasi keuangan UMKM kerajinan: transaksi jual-beli, kas masuk/keluar, data supplier, dan laporan. Terintegrasi Firebase Authentication & Cloud Firestore untuk sinkronisasi multi-perangkat.

---

## ✨ Fitur Utama

### 1. 💳 Transaksi
- Penjualan & pembelian dengan struk sederhana.

### 2. 💰 Kas
- Arus kas harian dengan kategori pemasukan/pengeluaran.

### 3. 🏭 Supplier
- Master supplier + riwayat pasok bahan.

### 4. 🔥 Firebase
- Auth, Firestore realtime, dan backup cloud.

### 5. 📊 Laporan
- Rekap harian/bulanan + grafik.

---

## 👥 Hak Akses Pengguna (Role-Based Access Control)

| Role | Akses & Wewenang |
| :--- | :--- |
| **Pemilik** | Laporan, master, supplier. |
| **Kasir/Karyawan** | Input transaksi & kas. |

> Otorisasi ditegakkan di backend (middleware/Policy) — bukan sekadar menyembunyikan menu.

---

## 🛠️ Tech Stack & Dependensi

* **Mobile**: Flutter 3.x (Dart 3+)
* **Backend**: Firebase / REST API (sinkronisasi cloud)
* **Storage Lokal**: SQLite / SharedPreferences (offline-first)
* **UI**: Material Design 3

---

## ⚙️ Panduan Instalasi & Menjalankan Aplikasi

### 1. Kloning Repositori
```bash
git clone https://github.com/ardhikaxx/handycraft_app
cd handycraft_app
```

### 2. Install Dependensi
```bash
flutter pub get
```

### 3. Jalankan Aplikasi
```bash
flutter run
```
Untuk build release:
```bash
flutter build apk --release
```

---

## 📚 Dokumentasi Sistem

* [⚖️ **LICENSE**](./LICENSE) — Lisensi resmi **Proprietary Software License (All Rights Reserved)**.
* [🛡️ **SECURITY.md**](./SECURITY.md) — Kebijakan keamanan & pelaporan celah (*Responsible Disclosure*).
* [🤝 **CONTRIBUTING.md**](./CONTRIBUTING.md) — Pedoman kontribusi kode & standar.
* [📜 **CODE_OF_CONDUCT.md**](./CODE_OF_CONDUCT.md) — Pedoman perilaku komunitas pengembang.
* [💬 **SUPPORT.md**](./SUPPORT.md) — Kanal bantuan teknis & komunikasi resmi pengembang.
* [📋 **CHANGELOG.md**](./CHANGELOG.md) — Riwayat rilis fitur terstruktur (*Keep a Changelog* & SemVer).
* [📚 **CITATION.md**](./CITATION.md) — Format sitasi karya untuk keperluan akademik.

---

## 💖 Dukungan & Donasi

Jika proyek **Aplikasi Keuangan UMKM - Rahmad HandyCraft** ini bermanfaat bagi Anda dan telah menghemat banyak jam kerja Anda, Anda dapat menunjukkan apresiasi dengan memberikan traktiran kopi (donasi) melalui pemindaian kode QRIS di bawah ini:

<p align="center">
  <img src="./qris.png" alt="QRIS Donasi" width="300"/>
</p>

> Donasi sepenuhnya bersifat sukarela dan tidak mengikat. Aplikasi tetap dapat digunakan secara utuh tanpa donasi.

---

## ⚠️ Ketentuan Penggunaan

Proyek ini dilindungi lisensi **Proprietary Software License (All Rights Reserved)**. Anda **dilarang** menyalin, memodifikasi, mendistribusikan ulang, atau menjual kode ini tanpa izin tertulis dari pemilik hak cipta. Lihat [LICENSE](./LICENSE) untuk detail lengkap.

---

## 👨‍💻 Pengembang & Hak Cipta

Dirancang dan dikembangkan dengan penuh dedikasi oleh:
**[Yanuar Ardhika Rahmadhani Ubaidillah (@ardhikaxx)](https://github.com/ardhikaxx)**
*Lead Software Architect & Maintainer*

> **Copyright (c) 2024 - 2026 Yanuar Ardhika Rahmadhani Ubaidillah (@ardhikaxx). All Rights Reserved.**
