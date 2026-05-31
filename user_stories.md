# User Stories - Habit Tracker App

Repository: habit_tracker  
Deskripsi: Cerita pengguna untuk proyek aplikasi pelacakan kebiasaan.

---

## 1. Login dan Registrasi

### User Story 1: Pendaftaran Akun

**Title:** Pendaftaran Akun

**User Story:**  
Sebagai pengguna, saya ingin mendaftar dengan nama, nama pengguna, usia, dan negara saya agar saya dapat membuat akun dan mengakses fitur pelacakan kebiasaan.

**Acceptance Criteria:**
1. Pengguna dapat mengisi nama, nama pengguna, usia, dan negara.
2. Sistem menampilkan pesan berhasil ketika proses pendaftaran selesai.
3. Sistem menampilkan pesan kesalahan jika ada data wajib yang belum diisi.

**Priority:** High  
**Story Points:** 3  
**Labels:** enhancement, priority: high

**Notes:**
- Data pengguna tidak disimpan secara permanen setelah pengguna keluar.
- Login hanya dapat dilakukan menggunakan kredensial default sesuai batasan lab.

---

### User Story 2: Masuk Akun

**Title:** Masuk Akun

**User Story:**  
Sebagai pengguna, saya ingin masuk menggunakan nama pengguna dan kata sandi saya agar saya dapat mengakses akun saya dan melacak kebiasaan saya.

**Acceptance Criteria:**
1. Pengguna dapat memasukkan nama pengguna dan kata sandi.
2. Sistem memvalidasi kredensial login.
3. Pengguna diarahkan ke halaman utama setelah berhasil login.

**Priority:** High  
**Story Points:** 3  
**Labels:** enhancement, priority: high

**Notes:**
- Login menggunakan username dan password default.

---

### User Story 3: Umpan Balik Kesalahan Saat Masuk

**Title:** Umpan Balik Kesalahan Saat Masuk

**User Story:**  
Sebagai pengguna, saya ingin menerima pesan jika saya memasukkan nama pengguna atau kata sandi yang salah agar saya tahu bahwa upaya masuk saya tidak berhasil.

**Acceptance Criteria:**
1. Sistem menampilkan pesan kesalahan jika username salah.
2. Sistem menampilkan pesan kesalahan jika password salah.
3. Pengguna tetap berada di halaman login setelah gagal masuk.

**Priority:** High  
**Story Points:** 2  
**Labels:** bug, priority: high

**Notes:**
- Pesan error harus jelas dan mudah dipahami pengguna.

---

## 2. Halaman Utama

### User Story 4: Lihat Pesan Sambutan

**Title:** Lihat Pesan Sambutan

**User Story:**  
Sebagai pengguna, saya ingin melihat pesan sambutan yang dipersonalisasi dengan nama saya di halaman utama, agar saya merasa diperhatikan dan dapat memastikan saya masuk ke akun yang benar.

**Acceptance Criteria:**
1. Sistem menampilkan pesan sambutan di halaman utama.
2. Nama pengguna ditampilkan dalam pesan sambutan.
3. Pesan sambutan muncul setelah pengguna berhasil login.

**Priority:** Medium  
**Story Points:** 2  
**Labels:** enhancement, priority: medium

**Notes:**
- Nama yang ditampilkan dapat berasal dari data registrasi atau profil.

---

### User Story 5: Tampilkan Kemajuan Mingguan

**Title:** Tampilkan Kemajuan Mingguan

**User Story:**  
Sebagai pengguna, saya ingin melihat kemajuan harian saya untuk setiap kebiasaan di halaman utama, agar saya bisa dengan mudah memantau kemajuan saya.

**Acceptance Criteria:**
1. Sistem menampilkan daftar kebiasaan pengguna.
2. Sistem menampilkan status kemajuan harian setiap kebiasaan.
3. Kemajuan diperbarui ketika pengguna menyelesaikan kebiasaan.

**Priority:** High  
**Story Points:** 5  
**Labels:** enhancement, priority: high

**Notes:**
- Kemajuan dapat ditampilkan dalam bentuk daftar, kartu, atau indikator visual.

---

### User Story 6: Lihat Kebiasaan yang Telah Diselesaikan

**Title:** Lihat Kebiasaan yang Telah Diselesaikan

**User Story:**  
Sebagai pengguna, saya ingin melihat bagian untuk kebiasaan yang telah diselesaikan di halaman utama, agar saya bisa melacak apa yang telah saya capai.

**Acceptance Criteria:**
1. Sistem menampilkan bagian khusus untuk kebiasaan selesai.
2. Kebiasaan yang sudah diselesaikan muncul dalam daftar selesai.
3. Sistem membedakan kebiasaan selesai dan belum selesai.

**Priority:** Medium  
**Story Points:** 3  
**Labels:** enhancement, priority: medium

**Notes:**
- Dapat menggunakan tanda centang atau warna khusus untuk kebiasaan selesai.

---

## 3. Menu Navigasi

### User Story 7: Akses Opsi Menu

**Title:** Akses Opsi Menu

**User Story:**  
Sebagai pengguna, saya ingin mengakses menu dengan opsi untuk mengonfigurasi kebiasaan saya, melihat laporan, mengedit profil saya, dan keluar, sehingga saya dapat dengan mudah menavigasi ke berbagai bagian aplikasi.

**Acceptance Criteria:**
1. Pengguna dapat membuka menu dari halaman aplikasi.
2. Menu menampilkan opsi Profil, Kebiasaan, Laporan, Notifikasi, dan Keluar.
3. Setiap opsi menu dapat dipilih oleh pengguna.

**Priority:** High  
**Story Points:** 3  
**Labels:** enhancement, priority: high

**Notes:**
- Menu harus mudah ditemukan oleh pengguna.

---

### User Story 8: Navigasi ke Profil

**Title:** Navigasi ke Profil

**User Story:**  
Sebagai pengguna, saya ingin mengakses halaman profil dari menu, sehingga saya dapat melihat dan memperbarui informasi pribadi saya.

**Acceptance Criteria:**
1. Pengguna dapat memilih menu Profil.
2. Sistem mengarahkan pengguna ke halaman profil.
3. Halaman profil menampilkan informasi pengguna.

**Priority:** Medium  
**Story Points:** 2  
**Labels:** enhancement, priority: medium

**Notes:**
- Halaman profil harus dapat diakses dari menu utama.

---

### User Story 9: Navigasi ke Halaman Kebiasaan

**Title:** Navigasi ke Halaman Kebiasaan

**User Story:**  
Sebagai pengguna, saya ingin mengakses halaman kebiasaan dari menu, sehingga saya dapat mengonfigurasi dan mengelola kebiasaan saya.

**Acceptance Criteria:**
1. Pengguna dapat memilih menu Kebiasaan.
2. Sistem mengarahkan pengguna ke halaman kebiasaan.
3. Halaman kebiasaan menampilkan daftar kebiasaan pengguna.

**Priority:** High  
**Story Points:** 3  
**Labels:** enhancement, priority: high

**Notes:**
- Halaman kebiasaan digunakan untuk menambah, menghapus, dan mengatur kebiasaan.

---

### User Story 10: Keluar dari Menu

**Title:** Keluar dari Menu

**User Story:**  
Sebagai pengguna, saya ingin keluar dari akun saya menggunakan opsi di menu, sehingga saya dapat keluar dengan aman ketika saya selesai menggunakan aplikasi.

**Acceptance Criteria:**
1. Pengguna dapat memilih opsi Keluar dari menu.
2. Sistem menghapus sesi login pengguna.
3. Sistem mengarahkan pengguna kembali ke halaman login.

**Priority:** High  
**Story Points:** 2  
**Labels:** enhancement, priority: high

**Notes:**
- Setelah logout, data kredensial pengguna tidak disimpan di cache browser.

---

## 4. Halaman Profil

### User Story 11: Lihat Informasi Pribadi

**Title:** Lihat Informasi Pribadi

**User Story:**  
Sebagai pengguna, saya ingin melihat nama, nama pengguna, usia, dan negara yang saya simpan di halaman profil saya, sehingga saya dapat melihat detail yang saya berikan selama pendaftaran.

**Acceptance Criteria:**
1. Halaman profil menampilkan nama pengguna.
2. Halaman profil menampilkan nama pengguna, usia, dan negara.
3. Data ditampilkan dengan format yang mudah dibaca.

**Priority:** Medium  
**Story Points:** 2  
**Labels:** enhancement, priority: medium

**Notes:**
- Informasi profil harus sesuai dengan data yang diinput pengguna.

---

### User Story 12: Edit Informasi Pribadi

**Title:** Edit Informasi Pribadi

**User Story:**  
Sebagai pengguna, saya ingin memperbarui nama, nama pengguna, usia, dan negara saya di halaman profil saya, sehingga saya dapat menjaga informasi saya tetap terbaru.

**Acceptance Criteria:**
1. Pengguna dapat mengubah nama.
2. Pengguna dapat mengubah nama pengguna, usia, dan negara.
3. Sistem menyediakan tombol simpan untuk menyimpan perubahan.

**Priority:** Medium  
**Story Points:** 3  
**Labels:** enhancement, priority: medium

**Notes:**
- Form edit harus memvalidasi data yang wajib diisi.

---

### User Story 13: Simpan Informasi yang Diperbarui

**Title:** Simpan Informasi yang Diperbarui

**User Story:**  
Sebagai pengguna, saya ingin perubahan yang saya buat pada profil saya disimpan, sehingga detail terbaru saya tersimpan dan tercermin di seluruh aplikasi.

**Acceptance Criteria:**
1. Sistem menyimpan perubahan data profil.
2. Sistem menampilkan pesan berhasil setelah data diperbarui.
3. Data terbaru muncul ketika halaman profil dibuka kembali.

**Priority:** High  
**Story Points:** 3  
**Labels:** enhancement, priority: high

**Notes:**
- Perubahan harus langsung terlihat di aplikasi.

---

### User Story 14: Perbarui Nama di Header

**Title:** Perbarui Nama di Header

**User Story:**  
Sebagai pengguna, saya ingin nama yang diperbarui saya ditampilkan di header aplikasi setelah saya mengubahnya di profil, sehingga perubahan saya langsung terlihat.

**Acceptance Criteria:**
1. Nama di header berubah setelah pengguna menyimpan profil.
2. Nama terbaru ditampilkan tanpa harus login ulang.
3. Sistem tetap menampilkan nama lama jika perubahan gagal disimpan.

**Priority:** Medium  
**Story Points:** 2  
**Labels:** enhancement, priority: medium

**Notes:**
- Header harus sinkron dengan data profil terbaru.

---

## 5. Halaman Kebiasaan

### User Story 15: Tambahkan Kebiasaan Baru

**Title:** Tambahkan Kebiasaan Baru

**User Story:**  
Sebagai pengguna, saya ingin menambahkan kebiasaan baru di halaman konfigurasi detail agar saya dapat mengelola dan memperbarui kebiasaan saya sesuai kebutuhan.

**Acceptance Criteria:**
1. Pengguna dapat mengisi nama kebiasaan baru.
2. Sistem menambahkan kebiasaan ke daftar kebiasaan.
3. Sistem menampilkan pesan berhasil setelah kebiasaan ditambahkan.

**Priority:** High  
**Story Points:** 5  
**Labels:** enhancement, priority: high

**Notes:**
- Data kebiasaan harus muncul di halaman utama dan laporan.

---

### User Story 16: Hapus Kebiasaan

**Title:** Hapus Kebiasaan

**User Story:**  
Sebagai pengguna, saya ingin menghapus kebiasaan yang ada agar saya dapat menjaga kebiasaan saya tetap terbaru.

**Acceptance Criteria:**
1. Pengguna dapat memilih kebiasaan yang ingin dihapus.
2. Sistem menampilkan konfirmasi sebelum menghapus.
3. Kebiasaan terhapus dari daftar setelah dikonfirmasi.

**Priority:** Medium  
**Story Points:** 3  
**Labels:** enhancement, priority: medium

**Notes:**
- Penghapusan kebiasaan sebaiknya tidak terjadi tanpa konfirmasi.

---

### User Story 17: Personalisasi Kebiasaan dengan Warna

**Title:** Personalisasi Kebiasaan dengan Warna

**User Story:**  
Sebagai pengguna, saya ingin menetapkan warna tertentu untuk setiap kebiasaan agar terasa lebih personal bagi saya.

**Acceptance Criteria:**
1. Pengguna dapat memilih warna untuk setiap kebiasaan.
2. Warna yang dipilih tampil pada daftar kebiasaan.
3. Warna tetap tersimpan selama sesi aplikasi berjalan.

**Priority:** Low  
**Story Points:** 2  
**Labels:** enhancement, priority: low

**Notes:**
- Warna dapat digunakan untuk membedakan kebiasaan satu dengan lainnya.

---

## 6. Halaman Laporan

### User Story 18: Lihat Laporan Mingguan

**Title:** Lihat Laporan Mingguan

**User Story:**  
Sebagai pengguna, saya ingin melihat laporan kemajuan kebiasaan mingguan saya agar saya bisa memahami seberapa baik saya mempertahankan kebiasaan saya.

**Acceptance Criteria:**
1. Sistem menampilkan laporan mingguan.
2. Laporan berisi data kemajuan kebiasaan.
3. Pengguna dapat memahami jumlah kebiasaan yang selesai dalam seminggu.

**Priority:** High  
**Story Points:** 5  
**Labels:** enhancement, priority: high

**Notes:**
- Laporan dapat ditampilkan dalam bentuk ringkasan atau visualisasi sederhana.

---

### User Story 19: Visualisasikan Kebiasaan yang Telah Diselesaikan

**Title:** Visualisasikan Kebiasaan yang Telah Diselesaikan

**User Story:**  
Sebagai pengguna, saya ingin melihat grafik kebiasaan yang telah saya selesaikan untuk setiap hari dalam seminggu agar saya bisa dengan cepat mengidentifikasi tren dalam kemajuan saya.

**Acceptance Criteria:**
1. Sistem menampilkan grafik kebiasaan selesai.
2. Grafik menunjukkan data harian selama satu minggu.
3. Pengguna dapat melihat tren peningkatan atau penurunan kebiasaan.

**Priority:** Medium  
**Story Points:** 5  
**Labels:** enhancement, priority: medium

**Notes:**
- Grafik dapat berupa bar chart atau line chart sederhana.

---

### User Story 20: Lihat Semua Kebiasaan

**Title:** Lihat Semua Kebiasaan

**User Story:**  
Sebagai pengguna, saya ingin melihat kebiasaan yang telah diselesaikan dan yang belum diselesaikan dalam laporan saya agar saya memiliki pandangan yang komprehensif tentang kinerja pelacakan kebiasaan saya.

**Acceptance Criteria:**
1. Sistem menampilkan kebiasaan selesai.
2. Sistem menampilkan kebiasaan belum selesai.
3. Sistem membedakan status kebiasaan secara jelas.

**Priority:** Medium  
**Story Points:** 3  
**Labels:** enhancement, priority: medium

**Notes:**
- Status kebiasaan dapat menggunakan teks, ikon, atau warna.

---

## 7. Halaman Notifikasi

### User Story 21: Aktifkan atau Nonaktifkan Notifikasi

**Title:** Aktifkan atau Nonaktifkan Notifikasi

**User Story:**  
Sebagai pengguna, saya ingin dapat mengaktifkan atau menonaktifkan notifikasi untuk aplikasi, sehingga saya dapat memilih apakah akan menerima pengingat untuk kebiasaan saya atau tidak.

**Acceptance Criteria:**
1. Pengguna dapat mengaktifkan notifikasi.
2. Pengguna dapat menonaktifkan notifikasi.
3. Sistem menyimpan status pilihan notifikasi pengguna.

**Priority:** Medium  
**Story Points:** 3  
**Labels:** enhancement, priority: medium

**Notes:**
- Pengaturan notifikasi harus mudah diakses pengguna.

---

### User Story 22: Tambahkan Kebiasaan untuk Notifikasi

**Title:** Tambahkan Kebiasaan untuk Notifikasi

**User Story:**  
Sebagai pengguna, saya ingin memilih kebiasaan tertentu untuk menerima notifikasi, sehingga saya hanya mendapatkan pengingat untuk kebiasaan yang sedang saya kerjakan.

**Acceptance Criteria:**
1. Sistem menampilkan daftar kebiasaan.
2. Pengguna dapat memilih kebiasaan untuk diberi notifikasi.
3. Sistem hanya mengirim notifikasi untuk kebiasaan yang dipilih.

**Priority:** Medium  
**Story Points:** 3  
**Labels:** enhancement, priority: medium

**Notes:**
- Pengguna dapat memilih lebih dari satu kebiasaan.

---

### User Story 23: Atur Waktu Notifikasi

**Title:** Atur Waktu Notifikasi

**User Story:**  
Sebagai pengguna, saya ingin memiliki opsi untuk menerima notifikasi tiga kali sehari yaitu pagi, siang, dan malam untuk semua kebiasaan yang dipilih, sehingga saya mendapatkan pengingat yang tepat waktu sepanjang hari untuk menyelesaikan kebiasaan saya.

**Acceptance Criteria:**
1. Sistem menyediakan pilihan waktu pagi, siang, dan malam.
2. Pengguna dapat mengatur jadwal notifikasi.
3. Notifikasi dikirim sesuai waktu yang dipilih.

**Priority:** Medium  
**Story Points:** 5  
**Labels:** enhancement, priority: medium

**Notes:**
- Waktu notifikasi dapat dibuat default jika pengguna belum mengatur manual.
