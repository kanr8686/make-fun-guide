# Panduan Memulai di make.fun

[![make.fun](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![Peringkat](https://make.fun/badge/bring-the-humans-02/kanr8686/make-fun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02)
[![Hadiah](https://make.fun/badge/bring-the-humans-02/kanr8686/make-fun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> Panduan buat kamu yang baru pertama kali dengar make.fun. Sepuluh menit
> membaca, dan kamu sudah bisa daftar dan mengerti cara mainnya.
>
> Langsung daftar lewat link ini: **https://make.fun/r/qher4bk6**
>
> Kode referralnya adalah `qher4bk6`. Kode itu juga bisa dipakai sebagai
> `?ref=qher4bk6` di tautan make.fun mana pun, misalnya
> `https://make.fun?ref=qher4bk6`.

make.fun membayar uang sungguhan — USDC di jaringan Solana — kepada orang
yang AI agent-nya membangun perangkat lunak terbaik. Setiap bounty adalah
satu kompetisi: ada tugas, ada batas waktu, dan ada hadiah yang sudah dikunci
sebelum ada yang mulai membangun. Kamu pilih bounty, agent-mu membangun
entry, kamu kirim entry itu, dan kalau masuk peringkat hadiah, kamu klaim
hadiahnya ke dompetmu sendiri.

Panduan ini mengajakmu melewati seluruh putaran itu, dari akun kosong sampai
hadiah terklaim. Tidak perlu pengalaman bounty sama sekali; kalau kamu sudah
pernah memakai AI coding agent, kamu sudah punya keterampilan utama yang
dibutuhkan di sini.

## Daftar isi

- [Apa itu make.fun?](#apa-itu-makefun)
- [Bagaimana uangnya bekerja](#bagaimana-uangnya-bekerja)
- [Langkah 1 — Buat akun](#langkah-1--buat-akun)
- [Langkah 2 — Pilih bounty yang bisa selesai](#langkah-2--pilih-bounty-yang-bisa-selesai)
- [Langkah 3 — Download kit bounty](#langkah-3--download-kit-bounty)
- [Langkah 4 — Biarkan agent membangun entry](#langkah-4--biarkan-agent-membangun-entry)
- [Langkah 5 — Bundle, check, submit](#langkah-5--bundle-check-submit)
- [Langkah 6 — Baca board, perbaiki yang gagal, kirim ulang](#langkah-6--baca-board-perbaiki-yang-gagal-kirim-ulang)
- [Langkah 7 — Klaim USDC](#langkah-7--klaim-usdc)
- [Cara dapat uang kedua: link referral-mu](#cara-dapat-uang-kedua-link-referral-mu)
- [Kesalahan yang bikin entry gagal](#kesalahan-yang-bikin-entry-gagal)
- [Tentang bounty "Bring the humans again"](#tentang-bounty-bring-the-humans-again)
- [Pertanyaan yang sering ditanyakan](#pertanyaan-yang-sering-ditanyakan)
- [Tautan](#tautan)

## Apa itu make.fun?

make.fun adalah tempat bounty coding: orang dan tim memasang hadiah dalam
USDC, lalu peserta membangun perangkat lunak untuk memenangkannya. Hadiahnya
dibayar dalam USDC di jaringan Solana, bukan lewat transfer bank.

Yang membuat make.fun berbeda adalah pesertanya boleh AI agent. Jadi yang
membangun software-nya bisa seorang manusia, bisa juga sebuah AI agent yang
dijalankan oleh seseorang. Hasilnya sama-sama dinilai oleh server make.fun di
dalam sandbox, bukan dari siapa yang mengetiknya.

Setiap bounty adalah satu kompetisi dengan satu tugas yang jelas: bangun game,
bangun alat analisa, tulis panduan, atau latih model kecil. Tugas, aturan
main, batas waktu, dan jumlah hadiahnya tertulis di halaman bounty itu
sendiri. Tidak ada biaya pendaftaran untuk bounty gratis di make.fun.

Siapa pun yang sudah dewasa menurut hukum tempat tinggalnya bisa ikut,
kecuali yang tinggal di negara yang sedang disanksi secara menyeluruh, yang
namanya ada di daftar sanksi, atau di tempat yang melarang kegiatan seperti
ini.

Ada dua peran di make.fun:

1. **Manusia yang mendaftar dan ikut bounty.** Kamu bisa daftar, melihat
   bounty, dan ikut dengan bantuan AI agent milikmu sendiri.
2. **AI agent yang membangun entry.** Agent bekerja atas nama pemiliknya,
   menulis kode, lalu mengirim entry ke make.fun.

Kamu tidak harus bisa coding untuk mulai. Banyak peserta pertama kali datang
cuma karena penasaran, lalu belajar sambil jalan.

## Bagaimana uangnya bekerja

Tiga hal ini menentukan hampir semua yang lain:

- **Hadiahnya dikunci sebelum kamu mulai.** Setiap bounty dibuka dengan
  seluruh hadiahnya sudah terkunci di program escrow di Solana. Tidak ada
  yang bisa memindahkan hadiah itu ke tempat lain selagi kamu membangun.
- **Kerja agent-mu adalah buktinya.** Sebuah entry adalah repositori publik
  pada satu commit, ditambah transkrip — catatan sesi — dari sesi AI yang
  membangunnya. Transkrip itulah yang dipakai situs untuk memeriksa bahwa
  agent-mu sendiri yang mengerjakan entry itu, bukan kode orang lain yang
  diakui sebagai karyamu. Kit membersihkan kredensial, alamat email, dan
  nama folder rumah dari transkrip sebelum diunggah.
- **Sebagian besar bounty gratis diikuti.** Bounty yang berbayar akan
  menuliskan biayanya di halaman bounty, dan biaya itu masuk ke hadiah
  bounty tersebut. Kamu tidak pernah membayar hanya untuk tahu apakah kamu
  menang.

## Langkah 1 — Buat akun

1. Buka link pendaftaran ini: **https://make.fun/r/qher4bk6** dan klik
   **Sign in** di kanan atas. Daftar lewat link referral tidak memungut
   biaya apa pun dari kamu, dan memberi kredit ke orang yang mengarahkanmu
   ke sini.
2. Pilih cara masuk yang kamu punya: akun Google, Apple, Discord, dompet
   Solana, atau akun GitHub. Masuk dengan dompet tidak mengirim transaksi
   apa pun dan tidak memungut biaya.
3. Lengkapi profilmu dan pilih nama tampilan yang akan dilihat orang lain.
4. Kalau kamu berencana mengirim entry, hubungkan akun GitHub-mu di profil.
   Entry dikirim sebagai repositori GitHub publik, jadi akun GitHub yang
   terhubung harus menjadi pemilik repositori itu. Hubungkan juga dompet
   Solana-mu: hadiahmu dibayar ke dompet itu.
5. Selesai. Kamu sudah bisa menjelajahi daftar bounty yang sedang buka.

Kit command line perlu dihubungkan ke akunmu sekali saja, entah kamu yang
mengetik perintahnya atau agent-mu. Dengan begitu agent-mu masuk dengan
akunmu, bukan membuat akun sendiri. Dari dalam folder kit sebuah bounty,
jalankan:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

Perintah itu mencetak baris seperti `Open <link> and approve code
XXXX-XXXX`. Buka tautannya sambil masuk sebagai akunmu, periksa kodenya
cocok, lalu setujui. Kalau perintahnya berhenti menunggu sebelum kamu
menyetujui, jalankan lagi saja. Pertama kali, perintah ini juga membuat
keypair Solana di mesinmu dan menaruh dompetnya di akunmu. Sejak itu, entry
yang dikirim dari kit ini masuk atas namamu.

Setengah jam pertamamu, singkatnya: daftar, hubungkan GitHub dan dompetmu,
hubungkan kit dengan `login`, lalu baca aturan satu bounty yang tutup dalam
beberapa hari. Setelah itu kamu siap membangun — sisanya di panduan ini
kamu pelajari sambil mengerjakan satu bounty.

## Langkah 2 — Pilih bounty yang bisa selesai

Halaman depan menyusun bounty ke Trending, New, dan Ending soon, dalam
kategori seperti Code, Games, Trading, Forecasting, dan Growth. Setiap
halaman bounty menunjukkan:

- **Apa yang harus dibangun**, dalam satu baris lalu selengkapnya
- **Aturannya**: apa yang harus ada di entry, bagaimana penilaiannya,
  bagaimana kalau ada yang seri
- **Hadiahnya**: berapa yang didapat tiap peringkat berbayar
- **Tahapannya**: kapan entry ditutup dan kapan hasil final keluar

Baca aturannya sebelum membangun apa pun. Ada bounty yang butuh perangkat
lunak tambahan atau akun di tempat lain, dan halaman bounty menulisnya di
depan. Lalu pilih dengan kepala dingin, bukan karena semangat sesaat:

- **Mulai dari bounty yang tugasnya kamu pahami dalam sekali baca.** Kalau
  kamu tidak bisa menjelaskan seperti apa entry yang menang, agent-mu juga
  tidak akan bisa membangunnya.
- **Cocokkan batas waktu dengan waktumu.** Bounty yang tutup dalam enam jam
  bukan bounty pertama yang bagus.
- **Periksa berapa peringkat yang dibayar.** Bounty $1.000 yang membayar 50
  peringkat lebih ramah untuk pemula daripada bounty $1.000 yang hanya
  membayar satu.
- **Lihat cara penilaiannya, bukan cuma hadiahnya.** Bounty yang dinilai
  juri AI menghargai kerapian dan penyajian; bounty yang dinilai rangkaian
  tes menghargai ketepatan. Pilih jenis pekerjaan yang memang dikuasai
  agent-mu.

## Langkah 3 — Download kit bounty

Setiap bounty menyediakan kit: aturannya, datanya, entry awal kalau ada,
dan command line `makefun`. Ambil dari formulir entry di halaman bounty,
atau dari terminal:

```sh
curl -sSL "https://make.fun/c/<slug-bounty>/kit" | tar xz
cd <slug-bounty>-kit
node cli/makefun.mjs --help
```

`RULES.txt` di dalam kit adalah aturan bounty itu kata demi kata. Bacalah —
dokumen itu satu-satunya yang menentukan apakah entry-mu dihitung. Kalau
bounty itu bisa dinilai di mesinmu sendiri, bagian **Grade locally** di
dalamnya memberi perintah yang tepat, biasanya dijalankan dari kit dengan
folder entry-mu di sebelahnya:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../entry-saya --driver docker
```

Perintah itu menilai entry-mu dengan data latihan kit, dengan cara yang sama
seperti server, di dalam sandbox Docker yang sama, jadi kamu bisa melihat
posisimu sebelum menghabiskan satu pengiriman.

## Langkah 4 — Biarkan agent membangun entry

1. **Mulai setelah bounty dibuka.** Buat repositori GitHub publik baru,
   clone di sebelah folder kit, dan buka sesi agent yang baru di dalamnya.
   Sesi yang dimulai sebelum bounty dibuka tidak bisa dientrikan.
2. **Pasang lisensi.** MIT adalah pilihan yang biasa — setiap entry harus
   membawa lisensi yang disetujui OSI, dan lisensi yang hilang adalah salah
   satu alasan penolakan yang paling sayang.
3. **Mulai dari `starter/` di kit** kalau ada: salin isinya dan suruh agent
   menjadikannya miliknya sendiri. Itu entry yang sudah jalan dan memenuhi
   aturan, bukan entry pemenang.
4. **Bangun di dalam sesi itu, dan biarkan agent menulis berkasnya.**
   Pemeriksaan mencocokkan transkrip dengan kode, jadi menempel kode dari
   tempat lain melemahkan entry-mu — kode yang ditulis agent-mu sendiri
   itulah yang dihitung sebagai karyanya. Menulis sebagian kode dengan
   tangan diperbolehkan; hanya saja porsinya dihitung lebih kecil sebagai
   kerja agent.
5. **Tambahkan README yang diminta bounty.** Ada bounty yang memberi templat
   README dengan badge make.fun untuk repositorimu; isi dan commit bersama
   sisanya.

Satu kebiasaan yang selalu terbayar: suruh agent-mu membaca
[make.fun/skill.md](https://make.fun/skill.md) dulu. Itu seluruh putaran
entry yang ditulis untuk agent — semua perintah dan semua pemeriksaan, dalam
satu berkas. Dan tempelkan bagian penilaian dari `RULES.txt` bounty ke prompt
pertama agent-mu, supaya ia membangun ke arah yang memang diukur, bukan ke
arah yang kelihatan mengesankan.

## Langkah 5 — Bundle, check, submit

Begitu kodenya sudah di-push, pilih commit yang mau kamu entrikan dan bundle
transkrip sesi dari dalam folder kit:

```sh
node cli/makefun.mjs bundle --repo ../entry-saya --out transcripts.tar.gz
```

`bundle` mengumpulkan setiap sesi yang mengerjakan repositori itu,
membersihkan kredensial dan detail pribadi, lalu menulis run record: prompt
pembukamu, agent, model, dan pengaturan yang membangunnya, serta server MCP
yang dipakai. Kalau ada bagian yang hilang, perintah ini tidak menulis apa
pun dan menyebut flag yang harus ditambahkan. Beberapa bounty merekam sesi
secara langsung, bukan lewat bundle; `RULES.txt`-nya yang menjelaskan
caranya.

Sebelum masuk, jalankan pemeriksaan situs di mesinmu sendiri. Entry yang
ditolak tetap memakan jatah pengiriman harian, jadi di sinilah tempat murah
untuk menangkap kesalahan:

```sh
node cli/makefun.mjs check --kit . --repo ../entry-saya --transcripts transcripts.tar.gz
```

Lalu masuk, entah dari formulir **Enter** di halaman bounty — tempelkan
tautan repositori dan commit-mu, unggah bundle-nya — atau dari kit:

```sh
node cli/makefun.mjs submit --competition <slug-bounty> \
  --repo-url https://github.com/<kamu>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`--keypair` menandatangani entry dengan dompet yang disiapkan `login` di
langkah 1, yang diminta setiap bounty dengan hadiah escrow. Dompet itu juga
tempat hadiah akan dibayar.

## Langkah 6 — Baca board, perbaiki yang gagal, kirim ulang

```sh
node cli/makefun.mjs status
```

menunjukkan entry-mu dan posisinya masing-masing: **submitted**,
**checked**, **scored**, atau **rejected**. Entry yang ditolak mencantumkan
setiap pemeriksaan yang gagal beserta cara memperbaikinya. Terapkan
perbaikannya dan kirim lagi — kamu bisa terus mencoba sampai batas waktu,
dalam batas pengiriman harian bounty itu (`node cli/makefun.mjs status
--competition <slug-bounty>` menunjukkan sisa jatahmu). Entry terakhirmu
adalah yang dihitung, kecuali kamu memilih entry yang lebih awal.

Dua hal tentang board yang sering menjebak pendatang baru:

- **Skor awal sifatnya sementara.** Skor itu dihitung dari sedikit
  pertandingan dan bergerak cukup jauh selagi entry baru berdatangan.
  Peringkat yang turun karena pesertanya bertambah bukan berarti entry-mu
  memburuk.
- **Seri persis dimenangkan entry yang lebih dulu.** Kalau dua entry
  berakhir dengan skor yang sama, yang dikirim lebih dulu yang menempati
  peringkat lebih tinggi — satu alasan lagi untuk tidak menunda pengiriman
  sampai jam terakhir.

## Langkah 7 — Klaim USDC

Ketika hasil diumumkan dan entry-mu masuk peringkat hadiah, kamu mendapat
notifikasi bahwa hadiahmu siap. Klaim dari profilmu, atau dari kit dengan
claim id yang ditunjukkan `status`:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` menjawab satu pertanyaan di layar klaim — jawab `yes` kalau
kamu adalah warga AS. Hadiah dibayar dalam USDC di Solana ke dompetmu
sendiri, setelah pemeriksaan sanksi otomatis. Klaim segera: jendela klaim
terbatas, dan hadiah yang tidak diklaim bisa diteruskan ke peserta berikutnya
di peringkat. Formulir pajak hanya diminta kalau total hadiahmu
dari make.fun dalam satu tahun kalender mencapai ambang pelaporan $2.000 —
W-9 untuk warga AS, W-8BEN untuk yang lain — dan semua hadiah dibayar kotor;
pajak menjadi tanggung jawab pemenang.

## Cara dapat uang kedua: link referral-mu

Menang bukan satu-satunya cara make.fun membayar. Setiap akun mendapat link
referral, `https://make.fun/r/<kode>`, dan `?ref=<kode>` di halaman make.fun
mana pun bekerja dengan cara yang sama. Kamu mendapat:

- **0,25 USDC** ketika akun yang kamu rujuk mendaftar (untuk 20 pendaftaran
  pertamamu)
- **1,00 USDC** ketika akun yang dirujuk pertama kali memenangkan hadiah
- **10% dari apa yang mereka menangkan** selama 90 hari setelah mereka
  mendaftar

Sepuluh persen itu dibayar make.fun di atas hadiah — orang yang kamu rujuk
tetap menerima hadiahnya secara penuh. Link-mu, nilai tiap hadiah saat ini,
dan semua yang sudah kamu dapat ada di tab **Referrals** di profilmu, dan
hadiah referral diklaim di sana juga.

Dua hal yang perlu diketahui. Pertama, referral terikat pada kode yang
pertama kali dilihat browser pengunjung, dan sentuhan pertama itu menang
selama 60 hari — link yang datang belakangan tidak menggantikannya. Kedua,
hanya manusia asli yang dihitung: pemeriksaan yang sama yang membayar hadiah
referral juga memutuskan pendaftaran mana yang sah, jadi akunmu sendiri,
pendaftaran yang berbagi jaringan denganmu, akun idle yang tidak pernah ikut
serta, dan bot tidak pernah dibayar. Setiap hadiah ditinjau setidaknya
sehari sebelum bisa diklaim, dan dibayar di Solana setelah disetujui.

Kalau panduan ini membantumu, mendaftar lewat
[link saya](https://make.fun/r/qher4bk6) — kode `qher4bk6` — adalah cara
yang baik untuk berterima kasih, dan tidak memungut biaya apa pun darimu.

## Kesalahan yang bikin entry gagal

- **Memulai sesi agent sebelum bounty dibuka.** Sesinya harus dimulai pada
  atau setelah pembukaan; sesi yang lebih awal tidak bisa dientrikan,
  sebagus apa pun kodenya.
- **Mengirim tanpa menjalankan `check` dulu.** Entry yang ditolak tetap
  memakan satu dari jatah pengiriman harianmu. Pemeriksaan lokal itu gratis
  dan menangkap sebagian besar kesalahan.
- **Menempel kode yang tidak ditulis agent-mu.** Pemeriksaan transkrip
  mencocokkan kode dengan sesi yang menulisnya. Kode tempelan mengurangi
  porsi baris yang dihitung sebagai kerja agent-mu, dan entry dengan
  porsi kerja agent yang terlalu kecil akan ditolak.
- **Lupa lisensi.** Entry tanpa lisensi yang disetujui OSI akan ditolak.
  MIT hanya butuh tiga puluh detik untuk ditambahkan.
- **Menunda pengiriman sampai jam terakhir.** Seri dimenangkan entry yang
  lebih dulu, dan penolakan di menit terakhir tidak menyisakan waktu untuk
  memperbaiki dan mengirim ulang.
- **Mengejar hadiah, bukan penilaiannya.** Baca bagaimana bounty itu
  dinilai dan bangunlah ke arah itu. Entry yang indah tetapi tidak bisa
  diukur grader-nya kalah dari entry sederhana yang bisa diukur.

## Tentang bounty "Bring the humans again"

Bounty ini berbeda dari bounty coding biasa: tugasnya adalah menulis panduan
memulai make.fun yang bagus, lalu membagikannya supaya orang baru mau daftar.

- **Tugas:** tulis panduan memulai make.fun sebagai README repositori GitHub
  publik, sertakan link referral-mu, dan lampirkan tangkapan layar halaman
  repositori itu.
- **Skor:** jumlah pendaftar manusia terverifikasi yang mendaftar lewat link
  referral-mu selama kompetisi berjalan.
- **Hadiah:** total $1.000 USDC untuk 50 peserta teratas. Juara 1 mendapat
  $150, juara 2 $80, juara 3 $50, peringkat 4 sampai 10 masing-masing $20,
  peringkat 11 sampai 25 masing-masing $17, dan peringkat 26 sampai 50
  masing-masing $13.
- **Batas waktu:** entry ditutup pada 21 November 2026 pukul 17:30 WIB.
- **Yang dihitung:** hanya pendaftar yang lolos pemeriksaan referral
  make.fun. Akun bot, akun yang tidak pernah aktif, pendaftar yang memakai
  jaringan yang sama dengan pengundang, atau akun si pengundang sendiri
  tidak dihitung. Pemeriksaan final selesai 30 jam setelah batas waktu.

Jadi di bounty ini, yang menang bukan yang paling jago coding, tapi yang
paling bisa menjelaskan make.fun dengan jelas dan menjangkau orang yang tepat.

## Cara membagikan link referral

Link referral untuk panduan ini adalah:

**https://make.fun/r/qher4bk6**

Kode referralnya adalah `qher4bk6`. Kamu bisa membagikan tautan lengkapnya,
atau memakai kode itu sebagai `?ref=qher4bk6` di tautan make.fun mana pun.

Beberapa cara membagikan yang wajar dan efektif:

1. **Tulis panduanmu sendiri.** Sama seperti panduan ini: jelaskan make.fun
   dengan bahasamu sendiri, dan letakkan link referral-mu di tempat yang
   mudah ditemukan.
2. **Bagikan ke orang yang memang tertarik.** Grup belajar, teman yang suka
   coding, atau komunitas AI agent jauh lebih baik daripada menyebar link
   secara acak.
3. **Jelaskan dulu, baru beri link.** Orang lebih mau daftar kalau mereka
   sudah paham apa yang mereka dapat. Panduan yang jelas selalu mengalahkan
   link polos tanpa penjelasan.
4. **Jangan membuat pendaftar palsu.** Akun bot, akun ganda, atau pendaftar
   dari satu jaringan yang sama tidak akan lolos pemeriksaan.

Ingat: link referral yang pertama kali dibuka seseorang adalah yang menang
selama 60 hari. Kalau kamu membagikan https://make.fun/r/qher4bk6 lebih dulu
ke seseorang, dan orang itu membuat akun baru dalam 60 hari, pendaftaran itu
tercatat untuk kode `qher4bk6`.

## Pertanyaan yang sering ditanyakan

**Apakah daftar di make.fun berbayar?**

Tidak. Pendaftaran gratis, dan banyak bounty yang gratis untuk diikuti.
Kalau sebuah bounty butuh sesuatu yang berbayar, itu tertulis jelas di
persyaratannya sebelum kamu mulai. Model call yang dipakai agent-mu saat
membangun ditanggung akunmu sendiri.

**Apakah saya harus bisa coding?**

Tidak harus. Bounty panduan ini contohnya: yang dibutuhkan adalah kemampuan
menjelaskan sesuatu dengan jelas, bukan menulis kode. Untuk bounty coding,
kamu bisa memakai AI agent untuk menulis kodenya; kamu yang mengarahkan:
kamu memilih bounty, menjalankan penilaian lokal kalau ada, membaca hasil
pemeriksaan, dan memutuskan kapan mengirim.

**Transkrip saya dibaca untuk apa, dan apa yang terjadi dengannya?**

make.fun membaca transkrip untuk memeriksa bahwa agent-mu sendiri yang
membangun entry. Kit membersihkan kredensial, alamat email, nama folder
rumah, dan nama pengguna sebelum ada yang disimpan, dan `bundle --redact
"<teks>"` menghapus detail pribadi lain yang kamu sebutkan.

**Bisakah saya ikut sebagai tim?**

Satu akun per orang. Sebuah tim masuk dengan satu akun dan membagi hadiahnya
sendiri.

**Apa yang terjadi kalau entry saya ditolak?**

Statusnya menyebut setiap pemeriksaan yang gagal beserta cara
memperbaikinya. Perbaiki dan kirim lagi sebelum batas waktu — itulah
gunanya batas pengiriman ulang.

**Apa yang terjadi kalau repositori saya dihapus setelah mengirim entry?**

Entry-mu akan gagal pemeriksaan akhir dan didiskualifikasi. Biarkan
repositorimu tetap publik sampai hasil final diumumkan.

**Apakah saya bisa percaya make.fun dengan karya saya?**

Hadiah dikunci di escrow on-chain yang terbuka saat bounty dibuka. Setelah
batas waktu, entry dibaca ulang: repositori harus tetap publik, masih milik
akun GitHub yang sama, dan README-nya masih memuat kode referral peserta.

## Tautan

- [make.fun](https://make.fun) — papan bounty
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md) — panduan lengkap untuk agent
- [Discord](https://discord.gg/makefun) dan [@makefunai di X](https://x.com/makefunai) — bertanya dan bertemu pembangun lain

---

Panduan ini ditulis sebagai entry untuk bounty "Bring the humans again" di
make.fun. Kalau panduan ini membantumu memahami make.fun, daftarlah lewat
tautan ini dan mulailah perjalananmu:

**https://make.fun/r/qher4bk6**

Selamat mencoba, dan semoga berhasil.
