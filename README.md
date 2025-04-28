# Multiprocessor and Symmetric Multiprocessor (SMP) Architecture Diagram

## 📋 Deskripsi

Proyek ini berisi diagram arsitektur untuk:
- *Multiple Processor Architecture*:  
  Setiap prosesor memiliki memori sendiri-sendiri tanpa berbagi, beroperasi secara independen.
- *Symmetric Multiprocessor Architecture (SMP)*:  
  Semua prosesor terhubung ke sebuah memori bersama menggunakan bus bersama, dengan akses yang simetris.

Diagram dibuat dengan desain modern:
- Blok berwarna berbeda.
- Efek shadow.
- Ikon CPU dan RAM untuk memperjelas fungsi masing-masing blok.
- Garis koneksi yang artistik dan berwarna.

## 📂 File

- multiprocessor_smp_diagram.xml:  
  File XML yang dapat diimpor ke [draw.io](https://app.diagrams.net/) untuk melihat atau mengedit diagram.

## 🛠 Cara Menggunakan

1. Buka [draw.io](https://app.diagrams.net/).
2. Pilih *Device* untuk penyimpanan lokal.
3. Klik *File > Import From > Device*.
4. Pilih file multiprocessor_smp_diagram.xml.
5. Diagram akan otomatis muncul dan siap untuk diedit atau dipresentasikan.

## 🖼 Preview

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

## 📋 Deskripsi Proyek

Proyek ini bertujuan untuk memberikan pemahaman yang lebih mendalam tentang dua jenis arsitektur multiprosesor yang sangat penting dalam dunia komputasi modern: **Multiple Processor Architecture** dan **Symmetric Multiprocessor Architecture (SMP)**. Kedua arsitektur ini mempengaruhi cara kita merancang sistem komputer dan aplikasi yang memanfaatkan kemampuan paralelisme untuk meningkatkan kinerja.

Dalam proyek ini, kami menyediakan diagram visual untuk kedua arsitektur yang akan membantu Anda memahami perbedaan mendasar antara keduanya, serta keunggulan dan keterbatasan masing-masing. Diagram ini dapat digunakan dalam berbagai konteks, seperti untuk keperluan edukasi, dokumentasi teknis, atau dalam presentasi di konferensi teknologi.

### **Multiple Processor Architecture**

Pada arsitektur *Multiple Processor*, setiap prosesor memiliki memori lokalnya sendiri (RAM) yang terisolasi dan tidak ada komunikasi langsung antara prosesor. Ini berarti bahwa masing-masing prosesor bekerja secara independen dengan memori yang dimilikinya tanpa ada mekanisme untuk berbagi data antar prosesor. Arsitektur ini cocok digunakan pada sistem yang tidak memerlukan koordinasi intensif antara prosesor atau aplikasi yang dapat diparalelkan dengan independen.

Beberapa ciri khas dari arsitektur *Multiple Processor*:
- Setiap prosesor memiliki memori lokal yang tidak dapat diakses oleh prosesor lain.
- Tidak ada komunikasi langsung antar prosesor.
- Skalabilitas terbatas karena pengelolaan memori yang terpisah.
- Efisien untuk aplikasi yang dapat berjalan secara terpisah atau membutuhkan komputasi independen.

### **Symmetric Multiprocessor Architecture (SMP)**

Di sisi lain, *Symmetric Multiprocessor (SMP)* adalah arsitektur di mana beberapa prosesor berbagi satu memori utama yang sama. Dalam sistem SMP, setiap prosesor memiliki akses yang setara (simetris) terhadap memori bersama, yang memungkinkan komunikasi dan berbagi data yang lebih efisien antar prosesor. Arsitektur ini sering digunakan pada sistem yang membutuhkan kapasitas komputasi tinggi dan mampu menangani proses yang saling bergantung.

Fitur utama dari arsitektur SMP:
- Semua prosesor terhubung ke satu memori bersama yang dapat diakses secara simultan.
- Memori bersama memungkinkan komunikasi yang lebih mudah dan berbagi data antar prosesor.
- Setiap prosesor memiliki akses yang setara (simetris) terhadap memori dan sumber daya lainnya.
- Scalability yang lebih baik, terutama dalam aplikasi komputasi intensif atau data paralel.

### 🎨 **Desain Diagram**

Diagram ini dirancang dengan gaya visual yang modern dan mudah dimengerti, dengan menggunakan warna dan ikon yang jelas untuk menggambarkan komponen-komponen penting dalam arsitektur komputer:
- **Blok Berwarna Berbeda**: Setiap jenis komponen, seperti prosesor (CPU) dan memori (RAM), diwakili oleh warna yang berbeda untuk memudahkan identifikasi.
- **Efek Shadow**: Efek bayangan memberikan dimensi tambahan pada diagram, menciptakan tampilan tiga dimensi yang lebih menarik.
- **Ikon CPU dan RAM**: Ikon grafis yang menggambarkan fungsi dari prosesor (CPU) dan memori (RAM) memudahkan pemahaman pengguna mengenai peran masing-masing komponen dalam arsitektur.
- **Garis Koneksi Artistik**: Menunjukkan hubungan antar elemen dengan garis berwarna dan artistik, memberikan visualisasi yang jelas namun tetap menarik.

### 📂 **File yang Termasuk**

- **`multiprocessor_smp_diagram.xml`**  
  Ini adalah file diagram dalam format XML yang dapat diimpor ke dalam aplikasi *draw.io* untuk melihat, mengedit, atau memodifikasi diagram arsitektur. File ini berisi semua elemen visual yang diperlukan untuk menggambarkan kedua arsitektur dengan jelas dan terstruktur.

### 🛠 **Cara Menggunakan**

Untuk mengimpor dan mengedit diagram, Anda dapat menggunakan aplikasi berbasis web *draw.io*, yang merupakan alat diagram yang mudah digunakan dan sangat populer. Ikuti langkah-langkah berikut untuk melihat dan mengedit diagram:

1. Kunjungi situs web [draw.io](https://app.diagrams.net/).
2. Pilih *Device* untuk menyimpan diagram secara lokal di perangkat Anda.
3. Klik pada menu *File > Import From > Device* untuk mengimpor file dari perangkat Anda.
4. Pilih file `multiprocessor_smp_diagram.xml` yang telah diunduh.
5. Diagram akan muncul secara otomatis di antarmuka *draw.io*, siap untuk diubah atau digunakan dalam presentasi.

### **Penjelasan Arsitektur dalam Diagram**

1. **Multiple Processor Architecture**:
   - Setiap prosesor diwakili oleh sebuah blok CPU yang memiliki memori lokal (RAM) yang terhubung langsung ke prosesor tersebut.
   - Tidak ada saling berbagi memori antar prosesor. Masing-masing prosesor beroperasi secara independen, dan komunikasi antar prosesor tidak terjadi melalui memori bersama.

2. **Symmetric Multiprocessor Architecture (SMP)**:
   - Semua prosesor diwakili oleh beberapa blok CPU yang terhubung ke satu memori bersama. Garis koneksi antara prosesor dan memori menunjukkan akses bersama ini.
   - Setiap prosesor memiliki akses setara (simetris) terhadap memori, memungkinkan koordinasi dan berbagi data antar prosesor secara efisien.

### ✨ **Credits**

Diagram dan desain ini dibuat oleh [M. RINO PRAMUJI], yang berfokus pada visualisasi arsitektur komputer dan konsep-konsep teknologi informasi. Kami berterima kasih atas kontribusinya dalam membuat diagram yang jelas dan mudah dipahami untuk konsep-konsep yang sangat penting dalam sistem komputasi multiprosesor.

---

> 🔥 **Catatan**: Anda bebas untuk mengedit atau menambahkan elemen lain pada diagram sesuai kebutuhan presentasi Anda. Diagram ini dapat disesuaikan lebih lanjut dengan menambah label, mengganti warna, atau mengubah tampilan untuk lebih sesuai dengan audiens atau kebutuhan spesifik Anda.

---

### 💡 **Mengapa Ini Penting?**

Memahami arsitektur multiprosesor adalah hal yang penting bagi para insinyur perangkat keras dan perangkat lunak, terutama dalam konteks pengembangan aplikasi yang memanfaatkan pemrosesan paralel. Dengan memahami perbedaan antara arsitektur *Multiple Processor* dan *Symmetric Multiprocessor* (SMP), para profesional dapat merancang sistem yang lebih efisien, dengan mempertimbangkan faktor-faktor seperti skalabilitas, kebutuhan sumber daya, dan komunikasi antar prosesor.

---

Dengan penjelasan ini, diharapkan pengguna dapat lebih mudah memahami diagram yang disediakan dan cara menggunakannya untuk memperkaya pemahaman mereka tentang dua arsitektur multiprosesor yang fundamental.

