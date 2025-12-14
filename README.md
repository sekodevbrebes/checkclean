# 🧹 CheckClean

**CheckClean** adalah aplikasi **Sistem Checklist dan Monitoring Kebersihan** yang digunakan untuk mengontrol, memantau, dan mengevaluasi pelaksanaan kebersihan gedung **Kantor Pemerintahan Terpadu (KPT)** yang terdiri dari beberapa instansi, bagian/bidang, serta lantai.

Aplikasi ini dirancang untuk membantu **petugas kebersihan, koordinator, dan pengelola gedung** agar proses kebersihan terdokumentasi dengan baik, transparan, dan mudah diawasi.

---

## 📌 Tujuan Aplikasi

* Menyediakan checklist kebersihan harian berbasis digital
* Mengontrol pekerjaan kebersihan per instansi, lantai, dan area
* Mempermudah monitoring dan evaluasi oleh koordinator
* Mengurangi penggunaan checklist manual (kertas)
* Mendukung kebersihan dan kenyamanan lingkungan kerja

---

## 🏢 Cakupan Area

CheckClean dirancang untuk gedung bertingkat dengan karakteristik:

* Gedung hingga **6 lantai**
* Beberapa **instansi/OPD** dalam satu gedung
* Setiap instansi terdiri dari beberapa **bagian/bidang**
* Area kerja, ruang rapat, toilet, lorong, lift, dan tangga

---

## 👥 Level User & Hak Akses

### 1️⃣ Admin Sistem

* Mengelola data user
* Mengelola data instansi, lantai, area, dan item checklist
* Melihat dan mengunduh laporan (rekap harian/bulanan)
* Monitoring seluruh area gedung

### 2️⃣ Koordinator Kebersihan

* Melihat checklist petugas
* Validasi dan verifikasi checklist harian
* Memberikan catatan dan evaluasi
* Monitoring per lantai atau instansi

### 3️⃣ Petugas Kebersihan

* Login dan mengisi checklist harian
* Memilih instansi, lantai, dan area tugas
* Mengisi checklist berdasarkan waktu kerja (pagi/siang/sore)
* Menambahkan catatan jika terdapat kendala

### 4️⃣ Viewer / Pimpinan (Opsional)

* Melihat laporan dan dashboard
* Tidak memiliki hak edit data

---

## ✅ Fitur Utama

* Checklist kebersihan harian
* Pembagian area berdasarkan instansi & lantai
* Checklist berdasarkan waktu (Pagi / Siang / Sore)
* Catatan pekerjaan dan kendala
* Validasi oleh koordinator
* Rekap laporan kebersihan
* Tampilan responsif (desktop & mobile)

---

## 🧾 Contoh Item Checklist

* Menyapu dan mengepel lantai
* Membersihkan meja dan kursi
* Membersihkan toilet
* Mengosongkan tempat sampah
* Membersihkan kaca dan pintu
* Membersihkan area lift dan tangga

---

## 🛠️ Teknologi yang Digunakan

* **Backend Framework**: Laravel 12
* **Frontend**: Livewire, Tailwind CSS
* **Database**: MySQL
* **Template Engine**: Blade
* **Authentication**: Laravel Auth (Session-based)
* **Deployment**: Shared Hosting / VPS / Cloud Server

---

## 🚀 Instalasi & Menjalankan Aplikasi

### 1. Clone Repository

```bash
git clone https://github.com/username/checkclean.git
cd checkclean
```

### 2. Jalankan (Frontend Static)

Cukup buka file berikut di browser:

```bash
index.html
```

> Untuk versi backend, silakan sesuaikan dengan framework yang digunakan.

---

## 📁 Struktur Folder (Contoh)

```
checkclean/
├── index.html
├── assets/
│   ├── css/
│   └── img/
├── components/
├── docs/
└── README.md
```

---

## 📈 Pengembangan Lanjutan (Roadmap)

* Autentikasi login multi-level
* Dashboard grafik kebersihan
* Export laporan PDF & Excel
* QR Code per ruangan
* Integrasi mobile (PWA)
* Notifikasi pekerjaan belum selesai

---

## 🤝 Kontribusi

Kontribusi sangat terbuka untuk pengembangan lebih lanjut.

Langkah kontribusi:

1. Fork repository
2. Buat branch baru
3. Commit perubahan
4. Ajukan Pull Request

---

## 📄 Lisensi

Aplikasi ini dikembangkan untuk kebutuhan internal pemerintahan.

Lisensi dapat disesuaikan sesuai kebijakan instansi.

---

## ✨ Penutup

**CheckClean** diharapkan menjadi solusi digital untuk meningkatkan kualitas kebersihan, akuntabilitas kerja, dan kenyamanan lingkungan kerja di gedung pemerintahan.

---

📌 *Dikembangkan untuk mendukung pengelolaan kebersihan gedung Kantor Pemerintahan Terpadu (KPT).*
