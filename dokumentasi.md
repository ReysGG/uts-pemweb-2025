# UTS PEMWEB
### Oleh
## 20230801547 - David boy
---
# PROSES SLR
```bash
https://themewagon.com/themes/logis/
Rumpun Ilmu : software Engineering
Deskripsi : Bikin Aplikasi Web
P (Platform) : Web app export import
I (Invervention) : Teknologi laravel filament dimana ada penjual, pembeli, admin, owner
C (Comparison) = Masih menggunakan manual
O (Outcome) = Aplikasi web yang bisa penjualan form untuk penjual menghasilkan invoice, pembeli menerima invoice, admin dapat mentrack semua penjualan dan menghasil data agar dapat memberitahu owner
S (Suspect) = Aplikasi mempermudah dalam perencanaaan import export

Berikan saya riset question (rq) terkait ide penelitian diatas!
Respon yang di berikan
Dari deskripsi ide penelitian yang Anda berikan, berikut adalah beberapa **Research Question (RQ)** yang dapat dikembangkan. RQ ini dirancang untuk mengarahkan penelitian, menguji asumsi, dan mengukur kesuksesan pengembangan aplikasi web berbasis Laravel Filament untuk bisnis ekspor-impor.

Riset question dibagi menjadi beberapa kategori untuk cakupan yang lebih komprehensif.

---

### **Kategori 1: RQ tentang Kebutuhan dan Permasalahan (Problem Validation)**

RQ ini bertujuan untuk memvalidasi bahwa masalah yang ingin diatasi memang benar-benar ada dan signifikan.

*   **RQ 1.1:** Seberapa besar inefisiensi yang ditimbulkan oleh proses manual (seperti pembuatan invoice, pelacakan penjualan, dan pelaporan) dalam operasional bisnis ekspor-impor skala menengah saat ini?
*   **RQ 1.2:** Tantangan operasional apa saja yang paling sering dihadapi oleh penjual, pembeli, admin, dan owner dalam proses bisnis ekspor-impor yang masih manual?
*   **RQ 1.3:** Seberapa besar kebutuhan para stakeholder (penjual, pembeli, admin, owner) terhadap sebuah sistem terpusat yang dapat mengotomasi pembuatan invoice, pelacakan transaksi, dan generasi laporan?

---

### **Kategori 2: RQ tentang Fungsionalitas dan Penerapan Teknologi (Development & Features)**

RQ ini berfokus pada aspek pengembangan perangkat lunak dan fitur-fitur spesifik yang akan dibangun.

*   **RQ 2.1:** Bagaimana merancang arsitektur peran (role) `penjual`, `pembeli`, `admin`, dan `owner` dalam Laravel Filament untuk memastikan alur kerja dan akses data yang aman dan efisien?
*   **RQ 2.2:** Fitur-fitur otomasi apa saja yang paling kritis (critical features) yang harus diimplementasikan dalam modul `Invoice Generation` untuk penjual dan `Invoice Reception` untuk pembeli?
*   **RQ 2.3:** Bagaimana merancang dashboard `Admin` yang efektif untuk melacak semua penjualan, mengelola data master, dan memantau kinerja operasional?
*   **RQ 2.4:** Parameter dan metrik data apa saja yang paling dibutuhkan oleh `Owner` dalam laporan yang dihasilkan sistem untuk mendukung pengambilan keputusan strategis?

---

### **Kategori 3: RQ tentang Pengukuran Kinerja dan Dampak (Evaluation & Outcome)**

RQ ini untuk mengevaluasi apakah aplikasi yang dibangun telah mencapai tujuannya dan memberikan dampak yang diharapkan.

*   **RQ 3.1:** Seberapa besar peningkatan efisiensi waktu dalam proses `pembuatan dan distribusi invoice` setelah menerapkan aplikasi web ini dibandingkan dengan proses manual?
*   **RQ 3.2:** Seberapa akurat dan cepat sistem dalam `melacak data penjualan` dan `menghasilkan laporan` bagi admin dan owner dibandingkan dengan metode sebelumnya?
*   **RQ 3.3:** Bagaimana tingkat kepuasan pengguna (User Satisfaction) dari masing-masing peran (`penjual`, `pembeli`, `admin`, `owner`) setelah menggunakan aplikasi ini? (Dapat diukur dengan kuesioner seperti System Usability Scale - SUS).
*   **RQ 3.4:** Sejauh mana aplikasi web ini mampu `mempermudah perencanaan` dalam bisnis ekspor-impor, khususnya dalam hal analisis data historis dan prediksi permintaan?

---

### **Saran Pengembangan dan Metodologi Penelitian:**

1.  **Penelitian Awal:** Gunakan RQ dari **Kategori 1** sebagai dasar untuk melakukan wawancara atau menyebarkan kuesioner kepada calon pengguna (perusahaan ekspor-impor) sebelum memulai pengembangan. Ini akan menguatkan latar belakang masalah penelitian Anda.
2.  **Tahap Pengembangan:** RQ dalam **Kategori 2** akan memandu Anda dalam tahap perancangan dan implementasi sistem. Jawabannya akan menjadi spesifikasi fungsional aplikasi.
3.  **Tahap Pengujian dan Evaluasi:** Setelah aplikasi selesai dibangun, gunakan RQ dalam **Kategori 3** untuk melakukan pengujian. Anda dapat membandingkan kinerja sistem lama (manual) dengan sistem baru (aplikasi Anda) atau mengukur persepsi pengguna melalui metode Usability Testing dan kuesioner.

Dengan menyusun Research Question seperti di atas, penelitian Anda akan memiliki arah yang jelas, terstruktur, dan dapat diukur, sehingga kontribusinya dalam bidang Software Engineering (khususnya dalam pengembangan sistem enterprise) akan lebih terlihat.
```

# PROSES RQ
```bash
Kategori 2: RQ tentang Fungsionalitas dan Penerapan Teknologi (Development & Features)
RQ ini berfokus pada aspek pengembangan perangkat lunak dan fitur-fitur spesifik yang akan dibangun.

RQ 2.1: Bagaimana merancang arsitektur peran (role) penjual, pembeli, admin, dan owner dalam Laravel Filament untuk memastikan alur kerja dan akses data yang aman dan efisien?

RQ 2.2: Fitur-fitur otomasi apa saja yang paling kritis (critical features) yang harus diimplementasikan dalam modul Invoice Generation untuk penjual dan Invoice Reception untuk pembeli?

RQ 2.3: Bagaimana merancang dashboard Admin yang efektif untuk melacak semua penjualan, mengelola data master, dan memantau kinerja operasional?

RQ 2.4: Parameter dan metrik data apa saja yang paling dibutuhkan oleh Owner dalam laporan yang dihasilkan sistem untuk mendukung pengambilan keputusan strategis?

dari sini perkirakan JUDUL YANG BAIK DAN MENARIK NYA APA

Respon yang di berikan
Berdasarkan RQ pada Kategori 2 yang berfokus pada aspek **fungsionalitas, desain arsitektur, dan penerapan teknologi**, berikut beberapa rekomendasi judul penelitian yang baik dan menarik.

Judul-judul ini mencerminkan inti dari pengembangan sistem dan terdengar akademis serta profesional.

---

### **Kategori Judul: Fokus pada Arsitektur & Desain Sistem**

Judul ini menekankan pada aspek teknis bagaimana sistem dirancang, khususnya mengenai manajemen peran (RBAC - Role-Based Access Control).

1.  **Perancangan dan Implementasi Sistem Manajemen Ekspor-Impor Berbasis Role-Based Access Control Menggunakan Laravel Filament**
    *   **Alasan:** Langsung menyebutkan teknologi (Laravel Filament), konsep inti (RBAC), dan domain aplikasinya (Ekspor-Impor). Sangat jelas dan teknis.

2.  **Arsitektur Sistem Terpusat untuk Otomasi Proses Bisnis Ekspor-Impor dengan Pendekatan Multi-Role User**
    *   **Alasan:** Fokus pada "arsitektur" dan "sistem terpusat", yang merupakan jawaban langsung dari RQ 2.1 dan RQ 2.3. Judul ini terdengar kuat dan berfokus pada rekayasa perangkat lunak.

---

### **Kategori Judul: Fokus pada Otomasi & Efisiensi**

Judul ini menyoroti nilai tambah utama dari aplikasi, yaitu mengotomasi proses yang sebelumnya manual.

3.  **Pengembangan Aplikasi Web untuk Otomasi Invoice dan Pelacakan Penjualan pada Bisnis Ekspor-Impor**
    *   **Alasan:** Menjawab RQ 2.2 secara langsung. Kata kunci "Otomasi Invoice" dan "Pelacakan Penjualan" sangat spesifik dan menggambarkan outcome yang diinginkan.

4.  **Implementasi Laravel Filament dalam Membangun Sistem Otomasi Workflow dan Reporting untuk Perusahaan Ekspor-Impor**
    *   **Alasan:** Menyoroti teknologi dan dua fungsi utama ("Workflow" untuk alur invoice dan "Reporting" untuk dashboard admin/owner). Judul ini menjanjikan sebuah solusi yang komprehensif.

---

### **Kategori Judul: Fokus pada Dashboard & Analytics**

Judul ini menarik untuk penelitian yang ingin sangat menekankan pada outcome bagi admin dan owner (RQ 2.3 dan RQ 2.4).

5.  **Rancang Bangun Dashboard Analytics Terintegrasi untuk Monitoring dan Pendukung Keputusan dalam Operasional Ekspor-Impor**
    *   **Alasan:** Sangat kuat di bagian "Analytics", "Monitoring", dan "Pendukung Keputusan". Judul ini ideal jika fokus penelitian Anda adalah pada penyediaan informasi strategis bagi pemilik bisnis.

---

### **Rekomendasi UTAMA (Paling Merepresentasikan RQ Kategori 2):**

Dari semua opsi di atas, judul berikut ini yang paling komprehensif dan kuat untuk mencakup keempat RQ Anda:

> **"Perancangan Sistem Manajemen Ekspor-Impor Berbasis Web dengan Laravel Filament: Studi pada Otomasi Invoice, Dashboard Admin, dan Laporan Strategis"**

**Mengapa judul ini sangat efektif:**
*   **"Perancangan Sistem... Berbasis Web dengan Laravel Filament"**: Jelas menyatakan platform dan teknologinya (menjawab konteks umum).
*   **"Otomasi Invoice"**: Langsung menjawab RQ 2.2.
*   **"Dashboard Admin"**: Langsung menjawab RQ 2.3.
*   **"Laporan Strategis"**: Langsung menjawab RQ 2.4 dan menyiratkan peran Owner.
*   Struktur judulnya logis dan mencerminkan urutan kerja dalam pengembangan sistem.

Anda bisa memilih judul yang paling sesuai dengan penekanan yang ingin Anda berikan dalam penelitian atau laporan tugas akhir Anda. Semua opsi di atas sudah baik dan langsung mencerminkan inti dari RQ yang telah dirumuskan.
```

```bash
terlampir file SLR dengan nama SLR.pdf
```

# BRD
```
terlampir file BRD berdasarkan SLR dengan nama file BRD.pdf
```

# IMPLEMENTASI WEBSITE
```
1. cd /root/boilerplate
2. ./start.sh uts-pemweb
3. cd /root/perkuliahan/uts-pemweb
4. cd src
5. code .
6. template website dengan ide saya diambil dari https://themewagon.com/themes/logis/
6. cd resource/views
8. mkdir layouts && mkdir pages && mkdir partials
9. cd layouts
10. touch layout.blade.php
11. cd ..
12. cd pages
13. touch app.blade.php
14. cd ..
15. cd partials
16. touch about.blade.php
17. touch cta.blade.php
18. touch faq.blade.php
19. touch featured-services.blade.php
20. touch features.blade.php
21. touch footer.blade.php
22. touch header.blade.php
23. touch hero.blade.php
24. touch href.blade.php
25. touch pricing.blade.php
26. touch script.blade.php
27. touch services.blade.php
28. touch testimonials.blade.php
29.touch ..
30. cd ../../routes/
