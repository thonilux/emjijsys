# 🏗️ EMJIJSYS - Analisis V2 Arsitektur, Struktur, MEP, Psikologi Ruang

Sumber utama: `D:\cad\emjijsys-Model.pdf`  
Referensi tambahan: `D:\cad\emjijsys-antigravity.md`  
Dokumen sebelumnya: `D:\cad\emjijsys-analasis.md`  
Preview gambar: `D:\cad\codex_redraw_floorplan_lantai1\docs\emjijsys_model_page1.png`  
Objek kajian: ruko-hunian 2 lantai PT. EMJI JAYA  
Status: analisis pra-gambar kerja, belum menggantikan perhitungan struktur/MEP final

## ⚡ 0. TL;DR Gen-Z Friendly

Versi pendeknya: desain ini sudah punya vibes yang cukup bagus buat ruko + hunian. Lantai 1 clear untuk usaha, lantai 2 mulai terasa sebagai rumah yang privat. Yang masih PR bukan ide ruangnya, tapi bagian teknis: struktur, balok, area basah, ventilasi, dan MEP. Jadi jangan buru-buru styling dulu ya, fondasinya dikunci dulu ✅

| Area | Vibes Sekarang | Yang Harus Diberesin |
|---|---|---|
| 🏪 Lantai 1 | toko/open space fleksibel | akses hunian jangan terlalu campur toko |
| 🪜 Tangga | jadi transisi kerja -> pulang | hitung step, void, headroom, balok tepi |
| 🏠 Lantai 2 | zoning sudah kebaca | koridor dan pintu jangan tabrakan |
| 🧺 Service area | laundry + KM sudah efisien | shaft, floor drain, exhaust wajib |
| 🛋️ Ruang keluarga + balkon | ini bagian paling healing | shading, railing, waterproofing |
| 🛠️ Ruang kerja | cocok buat soldering/tools | fume extractor + listrik aman, serius ini |
| 🧱 Struktur | grid kolom terlihat niat | overlay balok sebelum dinding dikunci |
| 📐 Gambar kerja | sudah ada title block | lineweight, skala, grid, elevasi perlu rapi |

Prioritas next move:

1. Tambahkan grid resmi `1-3` dan `A-E`.
2. Overlay balok-kolom di lantai 2.
3. Rapikan pintu, koridor, dan area toilet.
4. Kunci shaft plumbing + floor drain.
5. Baru lanjut interior/fasad biar tidak bolak-balik revisi 🔁

## 🧾 1. Executive Summary

Denah `emjijsys-Model.pdf` menunjukkan konsep ruko-hunian yang sudah memiliki arah desain kuat: lantai 1 dipertahankan sebagai toko/open space, lantai 2 dikembangkan sebagai hunian privat lengkap dengan ruang tamu, dapur kering, laundry, kamar mandi, mushola, ruang keluarga, ruang kerja, kamar tidur utama, kamar tidur tambahan, dan balkon.

Secara arsitektur, keputusan terbesar yang sudah tepat adalah pemisahan fungsi komersial dan hunian melalui lapisan ruang. Lantai 1 berorientasi pada fleksibilitas usaha, sedangkan lantai 2 membentuk gradasi dari publik terbatas ke privat. Secara psikologis, ini penting karena rumah di atas ruko sering mengalami konflik antara suasana kerja dan suasana pulang.

Secara struktur, gambar menunjukkan pola kolom yang relatif disiplin, kemungkinan 3 kolom arah lebar dan 5 baris arah panjang. Ini baik untuk bangunan 8.80 m x 16.00 m. Namun denah lantai 2 belum boleh dikunci sebelum dinding, kamar mandi, laundry, tangga, dan balkon dioverlay terhadap balok.

Secara MEP, pengelompokan kamar mandi dan laundry di area belakang-tengah adalah keputusan efisien. Tetapi gambar belum menunjukkan shaft plumbing, jalur air bersih, air kotor, air bekas, floor drain, exhaust, pembagian sirkuit listrik, dan kebutuhan khusus ruang kerja soldering.

Kesimpulan utama: desain ini layak dilanjutkan, tetapi tahap berikutnya harus berupa koordinasi teknis, bukan menambah ruang baru lagi. Urutan paling aman adalah grid -> struktur -> plumbing -> sirkulasi pintu -> bukaan/ventilasi -> interior. Singkatnya: idenya sudah oke, tinggal jangan sampai teknisnya nge-prank di lapangan ⚠️

## 📌 2. Data Dasar dari PDF dan Referensi Tambahan

| Item | Data |
|---|---:|
| Lokasi referensi | Desa Genggong Pojok, Kel. Delingan, Kec. Karanganyar, Kab. Karanganyar, Jawa Tengah |
| Luas lahan | +/- 226 m2 |
| Lebar lahan | 9.80 m |
| Perkiraan panjang lahan | +/- 23.06 m |
| Lebar bangunan | 8.80 m |
| Panjang bangunan utama | 16.00 m |
| Footprint bangunan | 140.80 m2 |
| Area parkir depan | +/- 9.80 m x 4.00 m = +/- 39.20 m2 |
| Sisa belakang | +/- 3.06 m |
| Sisa samping | +/- 0.50 m kiri dan +/- 0.50 m kanan bila bangunan simetris |
| Fungsi lantai 1 | toko / open space komersial |
| Fungsi lantai 2 | hunian privat |
| Orientasi gambar | atas = utara, kanan = timur, bawah = selatan, kiri = barat |

Catatan penting: angka di atas perlu diverifikasi langsung pada DWG/DXF menggunakan command `DIST`, karena PDF dapat berubah skala akibat plot. Jangan percaya PDF 100% untuk ukuran final; enak buat baca cepat, tapi belum tentu aman buat tukang ⚠️

## 📊 3. Skor Audit V2

Skor ini bukan nilai mutlak, tetapi cara cepat membaca tingkat kesiapan desain. Anggap ini raport desain, bukan vonis hidup-mati 🧭

| Aspek | Skor | Interpretasi |
|---|---:|---|
| Konsep arsitektur | 8/10 | Zoning sudah kuat, masih perlu perapian sirkulasi |
| Psikologi ruang | 8/10 | Hierarki privasi baik, arrival perlu diperhalus |
| Struktur konseptual | 6.5/10 | Grid kolom terbaca, balok dan void belum lengkap |
| MEP konseptual | 5.5/10 | Cluster plumbing baik, gambar teknis belum ada |
| Kenyamanan termal | 6/10 | Balkon membantu, area tengah rawan gelap/pengap |
| Gambar kerja | 4.5/10 | Title block dan denah ada, detail teknis belum cukup |
| Kesiapan konstruksi | 4/10 | Perlu gambar struktur, MEP, dan detail arsitektur |

## 📏 4. Prinsip Dasar yang Harus Dipakai

### 4.1 Skala Gambar

| Jenis Gambar | Skala Rasional |
|---|---:|
| Site plan | 1:500 atau 1:1000 |
| Denah lantai 1 dan lantai 2 | 1:100 untuk A3, 1:50 untuk detail |
| Tampak dan potongan | 1:100 atau 1:50 |
| Detail tangga | 1:20 atau 1:10 |
| Detail kamar mandi | 1:20 atau 1:10 |
| Detail railing/balkon | 1:20, 1:10, atau 1:5 |

### 4.2 Grid dan Elevasi

Grid yang disarankan:

| Arah | Grid | Jarak |
|---|---|---:|
| Lebar bangunan | 1-2-3 | 4400 mm + 4400 mm |
| Panjang bangunan | A-B-C-D-E | 4000 mm + 4000 mm + 4000 mm + 4000 mm |

Elevasi konseptual:

| Elemen | Elevasi |
|---|---:|
| Lantai 1 utama | +/-0.00 |
| Area parkir/teras | -50 mm sampai -150 mm dari lantai dalam |
| Kamar mandi/laundry | turun 20-30 mm dari lantai sekitar |
| Lantai 2 | +3600 mm bila floor-to-floor 3600 mm |
| Bordes tangga tengah | +1800 mm bila 20 riser @180 mm |
| Balkon | turun 20-30 mm dari ruang dalam |

### 4.3 Lineweight

| Elemen | Lineweight |
|---|---:|
| Dinding terpotong | 0.35-0.50 mm |
| Kolom beton | 0.40-0.60 mm |
| Dinding partisi | 0.18-0.25 mm |
| Pintu, jendela, railing, tangga | 0.13-0.18 mm |
| Sanitary dan furniture | 0.09-0.13 mm |
| Dimensi dan teks kecil | 0.09-0.13 mm |
| Grid samar | 0.05-0.09 mm |

## 🧭 5. Analisis Makro Site dan Massa

Bangunan memiliki karakter bidang memanjang dengan lebar efektif 8.80 m dan panjang bangunan 16.00 m. Proporsi seperti ini cocok untuk ruko karena bagian depan dapat dipakai sebagai area publik/komersial, sementara bagian belakang dan lantai atas dapat dipakai untuk servis dan hunian.

Dengan lahan +/-226 m2 dan footprint +/-140.80 m2, rasio dasar bangunan sekitar 62%. Ini masih masuk akal secara fungsi ruko, tetapi tetap perlu dicek terhadap aturan lokal seperti KDB, KLB, GSB, dan ketentuan campuran komersial-hunian.

Sisa samping +/-500 mm bukan ruang manusia yang nyaman. Ia lebih tepat diperlakukan sebagai:

- ruang talang dan pembuangan air hujan;
- celah maintenance;
- ruang ventilasi terbatas;
- area teknis untuk pipa kecil bila dibutuhkan.

Karena sisi depan diasumsikan selatan, balkon depan tidak menerima matahari sore barat secara langsung, tetapi tetap perlu shading karena panas jalan dan pantulan permukaan keras bisa signifikan.

## 🏪 6. Analisis Lantai 1

### 6.1 Fungsi Open Space

Lantai 1 sebagai toko/open space adalah keputusan tepat untuk ruko. Ruang ini memberi fleksibilitas yang tinggi: bisa menjadi toko, showroom, workshop ringan, area display, gudang temporer, atau ruang operasional usaha.

Kekuatan:

- Area utama lapang dan mudah diubah.
- Kolom perimeter tidak terlalu mengganggu fungsi.
- Area parkir depan memberi buffer dari jalan.
- Tangga di belakang menjaga lantai 2 tetap lebih privat dari pengunjung toko.

Kelemahan:

- Akses hunian belum benar-benar independen.
- Toilet/service lantai 1 belum dijelaskan lengkap.
- Partisi belakang belum jelas fungsinya.
- Belum terlihat arah bukaan semua pintu.
- Belum ada jalur evakuasi dan titik APAR.

### 6.2 Akses Hunian vs Akses Toko

Ini isu penting. Jika lantai 2 hanya dipakai keluarga pemilik, akses lewat toko masih bisa diterima. Tetapi jika toko melibatkan karyawan, pelanggan, atau jam operasional panjang, penghuni akan kehilangan privasi.

Pilihan desain:

| Opsi | Dampak |
|---|---|
| Tangga tetap di belakang dan akses lewat toko | Ruang toko maksimal, privasi hunian rendah |
| Tambah koridor akses privat di salah satu sisi dalam toko | Privasi naik, toko sedikit berkurang |
| Buat pintu/kunci transisi sebelum tangga | Solusi menengah, lebih aman secara psikologis |
| Pisahkan entrance hunian dari depan | Paling privat, tapi perlu studi fasad dan lebar lahan |

Rekomendasi V2: minimal buat "threshold" sebelum tangga, berupa pintu, partisi, atau kabinet yang menandai batas antara area usaha dan area rumah. Ini semacam tombol mental: dari mode kerja masuk mode pulang 🏠

### 6.3 Kolom Tengah sebagai Elemen Interior

Kolom tengah tidak harus dianggap gangguan. Dalam desain interior toko, kolom bisa menjadi titik:

- signage internal;
- display island;
- rak pendek;
- titik CCTV;
- titik lampu track;
- pembagi visual antara kasir, display, dan area kerja.

Namun kolom harus diselaraskan dengan layout toko. Jangan biarkan kolom berdiri acak tanpa fungsi visual.

### 6.4 Parkir dan Drainase Depan

Area depan +/-4.00 m cukup untuk parkir mobil compact atau beberapa motor. Tetapi perlu detail teknis:

- slope 1-2% ke saluran depan;
- trench drain sebelum ambang pintu toko;
- beda level 50-150 mm antara parkir dan lantai toko;
- gate minimal 3000 mm, lebih nyaman 3500 mm;
- permukaan anti-slip.

## 🏠 7. Analisis Lantai 2

Lantai 2 sudah membentuk hunian yang cukup matang. Denah ini bukan sekadar membagi kamar, tetapi sudah mencoba membentuk alur sosial: tangga -> ruang tamu -> dapur kering -> ruang keluarga/kamar. Ini sudah bukan asal sekat, tapi sudah mulai punya cerita ruang ✨

### 7.1 Zoning

| Zona | Ruang | Evaluasi |
|---|---|---|
| Publik terbatas | Tangga, ruang tamu | Tepat sebagai area penerima |
| Semi-publik | Dapur kering, meja makan | Cocok sebagai ruang interaksi ringan |
| Servis | Laundry, kamar mandi | Efisien karena terkumpul |
| Tenang/spiritual | Mushola | Baik jika tidak jadi jalur lewat |
| Keluarga | Ruang keluarga, balkon | Lokasi depan memberi rasa lega |
| Privat | Ruang kerja, kamar utama, kamar tidur | Cukup terlindungi dari tamu |

### 7.2 Sirkulasi

Titik paling sensitif adalah area sekitar kamar mandi, pintu ruang kerja, dan koridor menuju ruang keluarga/kamar. Jika pintu terlalu banyak bertemu pada satu area kecil, pengguna akan merasakan ruang sempit walaupun luas total cukup.

Standar yang perlu dikunci:

| Area | Minimum | Nyaman |
|---|---:|---:|
| Koridor utama | 900 mm | 1000-1200 mm |
| Area depan pintu toilet | 900 mm | 1100 mm |
| Jalur belakang kursi makan | 800 mm | 900-1000 mm |
| Jalur depan lemari | 800 mm | 900 mm |
| Jalur laundry | 800 mm | 900-1000 mm |

Rekomendasi: lakukan simulasi swing pintu dalam CAD. Pintu KM, pintu ruang kerja, pintu kamar utama, dan pintu kamar tidur tidak boleh saling mengganggu. Kalau pintu tabrakan, tiap hari bakal terasa ngeselin walau denahnya terlihat bagus di kertas 🚪

### 7.3 Ruang Tamu

Ruang tamu dekat tangga adalah keputusan psikologis yang bagus. Ia bekerja sebagai ruang penerima singkat dan filter sosial. Tamu berhenti di sini, tidak otomatis masuk ke ruang keluarga atau kamar. Jadi rumah tetap punya privacy shield 🛡️

Yang perlu diperhatikan:

- Jangan sampai pintu kamar mandi menjadi pandangan pertama dari ruang tamu.
- Jangan biarkan dapur kering terlihat terlalu "operasional" dari sofa tamu.
- Jika ruang tamu minim bukaan, tambahkan pencahayaan hangat dan ventilasi mekanis.
- Tambahkan foyer kecil: rak sepatu, console table, artwork, atau partisi ringan.

### 7.4 Dapur Kering dan Meja Makan

Dapur kering dekat ruang tamu cocok jika digunakan sebagai pantry ringan, bukan dapur basah berat. Secara sosial, posisinya baik karena menjadi ruang transisi antara tamu dan keluarga.

Dimensi:

| Komponen | Ukuran |
|---|---:|
| Kedalaman kabinet bawah | 600 mm |
| Kedalaman kabinet atas | 300-350 mm |
| Panjang counter minimum | 1800 mm |
| Panjang counter nyaman | 2400-3000 mm |
| Meja makan 4 orang | +/-800 x 1200 mm |
| Clear area belakang kursi | minimal 800 mm |

Rekomendasi:

- Gunakan kabinet tertutup agar tidak berantakan secara visual.
- Tambahkan backsplash mudah dibersihkan.
- Siapkan cooker hood/exhaust bila ada kompor.
- Sediakan stopkontak khusus untuk dispenser, microwave, rice cooker, dan kulkas kecil.

### 7.5 Laundry dan Service Room

Laundry di dekat tangga adalah strategi yang efisien. Karena user sebelumnya mengarah ke konsep service room/janitor, area ini sebaiknya tidak hanya menjadi tempat mesin cuci, tetapi menjadi ruang servis rumah. Ini area backstage rumah: kecil, tapi ngaruh banget ke kerapian harian 🧺

Program ideal:

- mesin cuci 600 x 600 mm;
- utility sink 450-600 mm;
- kabinet deterjen/chemical tertutup;
- rak alat pel/sapu;
- keranjang laundry;
- area jemur gantung;
- floor drain;
- exhaust fan;
- water stop pada pintu.

Detail wajib:

| Item | Rekomendasi |
|---|---:|
| Lebar nyaman service room | 1500 mm |
| Panjang nyaman | 3000-4000 mm |
| Slope lantai | 1-2% ke floor drain |
| Turun lantai | 20-30 mm |
| Tinggi keramik dinding area basah | minimal 1200 mm, ideal full height dekat sink |
| Stopkontak mesin cuci | grounded, aman dari cipratan |

### 7.6 Kamar Mandi Umum dan Kamar Mandi Privat

Dua kamar mandi berdekatan membuat plumbing lebih efisien. Namun area ini harus sangat hati-hati dari sisi privasi, bau, kelembapan, dan sirkulasi.

Ukuran ergonomis:

| Elemen | Minimum | Nyaman |
|---|---:|---:|
| Pintu KM | 700 mm | 750-800 mm |
| Shower | 800 x 800 mm | 900 x 900 atau 900 x 1200 mm |
| Area kloset | 750 x 1200 mm | 800 x 1300 mm |
| Area wastafel | 600 x 800 mm | 700 x 900 mm |
| Lebar KM kecil | 1200 mm | 1500 mm |

Catatan arsitektur:

- Pintu toilet jangan menghadap langsung ruang tamu/meja makan.
- Bila memungkinkan, buat dinding transisi atau niche kecil.
- Pintu KM lebih aman membuka keluar atau memakai sliding bila ruang sangat kecil.
- KM privat harus terasa privat walaupun tidak berada di dalam kamar.

Catatan teknis:

- Waterproofing lantai dan dinding wajib.
- Floor drain wajib.
- Exhaust fan wajib jika tidak ada jendela langsung.
- Pipa WC sebaiknya dekat shaft dan minim belokan.

### 7.7 Mushola

Mushola ukuran target 3000 x 2200 mm sudah baik. Dengan ukuran ini, ruang bisa dipakai 2-3 orang shalat dan masih punya storage kecil. Ukuran ini sudah kalem dan tidak maksa 🤲

Aspek psikologis:

- Mushola berperan sebagai anchor emosional rumah.
- Ia memberi jeda tenang di tengah rumah.
- Jangan jadikan mushola jalur sirkulasi.
- Jangan letakkan rak/lemari besar mengganggu arah kiblat.

Saran desain:

- Gunakan partisi rendah atau kisi agar tetap terang.
- Sediakan rak 300-350 mm untuk sajadah/mukena.
- Pencahayaan lembut, tidak langsung menyilaukan.
- Jika dekat ruang keluarga, beri batas akustik ringan agar ibadah tidak terganggu TV.

### 7.8 Ruang Keluarga dan Balkon

Ruang keluarga dekat balkon adalah salah satu keputusan paling kuat dalam denah ini. Secara psikologis, ini memberi ruang pemulihan setelah aktivitas kerja/toko. Balkon menjadi "ruang napas", bukan hanya ornamen. Ini bisa jadi spot paling waras di rumah 🌿

Ukuran balkon yang sudah dipilih sebelumnya, 3000 x 1500 mm, cukup untuk dua orang duduk santai.

Detail balkon:

| Item | Rekomendasi |
|---|---:|
| Lebar balkon duduk | 1500 mm |
| Panjang untuk 2 orang | 3000 mm |
| Tinggi railing | 1000-1100 mm |
| Slope lantai | 1-2% |
| Turun lantai | 20-30 mm dari ruang dalam |
| Floor drain | wajib |
| Waterproofing | wajib, naik ke dinding/parapet |

Saran ruang keluarga:

- Sofa menghadap ke arah yang tetap memberi kontrol visual ke koridor dan balkon.
- Hindari sofa membelakangi total jalur masuk.
- Gunakan storage tertutup agar area keluarga tidak terasa penuh.
- Beri shading pada balkon agar panas jalan tidak masuk berlebihan.

### 7.9 Ruang Kerja

Ruang kerja harus dipahami sebagai ruang semi-teknis karena user menyebut soldering tools dan rak alat. Ini bukan sekadar meja laptop. Ini mini-lab, jadi safety-nya jangan cuma modal feeling 🛠️

Kebutuhan:

| Kebutuhan | Rekomendasi |
|---|---|
| Meja solder | 700-800 mm dalam, 1600-2400 mm panjang |
| Rak alat | 350-450 mm dalam |
| Jalur kursi | minimal 900 mm |
| Exhaust | fume extractor ducted ke luar |
| Stopkontak | banyak, grounded, dengan sirkuit khusus |
| Pencahayaan | general 4000K + task light 4000-5000K |
| Storage | kombinasi terbuka dan tertutup |
| Safety | APAR kecil, permukaan meja tahan panas |

Aspek psikologis:

- Posisi meja idealnya diagonal terhadap pintu, sehingga pengguna bisa melihat orang masuk.
- Area kerja jangan langsung terlihat dari ruang tamu agar tidak terasa berantakan.
- Rak alat tinggi sebaiknya di dinding solid.
- Bila ruang dipakai lama, sediakan jendela atau ventilasi mekanis yang tidak mengganggu AC.

### 7.10 Kamar Tidur Utama

Kamar tidur utama berada cukup privat. Ini baik untuk kualitas istirahat.

Prinsip ranjang:

- Headboard di dinding solid.
- Tidak sejajar langsung dengan pintu.
- Pintu terlihat secara diagonal dari kasur.
- Hindari kepala ranjang berbagi dinding langsung dengan shower/WC.
- Wardrobe dapat menjadi buffer suara.

Ukuran nyaman:

| Elemen | Ukuran |
|---|---:|
| Kasur queen | 1600 x 2000 mm |
| Kasur king | 1800 x 2000 mm |
| Samping kasur | minimal 600 mm, nyaman 700-800 mm |
| Depan kasur | minimal 700 mm |
| Lemari | 600 mm dalam |
| Jalur depan lemari | 800-900 mm |

### 7.11 Kamar Tidur Tambahan

Kamar tidur tambahan dapat menjadi kamar anak, kamar tamu keluarga, atau kamar cadangan. Karena dekat fasad, hal yang paling penting adalah kontrol panas, kebisingan, dan privasi jendela.

Saran:

- Ukuran bersih ideal minimal 3000 x 3200 mm.
- Tambahkan shading pada jendela.
- Hindari ranjang langsung terlihat dari balkon/jalan.
- Pastikan posisi AC tidak meniup langsung ke kepala ranjang.

## 🧱 8. Analisis Struktur

### 8.1 Sistem Struktur yang Terbaca

Referensi tambahan menyebut sistem 15 titik kolom dalam konfigurasi 3 x 5. Ini cocok dengan pembacaan visual: 3 grid arah lebar dan 5 baris arah panjang. Grid ini adalah kerangka badan bangunan, jadi layout ruang harus hormat sama dia 🧱

Skema:

| Arah | Modul | Bentang |
|---|---|---:|
| Lebar | 2 modul | 4400 mm + 4400 mm |
| Panjang | 4 modul | 4000 mm x 4 |
| Jumlah titik kolom | 15 titik | 3 x 5 |

Struktur seperti ini relatif rasional untuk bangunan 2 lantai dan dapat disiapkan untuk 3 lantai jika pondasi, kolom, balok, dan pelat dihitung sejak awal.

### 8.2 Kolom dan Pondasi

Referensi tambahan menyebut:

- 4 kolom utama sudut;
- 11 kolom antara;
- kolom utama sudut kemungkinan 400 x 400 mm;
- kolom antara kemungkinan 350 x 350 mm;
- pondasi cakar ayam pada kolom utama;
- catatan struktur dipersiapkan untuk tumbuh 3 lantai.

Rekomendasi V2:

| Elemen | Ukuran Konseptual | Catatan |
|---|---:|---|
| Kolom utama/sudut | 400 x 400 mm | masuk akal untuk rencana tumbuh, tetap wajib hitung |
| Kolom antara | 350 x 350 mm | cek rasio tulangan dan beban |
| Balok induk | 250 x 500 mm | konseptual awal, final ikut bentang |
| Balok anak | 200 x 350 mm | untuk dinding/partisi yang tidak jatuh di grid |
| Pelat lantai | 120 mm | tergantung bentang dan beban |
| Dinding bata + plester | minimal 150 mm | dinding lantai 2 harus di atas balok |

### 8.3 Titik Kritis Struktur

| Titik | Risiko | Rekomendasi |
|---|---|---|
| Void tangga | retak sudut void, pelat lemah | balok tepi void di semua sisi |
| Kamar mandi lantai 2 | beban screed-air-keramik, risiko bocor | balok pendukung + waterproofing |
| Laundry | getaran mesin cuci, area basah | balok cukup, pad anti-getar |
| Balkon | kantilever, air hujan, railing | balok balkon + tulangan negatif |
| Dinding kamar | beban garis di atas pelat | letakkan di atas balok/balok anak |
| Kolom tengah ruang keluarga/mushola | gangguan ruang vs tumpuan struktur | integrasikan sebagai elemen interior |

### 8.4 Prinsip Tulangan Umum

Catatan ini bukan perhitungan final, tetapi arah koordinasi awal dengan engineer:

- Balok induk harus menerus antar kolom.
- Balok anak dipakai untuk mendukung dinding yang tidak tepat di grid.
- Balok tepi void tangga harus mengikat bukaan pelat.
- Balkon memerlukan tulangan atas/negatif di area tumpuan.
- Area kamar mandi memerlukan kontrol retak dan waterproofing yang baik.
- Jika bangunan tumbuh 3 lantai, pondasi tidak boleh dihitung untuk 2 lantai saja.

## 🔌 9. Analisis MEP

### 9.1 Plumbing

Cluster laundry dan dua kamar mandi adalah keputusan benar. Ini mengurangi panjang pipa dan membuat perawatan lebih mudah. Ini keputusan yang lowkey pintar, karena pipa pendek biasanya berarti masalah lebih sedikit 💧

Shaft plumbing:

| Item | Rekomendasi |
|---|---:|
| Ukuran shaft minimum | 300 x 600 mm atau 400 x 400 mm |
| Akses panel | wajib di tiap lantai |
| Pipa WC | PVC 100-110 mm |
| Pipa air bekas | PVC 50-75 mm sesuai beban |
| Vent pipe | wajib naik ke atas atap |
| Floor drain | KM, laundry, balkon |

Catatan:

- Pipa WC jangan terlalu banyak belokan 90 derajat.
- Floor drain harus memiliki trap agar tidak bau.
- Pipa buangan AC jangan dibuang bebas ke balkon.
- Shaft sebaiknya berada di dekat cluster KM/laundry, bukan jauh dari toilet.

### 9.2 Elektrikal

Lantai 2 memerlukan pembagian sirkuit yang lebih rapi karena ada ruang kerja alat elektronik, laundry, AC, dan pantry.

Sirkuit disarankan:

| Sirkuit | Catatan |
|---|---|
| Lampu lantai 2 | terpisah dari stopkontak |
| Stopkontak umum | ruang tamu, ruang keluarga, kamar |
| AC kamar utama | dedicated |
| AC kamar tidur tambahan | dedicated |
| AC ruang kerja | dedicated |
| Ruang kerja/soldering | dedicated + grounding |
| Mesin cuci | dedicated + ELCB/RCD |
| Water heater jika ada | dedicated |
| Pantry | dedicated untuk microwave/rice cooker/dispenser |
| Area basah | ELCB/RCD 30 mA |

Titik minimal:

| Ruang | Stopkontak |
|---|---:|
| Ruang tamu | 3 titik |
| Dapur kering | 4 titik |
| Ruang keluarga | 4 titik |
| Ruang kerja | minimal 8 titik |
| Kamar utama | 4 titik |
| Kamar tidur tambahan | 3 titik |
| Laundry | 2 titik khusus |
| KM | 1 titik IP-rated bila perlu |

### 9.3 Ventilasi dan Exhaust

| Area | Risiko | Solusi |
|---|---|---|
| Laundry | lembap dan bau | exhaust fan / kisi / bukaan langsung |
| Kamar mandi | bau dan lembap | exhaust fan + floor drain trap |
| Dapur kering | uap dan bau | cooker hood/exhaust |
| Ruang kerja soldering | asap flux | fume extractor ducted |
| Koridor tengah | gelap/pengap | roster, skylight, atau bukaan atas |
| Tangga | chimney effect panas | bukaan atas dengan kontrol hujan/panas |

## 🧠 10. Psikologi Arsitektur

### 10.1 Hierarki Privasi

Denah lantai 2 sudah memiliki urutan psikologis yang sehat:

1. Tangga sebagai transisi dari toko ke rumah.
2. Ruang tamu sebagai area penerima.
3. Dapur kering/meja makan sebagai semi-publik.
4. Mushola dan ruang keluarga sebagai ruang tenang keluarga.
5. Kamar tidur dan ruang kerja sebagai zona privat.
6. Balkon sebagai ruang pelepas tekanan.

Ini sangat penting untuk ruko-hunian. Tanpa transisi seperti ini, penghuni akan terus merasa tinggal di area kerja. Capek mentalnya bisa numpuk pelan-pelan 🧠

### 10.2 Sense of Arrival

Momen tiba di lantai 2 harus dirancang. Saat penghuni naik tangga, ruang yang pertama muncul sebaiknya memberi rasa aman, terang, dan tertata. Ini bukan lebay, arrival itu ngaruh ke mood harian 💡

Rekomendasi:

- tambahkan foyer kecil di dekat ruang tamu;
- letakkan rak sepatu/console/artwork sebagai penanda pulang;
- hindari pintu toilet sebagai view utama;
- gunakan lampu hangat 2700-3000K di area tangga/arrival;
- buat tekstur atau warna berbeda dari lantai 1 agar mental berpindah dari kerja ke rumah.

### 10.3 Prospect and Refuge

Ruang keluarga dekat balkon memberi "prospect": cahaya, pandangan, dan rasa lega. Kamar tidur dan mushola memberi "refuge": tempat terlindung dan tenang. Kombinasi ini sehat untuk rumah keluarga.

Agar bekerja baik:

- ruang keluarga jangan terlalu tertutup;
- kamar tidur jangan terlalu terekspos;
- mushola jangan jadi lorong;
- ruang kerja punya posisi meja yang bisa melihat pintu;
- balkon cukup nyaman untuk benar-benar dipakai.

### 10.4 Dual Identity Stress

Ruko-hunian punya tekanan psikologis khas: pemilik tinggal di tempat yang sama dengan usaha. Jika batas ruang tidak jelas, pikiran sulit "pulang".

Mitigasi:

- buat pintu/partisi transisi sebelum tangga;
- bedakan material dan pencahayaan area hunian;
- hindari barang toko naik ke lantai 2;
- sediakan ruang keluarga dan balkon sebagai zona pemulihan;
- ruang kerja elektronik jangan bercampur dengan ruang keluarga.

### 10.5 Kesehatan Ruang Kerja

Ruang soldering punya risiko kesehatan. Secara desain, ini harus dianggap ruang kerja teknis.

Wajib:

- fume extractor;
- stopkontak grounded;
- meja tahan panas;
- APAR kecil;
- rak alat tertutup;
- cahaya kerja cukup;
- jalur kabel rapi;
- ventilasi yang tidak menyebarkan asap ke kamar.

## 🔥 11. Keselamatan, Kebakaran, dan Evakuasi

Referensi tambahan menyoroti bahwa aspek kebakaran belum terlihat. Untuk ruko, ini penting karena lantai 1 dapat menampung barang dagangan, kabel, pelanggan, dan aktivitas komersial. Bagian ini tidak estetik, tapi wajib banget 🔥

Checklist minimal:

- APAR lantai 1 dekat area toko.
- APAR lantai 2 dekat ruang kerja/pantry.
- Smoke detector dekat tangga, ruang keluarga, dan kamar.
- Jalur tangga bebas dari barang.
- Lampu tangga cukup terang.
- Stopkontak ruang kerja dan laundry tidak overload.
- ELCB/RCD untuk area basah.
- Titik kumpul atau arah evakuasi ditandai pada gambar.

Tangga tunggal masih umum untuk rumah 2 lantai, tetapi karena fungsi lantai 1 komersial, disiplin evakuasi dan deteksi asap menjadi lebih penting.

## 🔊 12. Akustik, Bau, dan Kelembapan

### 12.1 Akustik

Sumber suara:

- aktivitas toko lantai 1;
- tangga;
- mesin cuci;
- jalan depan;
- ruang keluarga/TV;
- ruang kerja alat elektronik.

Mitigasi:

- pintu tangga menuju lantai 2 dibuat cukup rapat;
- mesin cuci pakai anti-vibration pad;
- kamar tidur memakai pintu solid;
- wardrobe digunakan sebagai buffer;
- AC outdoor jangan dekat kamar tidur;
- ruang kerja diberi pintu bila aktivitasnya berisik.

### 12.2 Bau dan Kelembapan

Sumber risiko:

- kamar mandi;
- laundry;
- pantry;
- sepatu dekat tangga;
- asap soldering.

Mitigasi:

- floor drain dengan trap;
- exhaust KM dan laundry;
- kabinet sepatu berventilasi;
- cooker hood pantry;
- fume extractor ruang kerja;
- bukaan atau roster untuk area tengah.

## 🌿 13. Iklim, Cahaya, dan Keberlanjutan

Karanganyar relatif lebih sejuk dibanding kota dataran rendah yang sangat panas, tetapi bangunan ruko tetap rawan panas karena fasad, atap, dan area jalan.

Strategi:

| Strategi | Aplikasi |
|---|---|
| Pencahayaan alami | bukaan balkon, jendela ruang keluarga, roster area tengah |
| Ventilasi silang | hubungkan bukaan belakang/tangga dengan balkon depan |
| Shading | kanopi balkon, kisi fasad, tirai luar |
| Rainwater handling | talang kiri-kanan, floor drain balkon, saluran parkir |
| Material tahan lembap | area laundry, KM, balkon |
| Pengurangan AC | ventilasi dan shading sebelum bergantung pada AC |

## 🧾 14. Regulasi dan Perizinan

Hal ini perlu dicek ke regulasi setempat. Jangan mengunci gambar final sebelum aspek berikut dikonfirmasi. Bagian ini agak birokratis, tapi mending dicek daripada revisi besar belakangan 🧾

| Aspek | Catatan |
|---|---|
| PBG | wajib untuk bangunan baru/perubahan besar |
| Fungsi campuran | komersial + hunian perlu dinyatakan jelas |
| KDB | footprint +/-140.80 m2 dari lahan +/-226 m2, sekitar 62% |
| KLB | jika 2 lantai penuh, total lantai +/-281.60 m2, KLB sekitar 1.25 |
| GSB | perlu cek jarak bangunan ke jalan |
| Drainase | parkir, balkon, talang, dan air hujan harus jelas |
| Proteksi kebakaran | APAR dan jalur evakuasi minimal |

## 📐 15. Checklist Gambar Arsitektur

Wajib dibuat:

- Denah lantai 1 skala 1:100.
- Denah lantai 2 skala 1:100.
- Grid angka-huruf resmi.
- Notasi elevasi: `+/-0.00`, `+3600`, turun KM/laundry/balkon.
- Tampak depan, samping, belakang.
- Potongan melalui tangga.
- Potongan melalui kamar mandi/laundry.
- Detail tangga.
- Detail balkon dan railing.
- Detail kamar mandi.
- Detail kusen dan bukaan.
- Denah atap dan arah aliran air hujan.
- Jadwal pintu dan jendela.

## 🧱 16. Checklist Gambar Struktur

Wajib dibuat:

- Denah pondasi.
- Denah sloof.
- Denah kolom dengan kode.
- Denah balok lantai 2.
- Denah pelat lantai 2.
- Detail balok tepi void tangga.
- Detail tangga beton.
- Detail balok balkon.
- Detail area basah lantai 2.
- Detail kolom dan sambungan balok-kolom.
- Catatan mutu beton, tulangan, dan selimut beton.
- Perhitungan struktur untuk opsi tumbuh 3 lantai jika itu tetap menjadi target.

## 🔌 17. Checklist Gambar MEP

Wajib dibuat:

- Denah air bersih.
- Denah air kotor dan air bekas.
- Denah vent pipe.
- Detail shaft plumbing.
- Denah floor drain.
- Denah exhaust fan.
- Denah titik lampu.
- Denah saklar.
- Denah stopkontak.
- Denah AC dan drain AC.
- Single line diagram sederhana.
- Pembagian sirkuit ruang kerja, laundry, pantry, AC, dan area basah.

## 🚨 18. Matriks Risiko Prioritas

| Prioritas | Risiko | Dampak | Tindakan |
|---:|---|---|---|
| 1 | Dinding lantai 2 tidak di atas balok | retak, pelat terbebani | overlay balok-kolom |
| 2 | Void tangga tidak detail | retak/getaran | balok tepi void |
| 3 | Kamar mandi/laundry bocor | kerusakan lantai 1 | waterproofing + FD + slope |
| 4 | Balkon tidak detail | bocor/kantilever bermasalah | balok balkon + drainase |
| 5 | Koridor dan pintu tabrakan | tidak nyaman harian | simulasi swing pintu |
| 6 | Ruang kerja tanpa exhaust | risiko kesehatan | fume extractor ducted |
| 7 | Area tengah gelap/pengap | kualitas hunian turun | roster/skylight/exhaust |
| 8 | Akses hunian lewat toko tanpa batas | privasi lemah | threshold/pintu transisi |
| 9 | Lineweight buruk | gambar sulit dibaca | CTB/layer cleanup |

## 🗺️ 19. Rekomendasi Tahap Kerja Berikutnya

Tahap 1 - Kunci teknis dasar:

- pastikan semua ukuran CAD dalam mm;
- buat grid `1-3` dan `A-E`;
- beri kode kolom;
- buat overlay balok lantai 2;
- cek void tangga dan balkon.

Tahap 2 - Rapikan denah arsitektur:

- simulasi semua bukaan pintu;
- kunci lebar koridor;
- kunci mushola 3000 x 2200 mm;
- kunci balkon 3000 x 1500 mm;
- atur furniture kamar utama, ruang kerja, dan ruang keluarga.

Tahap 3 - MEP:

- tentukan shaft plumbing;
- gambar jalur pipa;
- tentukan floor drain;
- tentukan exhaust;
- gambar titik listrik;
- pisahkan sirkuit ruang kerja dan area basah.

Tahap 4 - Dokumen cetak:

- rapikan CTB;
- isi title block;
- buat layout A3;
- buat PDF uji print;
- cek keterbacaan garis pada kertas putih.

## ✅ 20. Kesimpulan Akhir V2

Desain ini memiliki fondasi konsep yang baik. Lantai 1 kuat sebagai ruang usaha fleksibel, sementara lantai 2 sudah mulai matang sebagai hunian keluarga yang memisahkan tamu, servis, ibadah, kerja, istirahat, dan ruang santai.

Nilai psikologis terbaik dari denah ini adalah adanya gradasi dari tangga menuju ruang tamu, lalu ke ruang keluarga dan balkon yang lebih privat. Ini membuat rumah tidak terasa langsung terbuka setelah naik dari area usaha. Mushola di tengah juga memberi pusat ketenangan, sedangkan ruang kerja yang terpisah memberi peluang fokus.

Risiko terbesar bukan lagi pada ide ruang, tetapi pada koordinasi teknis: struktur balok-kolom, void tangga, balkon, area basah, exhaust ruang kerja, dan MEP. Karena itu, revisi berikutnya sebaiknya bukan menambah banyak ruang baru, melainkan membuat denah ini "terkunci secara teknik".

Rekomendasi final: lanjutkan dengan gambar overlay struktur lantai 2. Setelah itu baru finalisasi pintu, koridor, kamar mandi, service room, furniture utama, dan MEP. Jadi next step-nya jelas: bikin denahnya makin siap dibangun, bukan cuma makin cakep dilihat ✅
