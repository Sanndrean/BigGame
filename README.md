# BigGame

Game web layar penuh, mobile-first. Tidak memakai paket atau backend.

## Menjalankan

Buka `index.html` di browser, atau gunakan Live Server di VS Code. Tekan **PLAY** untuk mencoba masuk fullscreen (dukungan fullscreen bergantung pada browser/perangkat). Musik akan mulai otomatis jika file `music.mp3` tersedia di sebelah `index.html`.

## Cerita

Urutan cerita: gambar stickman, kasur, meja belajar, lampu tidur, tidur sampai pagi, makanan, baju, dan celana. Setelah makanan digambar, tulis namanya. Geser gambar ke mana pun di layar kamar lalu pilih **TARUH DI SINI**. Baju dan celana perlu ditempel ke badan stickman agar dikenakan dan ikut bergerak saat ia berjalan.

Game membaca coretan kasur untuk memperkirakan permukaan atasnya, lalu membuat stikman berjalan mendekat dan naik ke atas kasur. Benda lain juga dapat diletakkan di berbagai posisi kamar. Pemrosesan bentuk berjalan lokal di browser, tanpa layanan AI atau koneksi internet.

## Admin dan penyimpanan

Ketuk **By: Shannon Andrea** lima kali, lalu masukkan kode `777766`. Admin punya kategori **Semua**, **Belum Dinilai**, **Sudah Dinilai**, dan **Leaderboard**. Kamar diurutkan berdasarkan nilai tertinggi; leaderboard hanya menampilkan foto profil dan nama. Jika foto wajah ditolak, lingkaran foto profil tetap kosong. Admin dapat memberi nilai 1–100 dan menghapus data pemain.

Progres dan foto hanya tersimpan di browser lokal ini. Agar pemain HP dapat mengirim data yang terlihat admin di PC, perlu Firebase: Firestore untuk data pemain/nilai, Storage untuk gambar, serta Authentication untuk akses admin.

Sesudah cerita selesai, layar tamat tampil dua detik lalu game bertanya: “Bolehkah kita melihat wajah kamu untuk ditaruh di leaderboard?” Foto wajah bersifat opsional.

## Musik

Tambahkan lagu MP3 bernama `music.mp3` di folder yang sama dengan `index.html`. ZIP tidak menyertakan audio kosong atau lagu berhak cipta.

Untuk menghapus progres lewat ⚙ → **MULAI DARI AWAL**, masukkan kode admin `777766` lalu pilih **HAPUS PROGRES**.
