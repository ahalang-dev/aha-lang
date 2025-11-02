# Berkontribusi ke AHA! Lang

Terima kasih atas minat Anda untuk berkontribusi ke AHA! Lang! Ini adalah panduan singkat untuk membantu Anda memulai.

## Cara Berkontribusi

### Melaporkan Bug
Jika Anda menemukan bug, silakan buat "Issue" baru di GitHub dengan label `bug`. Sertakan:
- Deskripsi singkat masalahnya.
- Langkah-langkah untuk mereproduksi bug.
- Log error (jika ada).
- Informasi lingkungan (OS, versi Rust, versi LLVM).

### Menyarankan Fitur
Jika Anda memiliki ide untuk fitur baru, silakan buat "Issue" baru dengan label `enhancement`. Jelaskan:
- Apa fitur tersebut dan mengapa itu berguna.
- Bagaimana Anda membayangkan penggunaannya.

### Berkontribusi Kode
1.  **Fork** repositori ini.
2.  **Buat branch baru** untuk fitur atau perbaikan Anda (`git checkout -b fitur-baru-saya`).
3.  **Lakukan perubahan** Anda. Pastikan kode mengikuti gaya yang sudah ada dan semua tes berjalan.
4.  **Commit** perubahan Anda (`git commit -m 'Menambahkan fitur X'`).
5.  **Push** ke branch Anda (`git push origin fitur-baru-saya`).
6.  **Buat Pull Request** ke branch `main` repositori asli.

## Pengaturan Lingkungan Pengembangan

Pastikan Anda telah mengikuti langkah-langkah di `README.md` untuk menginstall semua prasyarat (Rust, LLVM, dll).

Untuk memastikan semuanya berjalan dengan baik, jalankan:
```bash
cargo check
cargo test
