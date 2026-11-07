# Rangkuman Workshop : Building with AI & Managing Change with GitHub

Dokumentasi dan rangkuman pembelajaran dari kegiatan **Workshop Day 1: Building with AI, Managing Change with GitHub**. Repository ini berfungsi sebagai catatan teknis, panduan praktik *version control*, serta portofolio eksperimen pengembangan aplikasi web berbasis *AI-assisted development*.

---

## 👤 Informasi Peserta

* **Nama Lengkap:** Dimas Mukhlas Ibrahim
* **Kelompok:** 07_Crazy_Taxi
* **Program  Studi:** Teknik Multimedi dan Jaringan
* **Instansi:** Politeknik Negeri Jakarta

---

## Deskripsi & Tujuan Repository

### Deskripsi
Repository ini berisi dokumentasi alur belajar (*learning journey*) pada kegiatan workshop *Building with AI, Managing Change with GitHub*. Di dalamnya mencakup rangkuman materi Prompt Engineering, perintah dasar Git/GitHub, mekanisme konfigurasinya, serta implementasi proyek *Student Task Planner* yang dikembangkan menggunakan AI.

### Tujuan & Kegunaan
* **Version Control Management:** Mengaplikasikan alur kerja Git (Working Directory, Staging Area, Repository) dalam proyek perangkat lunak.
* **Dokumentasi Pembelajaran:** Menyediakan repositori rujukan untuk materi *prompt engineering* dan alur kolaborasi GitHub.
* **Praktik Integrasi AI:** Menerapkan formulasi *prompt* terstruktur untuk mempercepat dan meningkatkan kualitas penulisan kode.

---

## Informasi & Dokumentasi Workshop

### 1. Informasi Kegiatan Workshop
* **Judul Workshop:** Building with AI, Managing Change with GitHub
* **Narasumber:** Nugi Farhan (Senior Product Designer)
* **Fokus Utama:** Penggabungan kapabilitas *AI-assisted development* dengan efisiensi *version control* menggunakan Git & GitHub

### 2. Rangkuman Materi Workshop

#### A. Prompt Engineering untuk AI
Prompt Engineering adalah metode merancang instruksi agar model AI menghasilkan jawaban yang presisi, relevan, dan efisien.

Komponen struktur *prompt* yang baik (RTCF):
* **Role:** Menentukan peran spesifik yang diambil AI (misal: *Senior Web Developer*).
* **Task:** Menjelaskan tugas utama yang wajib dikerjakan oleh AI.
* **Context:** Menyediakan latar belakang, batasan, dan spesifikasi proyek secara rinci.
* **Format:** Menentukan bentuk keluaran akhir (struktur kode, langkah instalasi, atau dokumentasi)

Penerapan Prompt Engineering terstruktur mampu meningkatkan kualitas respons AI, mengurangi bias, serta memberikan kontrol yang lebih baik terhadap luaran kode.

#### B. Dasar-Dasar Git & GitHub
* **Git:** *Distributed Version Control System* (DVCS) yang diciptakan Linus Torvalds pada tahun 2005 untuk melacak riwayat perubahan berkas secara lokal.
* **GitHub:** Platform berbasis web tempat menyimpan repositori Git secara *online* dan memfasilitasi kolaborasi antarpengembang.
Komponen alur kerja Git (Git Workflow):
* **Working Directory:** Direktori kerja tempat berkas proyek dibuat dan diubah.
* **Staging Area (Index):** Area persiapan tempat menyeleksi perubahan yang akan dimasukkan ke dalam commit berikutnya.
* **Git Directory (Repository):** Tempat simpanan database metadata dan seluruh riwayat commit dari proyek.
#### C. Perintah Dasar Git & Otentikasi SSH
Perintah penting dalam pengelolaan repositori:
* **Perintah Lokal:** `git init` (inisialisasi repo), `git add .` atau `git add -A` (menambahkan berkas ke staging), `git commit -m "pesan"` (menyimpan snapshot ke repo lokal).
* **Perintah Remote:** `git remote add <nama> <url>` (menghubungkan ke GitHub), `git push origin main` (mengunggah commit ke remote), `git pull origin main` (mengambil & menggabungkan perubahan dari remote).
* **Otentikasi SSH:** Pembuatan kunci keamanan menggunakan algoritma Ed25519 (Curve25519) melalui `ssh-keygen -t ed25519 -C "email"` untuk komunikasi terenkripsi dan aman dengan GitHub.

---

### 3. Poin-Poin Penting & Pengetahuan Baru

* **Konstruksi Prompt Berbasis Context:** Menyajikan *prompt* tanpa konteks menghasilkan output yang umum, sedangkan menyertakan komponen *Role, Task, Context,* dan *Format* menghasilkan kode modular yang siap pakai.
* **Pemisahan Peran Git vs. GitHub:** Memahami secara jelas bahwa Git beroperasi secara lokal di komputer pengembang, sementara GitHub bertindak sebagai platform kolaborasi terpusat di *cloud*.
* **Manajemen Staging Area:** Menyadari pentingnya memeriksa dan memilah berkas sebelum di-commit agar riwayat perubahan tetap rapi dan mudah dilacak.
* **Keamanan Otentikasi SSH Ed25519:** Mempelajari alur pembuatan SSH key, pengkonfigurasian `ssh-agent`, serta pendaftaran kunci publik ke GitHub sebagai alternatif transaksi data yang lebih cepat dan aman dibanding HTTPS.

---

### 4. Pendapat Pribadi tentang Day 1 Workshop

Sesi **Day 1 Proyek Workshop** berjalan sangat interaktif dan memberikan pemahaman praktis yang mendalam. Materi yang dibawakan oleh Mas Nugi Farhan membuka sudut pandang baru tentang bagaimana memanfaatkan AI bukan sekadar alat pembantu pencarian, melainkan mitra pengembang (*development partner*) yang efektif saat dikombinasikan dengan struktur *prompting* yang tepat.

Momen paling menarik bagi saya adalah saat mempraktikkan alur kerja pengembangan *Student Task Planner*. Proses mulai dari menyusun instruksi AI, mengeksekusi kode, hingga melakukan *versioning* serta mengunggahnya ke GitHub memberikan pengalaman langsung tentang alur kerja rekayasa perangkat lunak modern yang disiplin dan profesional.
