# Aplikasi Transfer Note

Aplikasi desktop untuk **pengarsipan proses produksi cat** di **PT Murni Cahaya Pratama**, dibuat dengan **Java (NetBeans)**.  
Aplikasi menyimpan dan mengelola data **proses pekerjaan/transfer note**, dengan dukungan **SQLite** dan **MS Access (UCanAccess)**.

> **Catatan:** Repo ini menggunakan **data simulasi/sample** untuk keperluan portofolio. Tidak menampilkan data produksi.

---

## ✨ Fitur Utama
- Input & update **Transfer Note** (tanggal, kode material, qty, shift, dsb.)
- Pencarian & filter data
- Ekspor (CSV/Excel) *(opsional, jika ada)*
- Multi database:
  - **SQLite** untuk penggunaan ringan/portabel
  - **MS Access** via **UCanAccess** untuk kompatibilitas lama
- Konfigurasi fleksibel via `config.properties`

---

## 🧱 Teknologi
- **Java 8+**
- **NetBeans** (Ant) atau **Maven** *(rekomendasi)*
- **SQLite JDBC (Xerial)**
- **UCanAccess** (MS Access) + dependensi (HSQLDB, Jackcess, Commons-logging)

---

## 📂 Struktur Proyek
