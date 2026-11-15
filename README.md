# 💳 KuroFin — Sistem Informasi Manajemen Keuangan Pribadi

**KuroFin** adalah proyek rekayasa perangkat lunak (RPL) untuk perancangan dan pengembangan aplikasi manajemen keuangan pribadi (*personal financial tracker*). Aplikasi ini dirancang untuk membantu pengguna mencatat transaksi pemasukan dan pengeluaran, mengelompokkan kategori keuangan, mengatur batas anggaran bulanan (*budgeting*), memvisualisasikan laporan keuangan dalam bentuk grafik, serta mengelola data profil pengguna.

---

## 📌 Apa Saja yang Baru di Repositori Ini?

Repositori ini telah diperbarui dengan kumpulan dokumen perancangan sistem lengkap pada direktori `FINAL/`, yang mencakup:

### 1. 📄 Dokumen Spesifikasi Kebutuhan Perangkat Lunak (SRS)
* **`FINAL/SRS/KuroFin_SRS.pdf`**: Dokumen formal *Software Requirements Specification* yang mendefinisikan kebutuhan fungsional, non-fungsional, serta batasan sistem KuroFin.

---

### 2. 📐 Diagram Pemodelan Sistem (UML Diagrams)
Seluruh diagram pemodelan perangkat lunak telah dirancang dan diunggah untuk menggambarkan arsitektur serta alur kerja sistem:

* **Use Case Diagram (v1.0)** (`FINAL/UseCase/USECASE DIAGRAM KUROFIN 1.0.pdf`):
  * Pemetaan interaksi aktor pengguna dengan fungsionalitas utama aplikasi (Pencatatan Transaksi, Filter Kategori, Pengaturan Batas Anggaran, Pembuatan Laporan, dan Pengaturan Profil).
* **Activity Diagram** (`FINAL/activity diagram/ACTIVITY DIAGRAM KUROFIN.pdf`):
  * Alur proses kerja sistem dari awal hingga akhir pada setiap skenario fitur utama.
* **Sequence Diagram** (`FINAL/sequence diagram/sequence diagram kuro fin.pdf`):
  * Alur interaksi dan pertukaran pesan antar-objek/komponen sistem dalam rentang waktu eksekusi.
* **State Machine Diagram** (`FINAL/state machine/STATE MACHINE KUROFIN.jpeg`):
  * Transisi status (*state changes*) objek dalam aplikasi (seperti status transaksi dan status peringatan anggaran).
* **Class Diagram** (`FINAL/Class Diagram/Class Diargram.jpeg`):
  * Struktur kelas, atribut, metode, relasi, serta kardinalitas data dalam sistem berorientasi objek KuroFin.
* **Object Diagram** (`FINAL/Object Diagram/OBJECT DIAGRAM KUROFIN.drawio.png`):
  * Contoh instansiasi objek dan hubungannya pada satu waktu operasional (*runtime snapshot*).
* **Deployment Diagram** (`FINAL/Deployment diagram/Deployment Diagram Kurofin.drawio (1).png`):
  * Arsitektur fisik perangkat lunak, komponen runtime, dan topologi infrastruktur hosting/database sistem.

---

### 3. 🎨 Desain Antarmuka & Prototipe Interaktif (UI/UX)
Tersedia tautan langsung ke desain Figma resmi yang ada di folder `FINAL/uiux/`:

* **Desain UI/UX (Figma Workfile):**
  👉 [Buka Desain Figma KuroFin](https://www.figma.com/design/VotZj3LEmC8KfWs0bbDrqz/ui-ux-design-rpl-10?node-id=49-1991)
* **Prototipe Interaktif (Figma Prototype):**
  👉 [Uji Coba Prototipe KuroFin](https://www.figma.com/proto/VotZj3LEmC8KfWs0bbDrqz/ui-ux-design-rpl-10?node-id=62-2705&p=f&m=draw&scaling=min-zoom&content-scaling=fixed&page-id=49%3A1991)

---

## 🗂 Struktur Direktori Repositori

```text
Project-RPL/
└── FINAL/
    ├── SRS/
    │   └── KuroFin_SRS.pdf
    ├── UseCase/
    │   └── USECASE DIAGRAM KUROFIN 1.0.pdf
    ├── activity diagram/
    │   └── ACTIVITY DIAGRAM KUROFIN.pdf
    ├── sequence diagram/
    │   └── sequence diagram kuro fin.pdf
    ├── state machine/
    │   └── STATE MACHINE KUROFIN.jpeg
    ├── Class Diagram/
    │   └── Class Diargram.jpeg
    ├── Object Diagram/
    │   └── OBJECT DIAGRAM KUROFIN.drawio.png
    ├── Deployment diagram/
    │   └── Deployment Diagram Kurofin.drawio (1).png
    └── uiux/
        ├── figma            # Tautan kanvas kerja UI/UX di Figma
        └── figma prototype  # Tautan simulator prototipe interaktif
```

---

## 🚀 Fitur Utama KuroFin

1. **Dashboard & Ringkasan Saldo**: Memberikan informasi total saldo, total pemasukan, dan total pengeluaran secara *real-time*.
2. **Pencatatan Transaksi**: Fitur input, edit, filter, serta riwayat transaksi pemasukan dan pengeluaran.
3. **Kategori Fleksibel**: Pengelompokan jenis transaksi (misal: makanan, transportasi, gaji, investasi) agar arus kas lebih teratur.
4. **Batas Anggaran (*Budget Limit*)**: Pengaturan plafon pengeluaran per kategori beserta indikator peringatan saat mendekati batas.
5. **Laporan & Visualisasi Grafik**: Analisis tren keuangan bulanan berbasis grafik batang dan lingkaran untuk mempermudah evaluasi finansial.
6. **Profil & Basis Data Pengguna**: Pengelolaan data akun dan preferensi pengaturan aplikasi.

---

## 👥 Kontributor

Proyek ini dikembangkan sebagai bagian dari tugas mata kuliah **Rekayasa Perangkat Lunak (RPL)**.
