# 🎮 Block Surge: Power-Up Edition

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**Block Surge: Power-Up Edition** adalah game *arcade falling-block puzzle* klasik berbasis web yang dimodifikasi dengan mekanik **Energi** dan **4 Power-Up Taktis**. Dibangun sepenuhnya menggunakan HTML5 Canvas, CSS3, dan Vanilla JavaScript dalam satu file mandiri tanpa dependensi eksternal (*zero-dependency*).

---

## ✨ Fitur Utama

* **⚡ Sistem Energi & 4 Power-Up Aktif:** Kumpulkan energi dari setiap balok yang mendarat dan baris yang dihancurkan untuk memicu kemampuan penghancur kapan saja.
* **👻 Bayangan Jatuh (*Ghost Piece*):** Indikator transparan yang memudahkan penempatan balok secara presisi sebelum melakukan *Hard Drop*.
* **💥 Efek Partikel Dinamis:** Visualisasi ledakan partikel saat baris berhasil dihapus atau terkena efek *power-up*.
* **📈 Tingkat Kesulitan Progresif:** Kecepatan jatuh balok dan perolehan poin meningkat otomatis seiring bertambahnya level.
* **📦 *Single-File Architecture*:** Seluruh kode permainan (HTML, CSS, dan logika JavaScript) dikemas dalam satu file ringan yang langsung berjalan di *browser* modern.

---

## 🕹️ Kontrol Permainan

| Tombol | Aksi | Keterangan |
| :--- | :--- | :--- |
| `Panah Kiri` / `A` | Geser Kiri | Menggerakkan balok satu kolom ke kiri |
| `Panah Kanan` / `D` | Geser Kanan | Menggerakkan balok satu kolom ke kanan |
| `Panah Atas` / `W` | Putar Balok | Memutar posisi balok sebesar $90^\circ$ disertai *wall-kick* otomatis |
| `Panah Bawah` / `S` | *Soft Drop* | Mempercepat jatuhnya balok ($+1$ poin per sel) |
| `Spasi` | *Hard Drop* | Menjatuhkan balok seketika ke dasar ($+2$ poin per sel) |
| `1` / `2` / `3` / `4` | Aktifkan *Power-Up* | Menggunakan *power-up* sesuai nomor tombol (atau klik langsung di panel) |

---

## 🔥 Daftar Power-Up

| Tombol | Nama Power-Up | Biaya Energi | Efek Taktis di Papan |
| :---: | :--- | :---: | :--- |
| **`1`** | 💣 **Kapsul Peledak** | `30 EN` | Mengubah balok aktif saat ini menjadi kapsul bom $1 \times 1$ yang menghancurkan area $5 \times 5$ di sekitarnya saat mendarat. |
| **`2`** | ⚡ **Sapuan Plasma** | `40 EN` | Langsung melenyapkan 2 baris paling bawah di papan permainan dan memberikan bonus poin instan. |
| **`3`** | 🧲 **Gravitasi Runtuh** | `50 EN` | Menarik seluruh balok yang menggantung ke bawah untuk menutup semua celah kosong dan memicu penghapusan baris otomatis. |
| **`4`** | ⏳ **Zona Waktu Lambat** | `25 EN` | Memperlambat kecepatan jatuh balok dan menggandakan seluruh perolehan skor ($2\times$) selama 10 detik. |

---

## 🚀 Cara Menjalankan Game

Karena proyek ini tidak membutuhkan *build tool* atau *server* khusus, Anda dapat menjalankannya dengan sangat mudah:

1. **Clone repositori ini:**
   ```bash
   git clone https://github.com/username-anda/block-surge.git
   ```
2. **Buka file permainan:**
   * Klik dua kali pada file `index.html` (atau `blocksurge.html`) untuk membukanya langsung di *browser* favorit Anda (Chrome, Firefox, Edge, atau Safari).

### 🌐 Hosting Gratis dengan GitHub Pages
Agar teman-teman Anda bisa langsung memainkannya lewat tautan web:
1. Ubah nama file kode game Anda menjadi **`index.html`** sebelum diunggah ke GitHub.
2. Buka menu **Settings** > **Pages** di repositori GitHub Anda.
3. Pada bagian **Build and deployment (Branch)**, pilih branch `main` dan klik **Save**.
4. Tunggu sekitar 1 menit, dan game Anda siap dimainkan secara *online*!

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah **MIT License** — silakan modifikasi, kembangkan, dan bagikan secara bebas.