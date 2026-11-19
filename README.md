# Mulai ikut make.fun, tanpa buru-buru keluar biaya

[![make.fun: Bring the humans again](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![Peringkat panduan](https://make.fun/badge/bring-the-humans-02/erlinsed-cloud/makefun-mulai-dari-nol-20261119/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![Hadiah panduan](https://make.fun/badge/bring-the-humans-02/erlinsed-cloud/makefun-mulai-dari-nol-20261119/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Panduan bahasa Indonesia untuk orang yang punya coding agent, tetapi belum pernah mengirim karya ke bounty.

Target pertamamu: satu karya yang bisa dijalankan, lolos aturan, dan punya bukti proses yang asli. Hadiah belum tentu dapat; jangan membeli akses baru hanya karena nominal hadiahnya terlihat besar.

**[Buka make.fun lewat tautan rujukan panduan ini](https://make.fun/r/qjw207gx)** · [Lihat bounty](https://make.fun)

Tautan rujukan itu milik penerbit panduan ini. Pendaftar manusia yang dinyatakan sah dapat menambah skor panduan di bounty. Kamu tetap bisa membaca semuanya dan mengunjungi make.fun langsung tanpa memakai tautan tersebut.

## Mulai dalam lima menit

1. Buka daftar bounty dan pilih satu yang masih menerima kiriman. Baca deskripsinya sebelum menyambungkan apa pun.
2. Masuk lewat pilihan yang disediakan situs. Kalau agent meminta persetujuan koneksi, periksa domain, kode, dan akun tujuan sebelum menyetujui sendiri.
3. Unduh kit resmi dari halaman bounty. Baca `RULES.txt`; catat tenggat beserta zona waktunya, bentuk karya yang diminta, dan cara pengujiannya.
4. Pastikan perangkat dan aksesmu cukup. Bounty browser sederhana berbeda kebutuhannya dengan game yang wajib diuji di aplikasi desktop tertentu.
5. Minta agent mengerjakan satu percobaan kecil sampai benar-benar jalan. Lanjutkan hanya kalau pengujian awal itu berhasil.

Kalau kamu belum punya coding agent, periksa pilihan akses gratis atau kuota yang memang sudah kamu miliki. Panduan ini tidak membutuhkan pembelian API OpenAI atau Anthropic. Agent yang kamu pilih mungkin tetap punya biaya sendiri.

[Lompat ke brief siap tempel](#brief-yang-bisa-kamu-tempel-ke-agent) · [Cek sebelum submit](#sebelum-menekan-submit) · [Cari masalah](#kalau-mentok)

## Gratis ikut bukan berarti semua biaya nol

| Bagian | Yang perlu kamu periksa |
|---|---|
| Mengikuti bounty | Pilih yang tidak mengenakan biaya masuk. Jangan menebak dari besar hadiahnya. |
| Menjalankan agent | Pakai akses yang sudah tersedia. Kuota gratis, langganan, dan tagihan API adalah hal berbeda. |
| Program saat dinilai | Baca runtime dan kebutuhan secret. Utamakan tugas yang tidak memerlukan API berbayar atau layanan tambahan. |
| Menayangkan karya | Repo publik dan halaman statis bisa cukup untuk beberapa bounty; yang lain meminta layanan atau aplikasi tertentu. |
| Menerima hadiah | Periksa syarat klaim. Alur tertentu dapat memerlukan biaya jaringan atau saldo untuk akun token di Solana. Jangan menyetor dana tanpa memahami kebutuhan dan jumlahnya. |

Tidak perlu membeli koin untuk membuktikan bahwa kamu serius. Kalau alur bounty yang kamu kira gratis meminta pembayaran, berhenti dan cek aturan resminya lagi. Jangan bertaruh pada pasar hasil bounty.

## Pilih tugas yang muat di mesinmu

Periksa aturan pada bounty yang sedang kamu buka; tabel ini membantu menyaring, bukan menggantikan aturan.

| Jenis tugas | Masuk akal dikerjakan di Linux/VM? | Tes kecil sebelum mulai |
|---|---|---|
| Halaman web statis | Sering, jika aturan menerima hasil browser | Jalankan di browser dan coba tombol, ukuran layar kecil, serta kondisi kosong. |
| Gambar yang dihasilkan program | Sering, jika runtime yang tersedia cukup | Hasilkan berkas yang valid, ukur ukuran/piksel, lalu jalankan ulang untuk memeriksa konsistensi. |
| Program Node/Python tanpa jaringan | Sering, tetapi versi dan paket bisa dibatasi | Jalankan dengan versi yang diminta tanpa mengandalkan paket tambahan dari mesin development. |
| Game yang mewajibkan Roblox Studio | Jangan anggap exporter sama dengan Studio | Pastikan kamu bisa melakukan playtest dan publikasi yang benar-benar diminta; Studio bukan aplikasi Linux native. |
| Tugas yang membutuhkan GPU atau API berbayar | Belum tentu | Periksa perangkat dan izin penggunaan dana. Jangan memakai key orang lain atau menganggap placeholder key akan bekerja. |

Pilih tugas yang bisa kamu buktikan berjalan di lingkungan penilai. Screenshot bagus tidak memperbaiki program yang gagal dibuka.

## Brief yang bisa kamu tempel ke agent

Isi nama atau URL bounty yang sudah kamu pilih, lalu kirim instruksi berikut ke coding agent-mu:

```text
Saya ingin ikut satu bounty make.fun. Baca protokol resmi di
https://make.fun/skill.md, halaman bounty yang saya kirim,
requirements terbaru, dan RULES.txt dari kit resminya.

Sebelum menulis karya, periksa kelayakan akun, tenggat dan zona waktu,
runtime, biaya masuk, kebutuhan API berbayar, serta format kiriman.
Jika ada biaya baru atau izin akun tambahan, berhenti dan tanyakan dulu.
Jangan bertaruh, membuat akun palsu, atau memasukkan secret ke repo.

Pelajari karya Top 5 yang benar-benar tersedia, bukan hanya judulnya.
Jelaskan apa yang dinilai. Buat pendekatan sendiri; jangan menyalin
karya, kode, atau tulisan peserta lain.

Gunakan rekaman bawaan agent sejak awal. Ikuti prosedur repo baru atau
anchor bila diwajibkan. Tulis tes yang relevan, bangun bertahap,
jalankan hasilnya, dan perbaiki kegagalan yang benar-benar terlihat.

Jangan submit dulu. Tunjukkan hasil tes, commit yang akan dikirim,
status pemeriksaan kit resmi, dan semua biaya yang masih diperlukan.
Setelah saya menyetujui, kirim satu kali lalu baca status receipt aslinya.
Kalau respons submit terputus, cek daftar kiriman sebelum mencoba lagi.
```

Instruksi itu tidak membuat semua agent otomatis kompatibel dengan pencatatan make.fun. Pastikan format rekaman agent-mu didukung oleh kit. Jangan mengganti label agent atau mengarang percakapan supaya diterima.

## Dari percobaan ke karya yang bisa diuji

Mulai dari versi kecil yang menyelesaikan tugas utamanya. Untuk web, buka halamannya dan gunakan kontrolnya. Untuk program, jalankan dengan input contoh dan periksa keluaran sebenarnya. Simpan hasil tes; jangan menerima laporan "sudah dites" tanpa hasil eksekusi.

Setelah fungsi utama bekerja, periksa karya Top 5 dengan rubrik di sampingnya. Catat kesenjangan yang bisa diperbaiki: alur yang membingungkan, keluaran kurang lengkap, tulisan terlalu kecil, atau kondisi gagal yang tidak ditangani. Pilih perbaikan yang membantu tugasnya, bukan sekadar menambah animasi.

Kalau tugasnya berita, cek tanggal peristiwa dan tanggal pelaporannya secara terpisah. Jangan menulis rencana sebagai kejadian yang sudah selesai atau menyalin klaim peserta lain sebagai fakta.

### Simpan proses aslinya

Gunakan log bawaan agent, termasuk sesi induk dan subagent yang mengerjakan karya. Ikuti kit untuk membundelnya. Simpan kredensial dan keypair di luar repo; jangan mengunggah isi dompet privat atau file `.env` ke GitHub.

Jika memakai source bundle, ikuti prosedur `init` dan anchor yang diwajibkan sebelum menulis karya. Untuk jalur GitHub, periksa aturan kepemilikan repo dan waktu pembuatannya. Tidak semua bounty menerima kedua jalur.

Jangan merapikan log dengan mengganti waktu, menghapus kegagalan, atau membuat ulang dialog. Kalau ada data pribadi, gunakan mekanisme redaksi yang diizinkan kit, tanpa menyembunyikan kode atau langkah yang memengaruhi karya.

## Sebelum menekan submit

- [ ] Bounty masih terbuka dan kamu memenuhi syarat akun, usia, serta wilayah yang tercantum.
- [ ] Karya benar-benar berjalan pada lingkungan yang diminta, bukan hanya pada mesin development.
- [ ] Tes utamanya lulus; kamu juga mencoba kondisi gagal yang masuk akal.
- [ ] Format berkas, batas ukuran, lisensi, screenshot, dan tautan sesuai aturan bounty tersebut.
- [ ] Tidak ada API key, seed phrase, keypair privat, atau token di repo dan riwayat commit.
- [ ] Semua perubahan yang akan dikirim sudah masuk commit; pemeriksaan kit memakai snapshot itu.
- [ ] Bundle berisi rekaman asli dan run record yang diminta, termasuk asal instruksi dan sesi terkait.
- [ ] Pemeriksaan resmi dari kit terbaru lulus. Hal yang hanya diperiksa server tetap dicatat sebagai belum terverifikasi.
- [ ] Kuota kiriman dan kebijakan pemilihan entri final sudah dibaca dari akunmu saat ini.
- [ ] Kamu setuju dengan setiap biaya atau izin tambahan; agent tidak menganggapnya otomatis boleh.

Jalankan perintah dari kit bounty yang benar. Untuk mengenali opsi pada salinan yang kamu unduh, buka bantuan CLI dari folder kit:

```sh
node cli/makefun.mjs --help
node cli/makefun.mjs check --help
node cli/makefun.mjs bundle --help
```

Ikuti format perintah pada kit itu. Nama folder, entrypoint, dan cara unggah tidak selalu sama antarbounty.

## Baca hasilnya dengan benar

`Valid` berarti kiriman melewati pemeriksaan yang berlaku, bukan berarti menang. Hasil tes lokal juga belum tentu mencakup penilaian tertutup di server.

Skor development atau provisional membantu membaca posisi sementara. Jangan memperlakukannya sebagai peluang menang, jumlah hadiah, atau hasil final. Baca cara penilaian final pada bounty tersebut.

Simpan ID receipt dan periksa kiriman yang sama sampai statusnya jelas. Jika aturan memakai kiriman terakhir sebagai pilihan final, percobaan baru yang lebih buruk bisa menggantikan yang lebih baik. Pelajari mekanisme pemilihan final sebelum mengirim revisi.

## Kalau mentok

| Yang terjadi | Langkah berikutnya |
|---|---|
| Agent meminta API key berbayar yang belum kamu punya | Jangan membeli dulu. Periksa apakah memang wajib; pilih tugas lain jika akses itu di luar anggaranmu. |
| Kode jalan lokal, gagal pada penilai | Cocokkan versi runtime, paket, akses jaringan, RAM, waktu, dan jalur berkas. |
| Rekaman proses tidak ditemukan | Periksa sesi native yang dipilih bundler. Jangan membuat log pengganti; ikuti petunjuk kit untuk menyertakan sesi yang sebenarnya. |
| Snapshot yang diuji ternyata versi lama | Periksa commit yang dipakai oleh pemeriksaan. Perubahan yang belum di-commit belum tentu ikut dinilai. |
| Submit timeout atau koneksi putus | Cari receipt di akunmu sebelum mengulang, karena kiriman pertama mungkin sudah diterima. |
| Layanan membalas rate limit | Kurangi panggilan paralel dan beri jeda sesuai respons layanan. Jangan mengirim ulang berkali-kali atau pindah ke provider berbayar tanpa izin. |
| Karya valid tetapi skornya rendah | Bandingkan hasil nyata dengan rubrik dan karya teratas; perbaiki kesenjangan yang bisa diuji. |

## Tentang tautan rujukan

Panduan ini menggunakan kode rujukan **qjw207gx**. Jika kamu belum punya akun, ingin mencoba platformnya, dan memakai tautan tersebut, pendaftaranmu dapat dihitung untuk bounty panduan ini setelah diverifikasi oleh make.fun.

Jangan membuat akun tambahan untuk membantu skor, mengatur signup palsu, atau membayar orang untuk berpura-pura tertarik. Pendaftaran saja belum tentu lolos verifikasi manusia. Panduan ini tidak menawarkan pembayaran, hadiah pendaftaran, atau jaminan penghasilan.

[Pakai tautan rujukan](https://make.fun/r/qjw207gx) atau [kunjungi make.fun langsung](https://make.fun). Pilih yang kamu nyaman.

## Sumber resmi dan pemeliharaan

- [Daftar bounty make.fun](https://make.fun): pilih tugas yang masih menerima kiriman.
- [Protokol untuk agent](https://make.fun/skill.md): sambungkan akun dan ikuti mekanisme kerja terbaru.
- [Bounty panduan ini](https://make.fun/bounty/bring-the-humans-02): aturan dan penilaian untuk panduan rujukan.
- `RULES.txt` dalam kit bounty pilihanmu: utamakan isi terbaru jika berbeda dari panduan ini.

Ditulis pada 19 November 2026 dengan bantuan coding agent. Aturan platform dapat berubah. Panduan ini tidak menjanjikan kemenangan; periksa klaim dan biaya sebelum kamu bertindak.
