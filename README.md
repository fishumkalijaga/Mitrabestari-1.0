# Workshop Article Studio — @ramakertamukti Labs

Aplikasi penulisan naskah ilmiah berbasis alur **Workshop Menulis Artikel Jurnal Terindeks Scopus** (25 slide). Menu: (1) fokus, (2) sintesis literatur dan gap, (3) metode serta data, (4) editor IMRaD, (5) jurnal dan submission, (6) audit dan respons reviewer.

## Cara cepat

Buka `index.html` di Chrome, Firefox atau Edge, lalu isi judul dan abstrak. Untuk draf yang lebih berguna, isi bukti literatur, desain penelitian, dan temuan terverifikasi. Klik **Susun draf berbasis isian** di halaman Editor IMRaD. Teks hasil dapat disunting.

**Cetak PDF** membuka dialog cetak browser → pilih *Save as PDF*. **Word** menghasilkan `.docx` asli (bukan `.doc` HTML). Ekspor **JSON** sebagai cadangan proyek, dan impor kembali jika berpindah perangkat.

## Deploy ke GitHub Pages

1. Buat repository publik atau repository yang mendukung Pages di akun Anda.
2. Unggah seluruh file paket ini langsung ke akar (`index.html`, `manifest.webmanifest`, `sw.js`, ikon, README).
3. Buka **Settings → Pages**. Pada **Build and deployment**, pilih **Deploy from a branch**, lalu `main` dan `/(root)`.
4. Setelah terbit, kunjungi `https://<username>.github.io/<nama-repo>/`.
5. Untuk pemasangan ke Home Screen, buka situs melalui HTTPS pada browser yang mendukung PWA, gunakan menu *Install app* / *Add to Home Screen*.

Aplikasi HTML bisa dibuka sebagai file lokal untuk penulisan dan ekspor. Fitur pemasangan PWA bekerja pada HTTPS/localhost, bukan berkas `file://`.

## Batas dan integritas akademik

- Aplikasi berjalan tanpa backend, AI model, atau API penelusuran jurnal. Draf adalah **transformasi berbasis aturan dari input penulis**, bukan analisis literatur otomatis.
- **Tidak** mengarang sumber, hasil statistik, kutipan wawancara, jumlah responden, persetujuan etik atau status indeksasi jurnal.
- Hasil hanya dimasukkan bila klaim, bukti, lokasi jejak dan konfirmasi penulis tersedia. Konfirmasi ini tidak sama dengan verifikasi independen.
- `Q1` dan status jurnal bukan diverifikasi aplikasi; input sumber, kategori, tahun dan tanggal cek manual melalui Scopus Sources/SCImago.
- Hasil audit adalah checklist **kelengkapan data**, bukan peringkat kualitas artikel atau probabilitas diterima jurnal.
- Penyimpanan menggunakan localStorage browser; jangan menganggapnya backup permanen. Unduh JSON secara berkala. Hindari data responden yang teridentifikasi.

## Acuan isi

Berdasarkan PPTX pengguna *Workshop Menulis Artikel Jurnal Terindeks Scopus*. Material slide mencantumkan Tress, G., Tress, B., & Saunders, D. A. (2014), *How to write a paper for successful publication in an international peer-reviewed journal*, Pacific Conservation Biology, 20(1), 17–24; serta panduan Scopus Sources, Elsevier Journal Finder, dan COPE. Adaptasi mengikuti struktur dan istilah dari slide yang diunggah pengguna. Pedoman jurnal tujuan tetap berlaku.
