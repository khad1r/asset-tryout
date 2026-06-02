# 🗃️ Repositori Aset Gambar Tryout 

Repositori ini secara eksklusif digunakan sebagai penyimpanan (hosting) gambar soal ujian. Gambar yang diunggah ke sini akan secara otomatis ditarik oleh sistem aplikasi tryout.

⚠️ **PERINGATAN KERAS:** Kesalahan penamaan file di sini akan menyebabkan soal gagal dimuat (blank) di layar peserta. Baca dan patuhi aturan di bawah ini sebelum mengunggah apa pun.

---

## ⛔ ATURAN WAJIB PENAMAAN FILE (SANGAT KETAT)

Sistem komputer tidak bisa membaca spasi atau huruf besar dengan baik. Semua nama file gambar **WAJIB** mengikuti format berikut:

1. **Gunakan Huruf Kecil Semua:** `soal_tiu.png` (BENAR) | `Soal_TIU.png` (SALAH)
2. **DILARANG Menggunakan Spasi:** `tiu_01.png` (BENAR) | `tiu 01.png` (SALAH)
3. **Gunakan Garis Bawah (_):** Jangan gunakan tanda hubung (-) atau simbol lainnya.
4. **Format File Wajib:** Hanya gunakan `.png` atau `.jpg`.

### 🔄 ATURAN REVISI SOAL (PENTING!)
Jika Anda menyadari ada gambar soal yang salah SETELAH diunggah, **JANGAN MENGUNGGAH ULANG DENGAN NAMA YANG SAMA.** Sistem akan tetap menampilkan gambar yang lama (efek *cache*). 

Selalu tambahkan `_v2`, `_v3` pada akhir nama file jika itu adalah gambar revisi.
* Awal: `tiu_15.png`
* Revisi 1: `tiu_15_v2.png`
* Revisi 2: `tiu_15_v3.png`

---

## 📤 CARA MENGUNGGAH GAMBAR (Tanpa Coding)

1. Pastikan Anda sudah login ke akun GitHub.
2. Buka halaman utama repositori ini.
3. Klik tombol **`Add file`** di bagian atas daftar file, lalu pilih **`Upload files`**.
4. Tarik dan lepas (*drag-and-drop*) semua file gambar Anda ke dalam kotak yang tersedia (bisa puluhan file sekaligus).
5. Tunggu hingga proses *loading* semua gambar selesai.
6. Geser ke bawah, lalu tekan tombol hijau **`Commit changes`**.
7. Selesai. Gambar sudah online.

---

## 📝 CARA MEMASUKKAN KE GOOGLE SHEETS

Setelah gambar diunggah ke sini, buka Google Sheets (Database Soal).
Pada kolom `Nama File Gambar`, **cukup ketikkan nama filenya saja beserta ekstensinya.**

* **Tulis:** `tiu_24.png`
* **JANGAN Tulis URL panjang:** `https://cdn.jsdelivr.net/.../tiu_24.png` (Sistem akan membuatkan URL-nya secara otomatis untuk Anda).

Jika gambar tidak muncul di aplikasi Tryout, periksa kembali apakah ada *typo* antara nama file yang Anda ketik di Google Sheets dengan nama file asli yang terunggah di repositori ini.
