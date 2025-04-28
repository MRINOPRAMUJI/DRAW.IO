# Multiprocessor and Symmetric Multiprocessor (SMP) Architecture Diagram

## 📋 Deskripsi

Proyek ini berisi diagram arsitektur untuk:
- **Multiple Processor Architecture**:  
  Setiap prosesor memiliki memori sendiri-sendiri tanpa berbagi, beroperasi secara independen.
- **Symmetric Multiprocessor Architecture (SMP)**:  
  Semua prosesor terhubung ke sebuah memori bersama menggunakan bus bersama, dengan akses yang simetris.

Diagram dibuat dengan desain modern:
- Blok berwarna berbeda.
- Efek shadow.
- Ikon CPU dan RAM untuk memperjelas fungsi masing-masing blok.
- Garis koneksi yang artistik dan berwarna.

## 📂 File

- `multiprocessor_smp_diagram.xml`:  
  File XML yang dapat diimpor ke [draw.io](https://app.diagrams.net/) untuk melihat atau mengedit diagram.

## 🛠️ Cara Menggunakan

1. Buka [draw.io](https://app.diagrams.net/).
2. Pilih **Device** untuk penyimpanan lokal.
3. Klik **File > Import From > Device**.
4. Pilih file `multiprocessor_smp_diagram.xml`.
5. Diagram akan otomatis muncul dan siap untuk diedit atau dipresentasikan.

## 🖼️ Preview

Berikut adalah tampilan preview dari diagram:
![ChatGPT Image 28 Apr 2025, 10 25 22](https://github.com/user-attachments/assets/c46e6a01-ced6-49bb-8092-1b2e53467f59)


### Multiple Processor Architecture
- Masing-masing processor (CPU) memiliki memory sendiri (RAM).
- Tidak ada sharing resources.

### Symmetric Multiprocessor Architecture (SMP)
- Processor-Processor berbagi satu bus komunikasi.
- Semua Processor mengakses satu shared memory bersama-sama.

## ✨ Credits
Diagram dan desain dibuat oleh [M. RINO PRAMUJI].

---

> 🔥 Feel free to edit atau menambahkan ornamen lain sesuai kebutuhan presentasi Anda!
>
> # Multiprocessor and Symmetric Multiprocessor (SMP) Architecture Diagram

## 📋 Deskripsi

Proyek ini berisi diagram arsitektur untuk:
- **Multiple Processor Architecture**:  
  Setiap prosesor memiliki memori sendiri-sendiri tanpa berbagi, beroperasi secara independen.
- **Symmetric Multiprocessor Architecture (SMP)**:  
  Semua prosesor terhubung ke sebuah memori bersama menggunakan bus bersama, dengan akses yang simetris.

Diagram dibuat dengan desain modern:
- Blok berwarna berbeda.
- Efek shadow.
- Ikon CPU dan RAM untuk memperjelas fungsi masing-masing blok.
- Garis koneksi yang artistik dan berwarna.

## 📂 File

- `multiprocessor_smp_diagram.xml`:  
  File XML yang dapat diimpor ke [draw.io](https://app.diagrams.net/) untuk melihat atau mengedit diagram.

## 🛠️ Cara Menggunakan

1. Buka [draw.io](https://app.diagrams.net/).
2. Pilih **Device** untuk penyimpanan lokal.
3. Klik **File > Import From > Device**.
4. Pilih file `multiprocessor_smp_diagram.xml`.
5. Diagram akan otomatis muncul dan siap untuk diedit atau dipresentasikan.

## 🖼️ Preview

Berikut adalah tampilan preview dari diagram:
![ChatGPT Image 28 Apr 2025, 10 25 22](https://github.com/user-attachments/assets/c46e6a01-ced6-49bb-8092-1b2e53467f59)

---

# ✨ Penjelasan Arsitektur

## 1. Multiple Processor Architecture

Pada **Multiple Processor Architecture**:
- Setiap prosesor memiliki **memori lokal** masing-masing.
- Tidak ada sharing resource antar prosesor.
- Prosesor bekerja secara independen tanpa tergantung prosesor lain.

**Kelebihan:**
- Tidak terjadi bottleneck memori.
- Efisien untuk tugas yang independen.

**Kekurangan:**
- Komunikasi antar prosesor lebih sulit.
- Tidak ideal untuk aplikasi yang membutuhkan banyak koordinasi.

**Contoh:**  
Cluster komputer, sistem terdistribusi.

---

## 2. Symmetric Multiprocessor Architecture (SMP)

Pada **SMP Architecture**:
- Semua prosesor berbagi **memori utama** yang sama.
- Terhubung menggunakan satu **bus bersama**.
- Akses ke memori bersifat simetris untuk semua prosesor.

**Kelebihan:**
- Memudahkan komunikasi dan sinkronisasi antar prosesor.
- Sangat efektif untuk aplikasi multi-threaded.

**Kekurangan:**
- Bus bisa menjadi bottleneck.
- Perlu mekanisme kontrol akses ke memori.

**Contoh:**  
Server multi-core, workstation high-end.

---

## 📋 Ringkasan Visual

**Multiple Processor:**

