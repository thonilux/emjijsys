# 🏗️✨ ANALISIS KOMPREHENSIF DESAIN EMJIJSYS-MODEL — V2
### 🏠 Ruko Hunian 2 Lantai — PT. Emji Jaya | *"From Shop Floor to Dream Home"*

📄 **Sumber Gambar:** [emjijsys-Model.pdf](file:///d:/cad/emjijsys-Model.pdf) (As Built Drawing)  
💻 **File CAD:** [emjijsys.dwg](file:///d:/cad/emjijsys.dwg)  
📍 **Lokasi:** Desa Genggong Pojok, Kel. Delingan, Kec. Karanganyar, Kab. Karanganyar, Jawa Tengah (57716)  
🌐 **Koordinat:** `-7.600609, 110.991651`  
📐 **Luas Lahan:** ±226 m² | **Lebar Lahan:** 9,80 m | **Panjang Lahan:** ±23,06 m  
🏢 **Footprint Bangunan:** 8,80 m × 16,00 m = 140,80 m²  
📏 **Tinggi Lantai 1 → 2:** 3.600 mm (floor-to-floor)  
📅 **Tanggal Analisis:** 29 Juli 2026 (Revisi V2)  
🤖 **Analis:** Antigravity AI — Claude Opus 4.6  
📚 **Referensi:** [emjijsys-analasis.md](file:///d:/cad/emjijsys-analasis.md), [emjijsys-antigravity.md](file:///d:/cad/emjijsys-antigravity.md), [analisis_lahan_dasar.md](file:///d:/cad/analisis_lahan_dasar.md), [rencana_ruko_hunian_v1.md](file:///d:/cad/rencana_ruko_hunian_v1.md), [analisis_kenyamanan_tangga.md](file:///d:/cad/analisis_kenyamanan_tangga.md)

---

## I. 🎯 RINGKASAN EKSEKUTIF — *TL;DR buat yang sibuk*

Gambar `emjijsys-Model.pdf` adalah **As Built Drawing** ruko hunian 2 lantai milik PT. Emji Jaya di lahan 226 m² di kawasan ibu kota Kabupaten Karanganyar. Konsepnya? 👇

> 🏪 **Lantai 1** = Open space komersial / toko → *hustle zone*  
> 🏠 **Lantai 2** = Hunian privat lengkap → *comfort zone*

Secara keseluruhan, desain ini punya **arah konsep yang kuat** 💪 — keputusan besar yang udah on point:
- ✅ Ruang tamu dekat tangga (filter sosial, tamu nggak langsung ke kamar)
- ✅ Ruang keluarga di depan dekat balkon (vibes santai + cahaya alami)
- ✅ Laundry & KM dikelompokkan (plumbing efisien, no ribet)
- ✅ Kamar tidur terpisah dari area penerima tamu (privacy is everything)

> ⚠️ **TAPI**, gambar ini **belum boleh dianggap final untuk konstruksi!** Yang paling perlu di-level-up: koordinasi dinding Lt.2 vs balok-kolom, detail area basah, sirkulasi di simpul toilet-tangga-ruang kerja, dan lineweight gambar biar terbaca di kertas putih.

### 📊 Skor Penilaian — *Seberapa siap desain ini?*

| Aspek | Skor | Vibe Check |
|:------|:----:|:-----------|
| 🏛️ **Arsitektur** | ★★★★☆ | Zoning on point! ✨ Sirkulasi & detail perlu diperhalus |
| 🧱 **Struktur** | ★★★☆☆ | Grid kolom terbaca, overlay dinding-balok belum verified |
| 🧠 **Psikologi Ruang** | ★★★★☆ | Hierarki privasi sehat 💚 beban kognitif perlu dikelola |
| 🔧 **MEP** | ★★☆☆☆ | Cluster plumbing efisien, gambar MEP belum ada 😬 |
| 📝 **Kelengkapan Gambar** | ★★☆☆☆ | Banyak info wajib masih kosong 🚨 |

### 🔥 8 Prioritas Teknis — *Fix ini dulu sebelum lanjut!*

1. 🔲 Kunci grid struktur resmi: angka `1-3` untuk arah lebar, huruf `A-E` untuk arah panjang.
2. 🧱 Overlay balok lantai 2 sebelum mengunci dinding kamar, mushola, ruang kerja, dan toilet.
3. 📏 Rapikan koridor tengah → bersih minimal 900 mm, ideal 1000–1200 mm.
4. 🚪 Cek swing pintu KM, ruang kerja, kamar utama, dan akses ruang keluarga.
5. 🔧 Tetapkan shaft plumbing di cluster laundry/toilet.
6. 🪜 Buat detail tangga, void tangga, balok tepi void, dan headroom.
7. 🌿 Buat detail balkon: balok, railing, slope, floor drain, waterproofing.
8. 📋 Lengkapi title block, skala, lineweight, layer, elevasi, dan notasi material.

---

## II. 🧭 ORIENTASI, MASSA BANGUNAN & DATA DIMENSI

### A. 🧭 Pembacaan Orientasi — *Rumah hadap mana sih?*

| Arah Pada Gambar | Arti | Implikasi Desain |
|:---|:---|:---|
| Atas | Utara | Area belakang bangunan |
| Kanan | Timur | Sisi kanan bangunan |
| Bawah | Selatan | **Fasad utama** — parkir & balkon menghadap selatan |
| Kiri | Barat | Sisi kiri bangunan |

Massa bangunan memanjang dari **selatan (depan) ke utara (belakang)**. Lebar bangunan 8,80 m di dalam lahan 9,80 m — menyisakan ±0,50 m di kiri dan kanan sebagai talang/maintenance gap (bukan jalur sirkulasi manusia).

> **Catatan:** Jika orientasi site sebenarnya berbeda, analisis bukaan, matahari, dan ventilasi perlu dikoreksi.

### B. 📐 Data Dimensi — *Angka-angka penting dari gambar*

| Elemen | Ukuran | Konversi CAD | Catatan |
|:-------|-------:|---:|:--------|
| Lebar lahan total | 9,80 m | 9.800 mm | Tertera di sisi atas denah |
| Lebar bangunan efektif | 8,80 m | 8.800 mm | Setelah dikurangi talang 2×0,50 m |
| Panjang bangunan | 16,00 m | 16.000 mm | Tertera di sisi kiri denah |
| Area parkir depan | ±4,00 m | 4.000 mm | Area kosong/halaman depan |
| Sisa lahan belakang | ±3,06 m | 3.060 mm | Area servis/teras |
| Partisi Lt.1 | 4,00 m panjang | 4.000 mm | Pojok kiri belakang |
| Tangga | ±2,40 × 4,00 m | 2.400 × 4.000 mm | Perlu dicek jumlah step & headroom |
| Ruang Tamu (Lt.2) | ±? × 2,75 m | 2.750 mm | Lebar mengikuti bidang kanan |
| Dapur Kering | ±? × 2,58 m | 2.580 mm | Cukup untuk pantry + meja kecil |
| Mushola | ±? × 2,20 m | 2.200 mm | Target: 3.000 × 2.200 mm |
| Ruang Kerja | ±? × 3,30 m | 3.300 mm | Baik untuk ruang kerja compact |
| Kamar Tidur Utama | ±? × 3,90 m | 3.900 mm | Layak, tergantung lebar bersih |
| Kamar Tidur Tambahan | ±? × 3,20 m | 3.200 mm | Cukup sebagai kamar anak/tamu |
| Ruang Keluarga | ±? × 5,25 m | 5.250 mm | Dekat balkon — sangat baik |
| Balkon | ±? × 2,50 m | 2.500 mm | Target: 3.000 × 1.500 mm |

> **Catatan:** PDF dapat mengalami scaling saat plot. Untuk gambar kerja, ukuran wajib diverifikasi dari file CAD dengan command `DIST` atau dimensi asli. Seluruh dimensi gambar kerja harus dalam **milimeter** dengan skala rasional (1:100 denah, 1:50 detail).

---

## III. 🖥️ EVALUASI KUALITAS GAMBAR CAD — *Udah siap print belum?*

### A. 📐 Skala, Plot & Text

| Item | Kondisi Sekarang | Rekomendasi |
|:---|:---|:---|
| Skala | Belum terlihat jelas pada title block | Tulis `1:100` untuk denah umum, `1:50` untuk detail |
| Sheet | Layout besar dengan ruang kosong | Gunakan A3 landscape dengan viewport layout |
| Plot style | Garis sangat samar pada PDF | Gunakan CTB custom dengan lineweight jelas |
| Text | Beberapa teks terlalu pucat | Pertebal layer teks, screening 100% |

Jika denah dibuat di model space dengan ukuran asli mm, plot A3 sebaiknya memakai viewport layout dengan skala 1:100. Jika objek sudah diperkecil ke ukuran kertas, plot 1:1 — tetapi kurang ideal untuk workflow CAD profesional.

### B. 🎨 Layer & Lineweight — *Kenapa gambarnya samar banget?*

> 😤 Masalah terbesar saat ini: elemen penting dan sekunder **hampir sama samar**. Nggak ada hierarki visual! Harusnya: dinding/kolom paling tebal → pintu/jendela → furniture → dimensi/grid.

| Layer | Warna ACI | Lineweight | Fungsi |
|:---|---:|---:|:---|
| `AXIS_GRID` | 1 atau 9 | 0,05–0,09 mm | Garis as/grid samar |
| `STRUCTURE_COLUMN` | 7 | 0,40–0,60 mm | Kolom beton |
| `STRUCTURE_WALL_CUT` | 7 | 0,35–0,50 mm | Dinding terpotong (paling tebal) |
| `ARCH_PARTITION` | 8 | 0,18–0,25 mm | Partisi/dinding ringan |
| `ARCH_DOOR_WINDOW` | 7 atau 8 | 0,13–0,18 mm | Pintu, jendela, kusen |
| `ARCH_FURNITURE` | 8 | 0,09–0,13 mm | Furniture dan equipment |
| `MEP_PLUMBING` | 3 | 0,13–0,18 mm | Pipa, floor drain, sanitary |
| `MEP_ELECTRICAL` | 5 | 0,13–0,18 mm | Lampu, saklar, stopkontak |
| `DIMENSION` | 2 | 0,09–0,13 mm | Dimensi |
| `TEXT_TITLE` | 4 | 0,13–0,18 mm | Judul dan label ruang |

### C. 📍 Grid, Elevasi & Notasi — *Yang masih missing*

| Aspek | Kondisi | Rekomendasi |
|:---|:---|:---|
| **Grid/as** | Kolom terlihat, grid formal belum ada | Lebar: `1-2-3` (4.400+4.400), Panjang: `A-B-C-D-E` (4×4.000) |
| **Elevasi** | Belum terlihat | `±0.00` Lt.1, `-0.05~-0.15` parkir, `+3.60` Lt.2 |
| **Elevasi KM/Laundry** | Tidak ada | Turun 20–30 mm dari lantai sekitar |
| **Elevasi balkon** | Tidak ada | Turun 20–30 mm dari ruang dalam |
| **Bordes tangga** | Tidak ada | `+1.80` bila 20 riser @180 mm |
| **Title block** | Banyak field kosong | Isi nama gambar, skala, tanggal, revisi, checker, kode gambar |

### D. ✅❌ Checklist Kelengkapan Gambar — *Progress check!*

| Aspek | Status | Prioritas |
|:------|:------:|:---------:|
| Skala gambar tertulis | ❌ | 🔴 |
| Grid/as struktur formal | ❌ | 🔴 |
| Notasi elevasi | ❌ | 🟡 |
| Line weight terstandar | ❌ | 🟡 |
| Arah bukaan pintu | ❌ | 🟡 |
| Simbol jendela/ventilasi | ❌ | 🟡 |
| Nama ruang konsisten | ✅ | — |
| Title block lengkap | ⚠️ | 🟡 |
| Detail tangga (potongan 1:50) | ❌ | 🟡 |
| Detail kamar mandi (denah 1:50 + potongan) | ❌ | 🟡 |
| Denah atap + kemiringan | ❌ | 🟢 |
| Tampak depan/samping/belakang | ❌ | 🟡 |

---

## IV. 🏪 ANALISIS ARSITEKTUR — LANTAI 1 *(Hustle Zone)*

### A. 🎯 Fungsi Utama

Lantai 1 = **toko / open space** (~120 m² netto). Basically satu lantai penuh buat bisnis! 💼 Bisa dipakai untuk display, workshop ringan, showroom, meja kasir, penyimpanan, atau area operasional fleksibel.

### B. 💪 Kelebihan — *Yang udah on point*

1. **Plan sederhana, mudah dibangun** — bentuk ruang efisien tanpa kerumitan berlebih.
2. **Ruang open space sangat besar** (~120 m² netto) — ideal untuk toko yang membutuhkan fleksibilitas layout.
3. **Struktur kolom perimeter** dengan beberapa kolom tengah memberi irama bentang yang efisien (±4,40 × 4,00 m per modul).
4. **Tangga di belakang** — akses hunian Lt.2 tidak mengganggu area komersial depan.
5. **Area parkir depan jelas** (9,80 × 4,00 m) — muat 2 mobil sejajar atau 6–8 motor.
6. **Partisi belakang** (4,00 m) — fleksibel sebagai gudang/kasir/kantor.

### C. 🚧 Kelemahan — *Yang perlu di-fix*

1. **Belum ada pemisahan akses toko vs. hunian** — penghuni harus melewati hampir seluruh area toko untuk mencapai tangga.

   | Skenario | Dampak |
   |:---|:---|
   | Tangga tetap di belakang, akses lewat toko | Efisien, tetapi privasi hunian lemah saat toko beroperasi |
   | Dibuat jalur akses samping/dalam khusus ke tangga | Lebih privat, tetapi mengurangi area toko |
   
   > Jika pemilik = penghuni dan usaha keluarga kecil, akses lewat toko masih bisa diterima. Jika ada karyawan/tamu usaha terpisah, akses hunian sebaiknya dibuat lebih jelas.

2. **Fungsi partisi belakang belum jelas** — kemungkinan: kantor kecil/kasir, gudang, ruang arsip, ruang servis, atau pantry staf. Masing-masing memerlukan spesifikasi berbeda (pintu, ventilasi, AC, shaft).

3. **Toilet tamu/karyawan** — terlihat toilet under-stair. Perlu dikonfirmasi kecukupan dimensi (minimal 1,20 × 2,00 m).

4. **Kolom tengah di area toko** — bisa dimanfaatkan sebagai:
   - Titik signage internal / CCTV
   - Pembatas halus area display vs area kerja
   - Tempat rak menempel / island display
   - Titik lighting track
   
   > Kolom jangan dibiarkan terlihat seperti gangguan — harus "dijadikan alasan" dalam desain interior.

5. **Arah bukaan pintu** — belum tergambar di seluruh denah.
6. **Jalur evakuasi kebakaran** — belum ada notasi.

### D. 🚗 Parkir & Area Depan

Area parkir ±4,00 m cukup untuk mobil kecil/sedang secara panjang minimum, tetapi perlu dicek radius bukaan pintu kendaraan.

| Item | Rekomendasi |
|:---|:---|
| Lebar gate | Min 3.000 mm (1 mobil), nyaman 3.500 mm |
| Kemiringan parkir | 1–2% ke saluran drainase |
| Trench drain | Di depan fasad — cegah air hujan masuk toko |
| Level parkir | Lebih rendah 50–150 mm dari lantai toko (`±0.00`) |
| Finishing | Paving block atau beton ekspos dengan drainase |

---

## V. 🏠 ANALISIS ARSITEKTUR — LANTAI 2 *(Comfort Zone)*

### A. 🗺️ Zoning Makro — *Siapa di mana?*

Lantai 2 = inti hunian. Denah udah membentuk gradasi yang jelas — **good job!** 👏

| Zona | Ruang | Nilai Positif | Risiko |
|:---|:---|:---|:---|
| **Arrival** | Tangga, ruang tamu | Tamu berhenti di area penerima | Visual pintu toilet bisa terlalu dekat |
| **Service** | Laundry, KM umum, KM privat | Plumbing terkumpul | Bau/lembap harus dikendalikan |
| **Social harian** | Dapur kering, meja makan | Cocok dekat ruang tamu | Bisa berantakan terlihat tamu |
| **Spiritual/tenang** | Mushola | Area khusus ibadah | Jangan jadi jalur sirkulasi |
| **Privat kerja** | Ruang kerja | Terpisah dari ruang tamu | Butuh exhaust soldering |
| **Privat tidur** | KT Utama, KT tambahan | Tidak langsung terekspos tamu | Perlu cek posisi pintu & furniture |
| **Restoratif** | Ruang keluarga, balkon | Area santai dekat bukaan | Perlu shading, railing, waterproofing |

### B. 🚶 Sirkulasi Utama — *Alur gerak di dalam rumah*

Alur sirkulasi:

```
Naik tangga → Ruang Tamu / Dapur Kering → Koridor Tengah
                                               │
                          ┌──────────┬─────────┼──────────┬────────────┐
                          │          │         │          │            │
                       Mushola   R.Kerja    KT Utama   R.Keluarga   Balkon
                                                          │
                                                       KT Tambahan
```

Secara psikologis, alur ini cukup baik karena tidak membawa tamu langsung ke kamar. Titik kritis ada di **simpul KM — tangga — ruang kerja** — jika terlalu banyak pintu bertemu, ruang terasa sempit, canggung, dan rawan tabrakan daun pintu.

| Jalur | Minimal | Nyaman | Catatan |
|:---|---:|---:|:---|
| Koridor utama | 900 mm | 1000–1200 mm | Untuk hunian 2 lantai |
| Depan pintu KM | 900 mm | 1100 mm | Hindari pintu saling tabrak |
| Area meja makan | 800 mm clear | 900–1000 mm | Agar kursi bisa ditarik |
| Depan lemari/rak kerja | 800 mm | 900–1000 mm | Untuk gerak dan buka laci |

### C. 🔍 Evaluasi Detail per Ruang — *Deep dive tiap zona!*

---

#### C.1 🪜 Tangga — *Portal dari toko ke rumah*

Tangga dibaca sebagai tangga U/dua flight dengan angka anak tangga 1–18 terlihat. Target: 20 riser @180 mm untuk floor-to-floor 3.600 mm.

| Parameter | Rekomendasi | Status |
|:---|---:|:---|
| Tinggi riser | 160–180 mm | ⚠️ Perlu konfirmasi jumlah step |
| Lebar tread | 260–300 mm | Target 280 mm |
| Lebar tangga | min 900 mm, nyaman 1000–1200 mm | ✅ Terbaca 1.200 mm |
| Headroom | min 2.100 mm | ⚠️ Perlu cek |
| Handrail | 850–900 mm | ❌ Belum tergambar |
| Bordes | min = lebar tangga | ⚠️ Perlu konfirmasi |

**Catatan arsitektural:**
- Tangga di belakang memberi privasi area depan — keputusan baik.
- Tangga adalah **transisi mental** dari dunia kerja/toko ke rumah — jangan terasa gelap/servis.
- Pencahayaan tangga harus hangat dan cukup terang.

**Catatan struktur:**
- Void tangga wajib diberi balok tepi.
- Bordes harus jelas tumpuannya.
- Jika ada KM/storage bawah tangga, cek headroom dan kemiringan bawah plat.

---

#### C.2 🛋️ Ruang Tamu — *Filter sosial, tamu stop di sini*

Ditempatkan dekat tangga di sisi kanan belakang — keputusan tepat. Berfungsi sebagai **filter sosial**: tamu berhenti di sini, tidak perlu masuk jauh ke ruang keluarga.

**Kelebihan:** Area privat depan tetap terlindungi. Tamu mendapat tempat berhenti yang jelas setelah naik tangga.

**Risiko:**
- Jika terlalu dekat dapur kering, area pantry bisa terlihat berantakan oleh tamu.
- Jika pintu KM terlihat langsung dari ruang tamu, kualitas psikologis ruang turun.
- Mungkin kurang mendapat cahaya alami jika tidak ada bukaan.

**Saran:**
- Buat partisi rendah/kabinet tipis antara ruang tamu dan dapur kering.
- Tambahkan jendela/ventilasi ke arah timur atau bukaan atas.
- Pencahayaan warm 3000–3500K.
- Sediakan satu dinding fokus: artwork, rak pendek, atau panel TV kecil.

---

#### C.3 ☕ Dapur Kering & Meja Makan — *Coffee corner + snack zone*

Dekat ruang tamu — cocok untuk pantry ringan (kopi, sarapan, snack, plating). **Bukan pengganti dapur basah** kalau sering masak berat ya! 🍳

| Komponen | Ukuran |
|:---|---:|
| Kedalaman kabinet bawah | 600 mm |
| Kedalaman kabinet atas | 300–350 mm |
| Lebar meja kerja minimum | 1.800 mm |
| Lebar meja kerja nyaman | 2.400–3.000 mm |
| Clear area depan kabinet | 900–1.000 mm |
| Meja makan 4 orang | ±800 × 1.200 mm |
| Clear belakang kursi | min 800 mm |

**Saran:**
- Letakkan sink kecil jika ada pipa dekat KM/laundry.
- Hindari kompor besar tanpa exhaust.
- Pantry yang terlihat dari ruang tamu harus mudah dirapikan (kabinet tertutup).
- Siapkan exhaust, stopkontak khusus, dan backsplash mudah dibersihkan.

---

#### C.4 🧺 Laundry / Service Room — *Behind the scenes*

Dekat tangga dan KM — baik dari sisi MEP dan psikologis (laundry tersembunyi = rumah terlihat rapi ✨).

| Elemen | Ukuran |
|:---|---:|
| Mesin cuci front load | ±600 × 600 mm |
| Sink utilitas | 450–600 mm lebar |
| Counter | 600 mm dalam |
| Jalur gerak depan mesin | min 800 mm |
| Lebar service room nyaman | 1.500 mm |
| Panjang service room nyaman | 3.000–4.000 mm |

**Fungsi yang bisa ditampung:** Mesin cuci, utility sink, rak deterjen, rak alat pel/sapu, chemical cabinet, tempat jemur indoor ringan.

**Detail wajib:**
- Lantai turun 20–30 mm atau ada water stop.
- Slope 1–2% ke floor drain.
- Dinding area basah: keramik/cat waterproof min 1.200 mm, full height dekat sink.
- Stopkontak mesin cuci jauh dari cipratan air, punya grounding.
- Exhaust atau kisi ventilasi wajib.

---

#### C.5 🚿 Kamar Mandi — *Dua KM, satu cluster — smart!*

Dua kamar mandi berdekatan — keputusan bagus secara plumbing 👌 Satu melayani ruang tamu/keluarga (umum), satu lebih privat untuk kamar utama.

| Elemen | Minimum | Nyaman |
|:---|---:|---:|
| Lebar pintu KM | 700 mm | 750–800 mm |
| Area shower | 800 × 800 mm | 900 × 1.200 mm |
| Area kloset | 750 × 1.200 mm | 800 × 1.300 mm |
| Area wastafel | 600 × 800 mm | 700 × 900 mm |
| Lebar ruang KM kecil | 1.200 mm | 1.500 mm |

**Catatan psikologis:**
- Pintu toilet jangan menjadi focal point dari ruang tamu atau meja makan.
- Jika pintu harus terlihat, buat transisi visual: dinding pendek, tanaman, kabinet linen, atau niche.
- Toilet privat yang tidak dalam kamar tetap bisa terasa privat bila aksesnya dari koridor keluarga.

**Catatan teknis:**
- KM lantai 2 wajib waterproofing serius (naik ke dinding min 200–300 mm, area shower lebih tinggi).
- Pisahkan area shower basah dengan kaca/curtain.
- Exhaust wajib jika tanpa jendela langsung.
- Floor drain min 1 di area shower, 1 di area umum KM.

---

#### C.6 🕌 Mushola — *Anchor emosional rumah* 🤲

Target: 3.000 × 2.200 mm — baik untuk 2–3 orang, masih bisa menampung rak sajadah kecil.

**Evaluasi:**
- Posisi tidak langsung di ruang tamu → lebih tenang.
- Dekat ruang keluarga → terasa bagian kehidupan harian rumah.
- Dekat kamar mandi untuk wudu, tapi pintu KM jangan mengganggu kesakralan ruang.

**Saran desain:**
- Partisi tidak perlu full tertutup — bisa dinding 1.200–1.500 mm atau kisi agar cahaya masuk.
- Sediakan rak dangkal 300–350 mm untuk sajadah/mukena.
- Hindari furniture berat di dinding arah kiblat.
- Lantai bisa dinaikkan 50–100 mm atau dibedakan materialnya untuk memberi rasa khusus.
- Pencahayaan lembut (warm white), tidak menyilaukan. Gunakan indirect/cove lighting.
- **Jangan dijadikan jalur lewat utama** — ini krusial.

---

#### C.7 🛋️🌿 Ruang Keluarga + Balkon — *The healing zone* 💚

Ruang keluarga di area depan-kiri dekat balkon — **keputusan yang sangat FIRE** 🔥. Ruang keluarga seharusnya jadi tempat paling santai, bukan ruang sisa. Dekat balkon = ruang punya "nafas."

**Kelebihan:**
- Lebih privat dari ruang tamu.
- Mendapat potensi cahaya dan udara dari balkon.
- Bisa menjadi pusat aktivitas keluarga.
- Memberi rasa lepas setelah naik dari toko/area usaha.

**Risiko:**
- Jika terlalu terbuka ke koridor, aktivitas keluarga masih terlihat dari area tamu.
- Jika balkon terlalu panas, ruang keluarga ikut panas.
- Jika mushola terlalu dekat tanpa pembatas, suara TV/aktivitas mengganggu ibadah.

**Saran:**
- Pisahkan dengan mushola via partisi rendah/kisi.
- Orientasikan sofa agar tidak membelakangi semua akses.
- Bukaan balkon cukup besar, tapi pakai shading/kanopi.
- Storage tertutup untuk mengurangi visual clutter.

**Detail balkon:**

| Item | Rekomendasi |
|:---|---:|
| Lebar nyaman balkon duduk | 1.500 mm |
| Panjang untuk 2 orang | 3.000 mm |
| Tinggi railing | 1.000–1.100 mm |
| Slope lantai | 1–2% ke floor drain |
| Turun lantai dari ruang dalam | 20–30 mm |
| Waterproofing | Wajib, naik ke dinding/parapet |

---

#### C.8 🔧⚡ Ruang Kerja — *Workshop mode: ON* 🛠️

Sisi kanan tengah — untuk fungsi rak alat dan soldering tool, ruang ini butuh **perlakuan teknis serius**. Bukan sekadar kamar kerja biasa!

| Kebutuhan | Saran |
|:---|:---|
| Meja kerja utama | 700–800 mm dalam, 1.600–2.400 mm panjang |
| Rak alat | dalam 350–450 mm |
| Jalur kursi | min 900 mm |
| Exhaust soldering | **Fume extractor ducted ke luar** (bukan exhaust biasa!) |
| Stopkontak | Banyak, grounded, tidak bertumpuk sembarangan |
| Pencahayaan | Task light 4000–5000K |
| Lantai | Mudah dibersihkan, anti lembap |
| Meja | Tahan panas |
| Kursi | Ergonomis |
| Storage | Alat tajam/panas tertutup |

**Aspek psikologis:**
- Ruang terpisah dari ruang keluarga = membantu fokus.
- Pintu jangan langsung mengekspos meja kerja berantakan.
- Posisi duduk idealnya bisa melihat pintu secara diagonal.
- Jangan menjadi jalur menuju ruang lain.

**Risiko kesehatan:**
- Asap flux/solder tidak boleh menyebar ke kamar tidur dan ruang keluarga.
- Panas alat dan kabel harus aman dari anak.
- Debu kecil harus dikendalikan.

---

#### C.9 🛏️ Kamar Tidur Utama — *Safe space, no disturbance* 😴

Sisi kanan tengah-depan — cukup privat, nggak langsung dekat tangga/ruang tamu. Kedalaman ±3.900 mm layak.

| Elemen | Ukuran |
|:---|---:|
| Kasur queen | 1.600 × 2.000 mm |
| Kasur king | 1.800 × 2.000 mm |
| Sisi kiri/kanan ranjang | min 600 mm, nyaman 700–800 mm |
| Depan ranjang | min 700 mm |
| Lemari pakaian | 600 mm dalam |
| Jalur depan lemari | 800–900 mm |

**Prinsip penempatan ranjang:**
- Kepala ranjang menempel dinding solid.
- Ranjang tidak sejajar langsung dengan pintu.
- Pintu masih terlihat dari tempat tidur secara diagonal.
- Hindari kepala ranjang menempel dinding toilet/shower.
- Wardrobe sebagai buffer akustik.
- Ukuran bersih ideal: min ±3.500 × 3.900 mm untuk kesan premium.

---

#### C.10 🛌 Kamar Tidur Tambahan — *Flex room*

Depan-kanan bawah — kamar anak/tamu/cadangan. Dekat fasad selatan = perlu kontrol panas ☀️🔥.

**Saran:**
- Minimal bersih 3.000 × 3.200 mm (kasur single/double kecil + lemari + meja kecil).
- Bila menghadap fasad selatan, beri shading untuk mengurangi panas/silau.
- Jendela jangan langsung mengekspos ranjang dari balkon/jalan.
- Pintu jangan langsung membuka ke arah ranjang.
- Ventilasi alami atau AC-ready.

---

## VI. 🧱 ANALISIS STRUKTUR — *Tulang punggung bangunan*

### A. 🏗️ Sistem Struktur

Bangunan pakai **sistem rangka beton bertulang** (portal frame) dengan grid sederhana yang rasional — basically kerangka yang kokoh 💪:

| Grid | Jarak |
|:---|---:|
| 1–2 (lebar) | 4.400 mm |
| 2–3 (lebar) | 4.400 mm |
| A–B (panjang) | 4.000 mm |
| B–C (panjang) | 4.000 mm |
| C–D (panjang) | 4.000 mm |
| D–E (panjang) | 4.000 mm |

```
              ←──── 8.800 mm ────→
              ←4.400→←──4.400──→

    [K1]★─────[K2]─────[K3]★    ← Grid A (depan)       ─┐
     │          │          │                               │
     │  4.000   │  4.000   │                               │
     │          │          │                               │
    [K4]──────[K5]──────[K6]     ← Grid B                  │
     │          │          │                               │
     │  4.000   │  4.000   │                            16.000 mm
     │          │          │                               │
    [K7]──────[K8]──────[K9]     ← Grid C                  │
     │          │          │                               │
     │  4.000   │  4.000   │                               │
     │          │          │                               │
   [K10]─────[K11]─────[K12]    ← Grid D                  │
     │          │          │                               │
     │  4.000   │  4.000   │                               │
     │          │          │                               │
   [K13]★────[K14]─────[K15]★   ← Grid E (belakang)      ─┘
     │          │          │
   Grid 1    Grid 2     Grid 3

   ★ = Pilar pangkon (kolom sudut) — pondasi cakar ayam (3 cakar × 4 = 12 biji)
```

### B. 📐 Dimensi Struktural — *Seberapa gede sih kolomnya?*

| Elemen | Ukuran Konseptual | Status | Catatan |
|:---|---:|:---:|:---|
| Kolom utama (sudut) | 400 × 400 mm | ✅ | Siap tumbuh 3 lantai |
| Kolom antara | 350 × 350 mm | ✅ | Memadai |
| Balok induk | 250 × 500 mm | ⚠️ | Wajib hitung engineer |
| Balok anak | 200 × 350 mm | ⚠️ | Sesuai bentang |
| Pelat lantai | 120 mm | ⚠️ | Perlu hitung sesuai beban |
| Dinding bata + plester | min 150 mm | ✅ | |
| Sloof pengikat | ≥200 × 300 mm | ⚠️ | Sesuai hitung |
| Pondasi cakar ayam | 1.200 × 1.200 mm | ✅ | Per catatan A3 |
| Tinggi lantai 1 → 2 | 3.600 mm | ✅ | |

> ⚠️ **PENTING BANGET:** Ini bukan desain final! Kalau mau tumbuh 3 lantai, ukuran kolom dan pondasi HARUS dihitung ulang dari awal sama engineer sipil. No shortcut! 🚫

### C. 🚨 Titik Kritis Struktural — *Danger zones!*

#### C.1 🔴 Balok di Bawah Dinding Lantai 2 — **PRIORITAS TERTINGGI** ‼️

Ini titik paling penting. Dinding lantai 2 **tidak boleh ditempatkan seenaknya** di atas pelat tanpa memikirkan balok. Dinding bata/plester bisa sangat berat.

- Dinding kamar tidur sisi kanan → harus di atas balok grid atau balok anak.
- Dinding toilet/laundry → **wajib** didukung balok (area basah lebih berat).
- Dinding mushola dan ruang keluarga → cek apakah jatuh pada garis balok.
- Jika dinding tidak di atas balok → gunakan partisi ringan **atau** tambahkan balok anak.

#### C.2 ⚠️ Void Tangga — *Lubang di pelat = sensitif!*

Void tangga memotong pelat lantai 2, membuat struktur sekitar tangga lebih sensitif.

**Wajib ada:**
- Balok tepi void di sisi panjang dan pendek.
- Penyaluran tulangan pelat ke balok tepi.
- Tumpuan bordes yang jelas.
- Detail sambungan tangga ke balok/bordes.

**Risiko jika tidak benar:** retak di sudut void, getaran di sekitar tangga, pelat terasa lemah, beban dinding tidak tersalurkan baik.

#### C.3 🌿 Balkon Depan — *Cantik tapi high risk*

Elemen risiko tinggi — terkena air, panas, dan sering bekerja sebagai kantilever.

**Wajib dicek:**
- Apakah kantilever atau ditumpu kolom/balok bawah.
- Tulangan negatif di area tumpuan.
- Balok tepi balkon.
- Waterproofing dan slope.
- Railing terikat ke balok/parapet yang kuat, **bukan sekadar finishing**.

#### C.4 💧 Area Basah Lantai 2 — *Bocor = nightmare*

Laundry dan KM di lantai 2 → risiko bocor dan beban tambahan signifikan.

- Screed kemiringan menambah beban mati.
- Keramik dan waterproofing menambah beban.
- Bak air/water heater jika ada harus diperhitungkan.
- Floor drain dan pipa **tidak boleh asal memotong balok**.

#### C.5 📈 Persiapan Tumbuh 3 Lantai — *Future-proof!*

Catatan teknis di gambar A3 menyebutkan "Struktur disiapkan untuk Tumbuh 3 Lantai" 🏗️📈 Artinya:
- Kolom utama 400×400 mm sudah sesuai.
- Pondasi cakar ayam harus dihitung ulang untuk beban penuh 3 lantai.
- Sloof dan ring balok harus diperkuat sesuai proyeksi penuh.

### D. 📋 Checklist Gambar Struktur — *To-do list engineer*

- [ ] Denah pondasi
- [ ] Denah sloof
- [ ] Denah kolom lengkap dengan kode kolom resmi
- [ ] Denah balok lantai 2 (balok induk + balok anak)
- [ ] Denah pelat lantai 2
- [ ] Detail balok tepi void tangga
- [ ] Detail balok kantilever balkon
- [ ] Detail pelat area KM/laundry (tebal + tulangan)
- [ ] Detail kolom dan tulangan
- [ ] Detail sambungan kolom–balok
- [ ] Detail pondasi cakar ayam (tampak dan potongan)
- [ ] Detail sloof penghubung
- [ ] Overlay dinding Lt.2 vs balok — **pastikan semua dinding di atas balok**
- [ ] Perhitungan struktur oleh engineer sipil (beban 3 lantai)
- [ ] Catatan mutu beton, tulangan, dan selimut beton

---

## VII. ANALISIS PSIKOLOGI ARSITEKTUR

### A. Hierarki Privasi — Sangat Baik

Denah Lantai 2 menunjukkan gradasi yang **sehat secara psikologis**:

```
1. TANGGA ↑           → Transisi dari zona usaha ke zona hunian
   │                     (pergantian "mode mental" dari bekerja ke pulang)
   ▼
2. RUANG TAMU          → Ruang penerima singkat / filter sosial
   │                     (tamu berhenti di sini, tidak masuk lebih dalam)
   ▼
3. DAPUR KERING        → Semi-publik keluarga, aktivitas sosial ringan
   │                     (zona "hidup" yang netral dan hangat)
   ├──▶ LAUNDRY/KM     → Servis — tersembunyi, tidak terekspos tamu
   ▼
4. MUSHOLA             → Anchor emosional, zona tenang
   │                     (tidak di jalur sirkulasi utama = fokus ibadah)
   ▼
5. RUANG KELUARGA      → Inti kehidupan keluarga, dekat balkon
   │                     (cahaya alami, udara segar = pemulihan mental)
   ├──▶ BALKON          → Ruang decompression (keluar sejenak)
   ▼
6. KAMAR TIDUR         → Zona paling privat, terlindungi dari publik
   │
   ├──▶ KT UTAMA       → Aman, jauh dari tangga/tamu
   └──▶ KT TAMBAHAN    → Buffer ke fasad, kontrol privasi via shading
```

Gradasi ini penting karena rumah di atas ruko sering punya **konflik identitas**: sebagian terasa tempat kerja, sebagian tempat pulang. Denah ini mulai memisahkan keduanya.

### B. Rasa "Pulang" (Sense of Arrival)

Pada hunian di atas toko, pengalaman naik tangga adalah **momen psikologis penting**. Tangga harus mengubah suasana dari komersial menjadi domestik.

**Yang perlu dibuat:**
- Pencahayaan tangga hangat (2700–3000K).
- Landing/area atas tangga tidak gelap.
- Elemen penyambut kecil: console, tanaman, artwork, kabinet sepatu, atau dinding tekstur.
- Ruang tamu tidak perlu besar, tapi harus memberi jeda.

> Jika ini dilakukan, penghuni akan merasa **"sudah pulang"**, bukan hanya pindah lantai.

**Yang perlu dijaga:**
- Pintu KM **jangan menjadi visual pertama** saat naik tangga.
- Kamar tidur jangan terlihat dari ruang tamu.
- Meja kerja soldering jangan terlihat langsung dari area sosial.
- Mushola jangan menjadi lorong.

### C. Prospect and Refuge (Jay Appleton)

Ruang nyaman biasanya memberi dua hal: bisa melihat sekitar (prospect), tetapi tetap terlindung (refuge).

| Zona | Prinsip | Penerapan |
|:---|:---|:---|
| **Ruang Keluarga + Balkon** | Prospect | Pandangan keluar, cahaya, rasa kontrol |
| **Kamar Tidur** | Refuge | Dinding solid, posisi ranjang terlindung |
| **Ruang Kerja** | Keduanya | Bisa melihat pintu, tapi tidak terekspos penuh |
| **Mushola** | Refuge kuat | Tenang, fokus, tidak ramai visual |

### D. Beban Kognitif dan Kerapian Visual

Rumah sempit-memanjang dengan banyak fungsi (11 zona) mudah terasa penuh jika terlalu banyak fungsi terbuka. **Storage tertutup menjadi sangat penting:**

- Pantry → kabinet tertutup
- Laundry → storage chemical tertutup
- Ruang kerja → rak tertutup sebagian
- Koridor → jangan dipenuhi lemari acak
- Mushola → storage khusus sajadah/mukena

### E. Kesehatan Tidur

Untuk kamar tidur:
- Hindari ranjang terkena cahaya langsung terlalu keras.
- Hindari kepala ranjang di dinding toilet/shower.
- Pastikan sirkulasi udara baik.
- Kurangi suara dari ruang keluarga dan balkon.
- Jalur listrik aman untuk AC/charger.
- Pintu solid, bukan terlalu tipis.

### F. Kesehatan Kerja (Ruang Soldering)

Ruang soldering harus diperlakukan sebagai **ruang kerja semi-teknis**:

| Risiko | Mitigasi |
|:---|:---|
| Asap flux/solder | Fume extractor ducted ke luar |
| Debu kecil | Ventilasi + lap berkala |
| Kabel dan adaptor banyak | Cord management, terminal aman |
| Panas alat | Meja tahan panas, storage tertutup |
| Postur kerja lama | Kursi ergonomis, task light tidak menyilaukan |

### G. Dual Identity Stress

Penghuni menjalani dua peran (pengusaha + keluarga) di satu bangunan. Tangga menjadi elemen psikologis kunci sebagai **"pemisah dunia."** Desain tangga harus memperkuat transisi ini:
- Perubahan material lantai (toko → tangga → rumah).
- Perubahan pencahayaan (komersial → hangat domestik).
- Perubahan aroma (jika memungkinkan).

### H. Dampak Psikologis per Zona

| Zona | Efek Psikologis | Potensi Masalah |
|:-----|:----------------|:----------------|
| **Tangga** | Transisi mode mental usaha → rumah | Jika gelap/sempit → rasa cemas |
| **Ruang Tamu** | Rasa diterima, kontrol sosial | Jika terlalu kecil → sumpek |
| **Dapur Kering** | Kehangatan, sosial ringan | Jika bau/pengap → mengganggu seluruh lantai |
| **Laundry** | Aktivitas rutin, "behind the scene" | Jika terekspos → rumah terasa berantakan |
| **Mushola** | Ketenangan, centering | Jika jadi jalur lewat → kehilangan sakralitas |
| **Ruang Keluarga** | Pemulihan, kebersamaan | Jika tanpa cahaya alami → depresi ringan |
| **Balkon** | Decompression, koneksi luar | Jika terlalu kecil → hanya ornamen |
| **Ruang Kerja** | Fokus, produktivitas | Jika tanpa exhaust → **bahaya kesehatan** |
| **Kamar Tidur** | Istirahat, rasa aman | Jika dekat area publik → kualitas tidur turun |

### I. Risiko Psikologis yang Perlu Dimitigasi

1. **Klaustrofobia di area tengah** — koridor tengah Lt.2 berpotensi gelap dan sempit tanpa bukaan. Solusi: skylight, roster, atau void kecil.
2. **Kebisingan dari toko** — suara dari Lt.1 bisa naik via tangga. Solusi: pintu tangga di Lt.2, insulasi lantai.
3. **Dual identity stress** — tangga harus memperkuat transisi (perubahan material, pencahayaan, aroma).

---

## VIII. ANALISIS MEP (MEKANIKAL, ELEKTRIKAL, PLUMBING)

### A. Plumbing

#### A.1 Air Bersih

Cluster laundry + KM bagus karena memendekkan jalur pipa.

- Buat shaft min ±300 × 600 mm jika memungkinkan (ideal 400 × 400 mm).
- Pisahkan jalur ke KM umum, KM privat, laundry, dan pantry.
- Siapkan stop kran individual per area.
- Tentukan water heater sejak awal.
- Pipa PPR/HDPE, tekanan min 1,5 bar, header distribusi di Lt.2.

#### A.2 Air Kotor, Air Bekas, dan Vent

| Jenis | Sumber | Catatan |
|:---|:---|:---|
| **Air kotor** | WC | Pipa PVC 4" (110mm), jalur sesingkat mungkin, slope min 2% |
| **Air bekas** | Shower, wastafel, sink, laundry | Pipa PVC 2" (50mm), terpisah dari air kotor |
| **Vent** | Pipa udara | Naik ke atas atap, min 1" (25mm), anti bau siphon trap |

- Letakkan WC sedekat mungkin dengan shaft.
- Hindari terlalu banyak belokan 90°.
- Floor drain laundry dan balkon harus punya trap.
- Buangan AC jangan menetes bebas ke balkon/tetangga.

#### A.3 Diagram Alur Plumbing

```
                    ATAP
                     │ ← Vent pipe
           ┌─────────┤
           │    SHAFT │
    ┌──────┴──┐  ┌───┴────┐
    │ LAUNDRY │  │   KM   │     LANTAI 2
    │(air bkn)│  │(air ktr│
    │ mesin   │  │+air bkn│
    │ cuci    │  │ WC+shwr│
    └────┬────┘  └───┬────┘
         │           │
    ═════╪═══════════╪═════     PELAT LANTAI 2
         │           │
    ┌────┴───────────┴────┐
    │   SHAFT VERTIKAL    │     DINDING
    │   (menerus ke bawah)│
    └─────────┬───────────┘
              │
    ══════════╪════════════     PELAT LANTAI 1
              │
    ┌─────────┴───────────┐
    │  SALURAN HORIZONTAL │     DI BAWAH LANTAI 1
    │  → ke saluran kota  │
    └─────────────────────┘
```

---

### B. Elektrikal

#### B.1 Pembagian Sirkuit

| Sirkuit | MCB | Area |
|:---|:---|:---|
| Lampu umum | C10A | Semua ruang Lt.2 |
| Stopkontak umum | C16A | Ruang tamu, ruang keluarga, kamar |
| AC KT Utama | C16A | Dedicated, kabel 2.5mm² |
| AC KT 2 | C16A | Dedicated |
| AC R.Kerja | C16A | Dedicated (beban alat elektronik tinggi) |
| R.Kerja stopkontak | C16A + ELCB | Solder station, oscilloscope, dll. |
| Pantry/Dapur Kering | C16A | Kulkas, microwave, dispenser |
| Mesin Cuci | C16A | Dedicated |
| Water Heater | C20A | Jika ada |
| **Area Basah (KM+Laundry)** | **ELCB 30mA** | **WAJIB untuk keselamatan** |

**Ruang kerja soldering:** Stopkontak jangan hanya banyak, tapi harus **aman** — grounding wajib, MCB sesuai beban, hindari terminal bertumpuk permanen, exhaust/fan switch terpisah.

#### B.2 Titik Lampu & Stopkontak

| Ruang | Titik Lampu | Stopkontak | Catatan |
|:---|:---|:---|:---|
| Ruang Tamu | 2 (downlight + pendant) | 3 | Warm 3000–3500K |
| Dapur Kering | 2 (general + task) | 4 | Task 4000K di countertop |
| Mushola | 1 (indirect/cove) | 1 | **Lembut, merata, tidak menyilaukan wajah** |
| Ruang Keluarga | 3 (utama + ambient + balkon) | 4 | Dimmer jika memungkinkan |
| Ruang Kerja | 3 (general + 2 task) | **8 min** | 4000–5000K, grounding wajib, kabel 2.5mm² |
| KT Utama | 2 (general + bedside) | 4 | Sakelar hotel (2 titik), warm 2700–3000K |
| KT Tambahan | 2 | 3 | Lampu baca |
| KM | 1 (LED waterproof IP65) | 1 (IP44) | Terang 4000K, tahan lembap |
| Laundry | 1 | 2 | Terang 4000K, ELCB wajib |
| Tangga | 2 (atas + bawah) | 1 | Sakelar hotel, terang-aman |

#### B.3 Panel Distribusi

```
PANEL UTAMA (Lt.1)
├── MCCB 40A → Total bangunan
│   ├── MCB C20A → Lampu + SK Toko (Lt.1)
│   ├── MCB C20A → AC Toko (jika ada)
│   └── ELCB 30mA → Toilet Lt.1 (area basah)
│
└── PANEL DISTRIBUSI (Lt.2)
    ├── MCB C10A → Lampu Lt.2
    ├── MCB C16A → SK Umum
    ├── MCB C16A → AC KT Utama
    ├── MCB C16A → AC KT 2
    ├── MCB C16A → AC R.Kerja
    ├── MCB C16A → SK R.Kerja (dedicated)
    ├── MCB C16A → SK Dapur Kering
    ├── MCB C16A → Mesin Cuci
    ├── MCB C20A → Water Heater
    └── ELCB 30mA → Area Basah (KM + Laundry)
```

---

### C. Ventilasi & Tata Udara

Masalah utama hunian di atas ruko: **panas dan udara terjebak**. Area tengah paling rawan.

| Zona | Kondisi | Strategi |
|:---|:---|:---|
| **Ruang depan** (R.Keluarga, Balkon) | ✅ Baik | Jendela besar + balkon sebagai buffer |
| **Ruang tengah** (Mushola, R.Kerja) | ⚠️ Pengap | Skylight/roster + cross ventilation |
| **Ruang belakang** (R.Tamu, Dapur) | ⚠️ Tergantung bukaan | Jendela/roster ke area belakang |
| **Laundry** | ❌ Risiko tinggi | **Exhaust fan wajib** atau bukaan langsung |
| **Kamar Mandi** | ❌ Tanpa jendela | **Exhaust fan wajib** + timer otomatis |
| **Dapur Kering** | ⚠️ Uap & bau | Cooker hood / exhaust fan |
| **Ruang Kerja** | ❌ Bahaya uap solder | **Fume extraction terarah WAJIB** |
| **Tangga** | ⚠️ Chimney effect | Bukaan atas dikontrol (anti panas & hujan) |

**Cross ventilation:**

```
POTONGAN MELINTANG Lt.2:

    ANGIN MASUK                              ANGIN KELUAR
  (sisi belakang/utara)                    (sisi depan/selatan/balkon)
        ↓                                         ↑
  ┌─────╦═════════════════════════════════════╦─────┐
  │     ║  Laundry → Dapur → Mushola →       ║     │
  │     ║         R.Keluarga → Balkon         ║     │
  └─────╩═════════════════════════════════════╩─────┘
        ↑ roster/jendela                     ↑ bukaan balkon
```

---

### D. Mekanikal

| Sistem | Rekomendasi |
|:---|:---|
| **AC Split** | Kamar tidur (2 unit) + ruang kerja (1 unit) = min 3 unit |
| **Outdoor unit AC** | Area belakang/samping bangunan, **jangan di balkon depan** |
| **Drain AC** | Jangan menetes bebas ke balkon/tetangga |
| **Exhaust fan** | KM, laundry, dapur kering, ruang kerja (4 titik minimum) |
| **Fume extractor** | Ruang kerja — **khusus solder fume, bukan exhaust biasa** |
| **Water pump** | Booster pump di Lt.1 jika tekanan PDAM kurang |
| **Toren air** | Di atap/belakang, kapasitas min 500 liter |

---

## IX. KEAMANAN, KEBAKARAN, DAN EVAKUASI

Bangunan ruko punya risiko khusus: lantai 1 berisi barang dagangan, listrik usaha, dan aktivitas publik.

| Elemen | Status | Rekomendasi |
|:---|:---:|:---|
| Tangga = jalur evakuasi utama | ✅ | **Jangan tutup akses tangga dengan rak/barang toko** |
| Lebar tangga | ✅ 1.200 mm | Memadai untuk evakuasi |
| Smoke detector | ❌ | Wajib di: dekat tangga, ruang keluarga, setiap kamar tidur |
| APAR (pemadam ringan) | ❌ | Min 1 unit Lt.1 (toko), 1 unit Lt.2, 1 kecil di R.Kerja |
| Jalur evakuasi ternotasi | ❌ | Tambahkan arah panah evakuasi |
| Balkon sebagai bantuan evakuasi | ⚠️ | Bantuan visual, **bukan** jalur evakuasi utama |
| Material tahan api | ❓ | Dinding antar-unit min 1 jam tahan api |

---

## X. AKUSTIK DAN BAU

### A. Akustik

| Sumber Bising | Dampak | Mitigasi |
|:---|:---|:---|
| Toko lantai 1 | Suara pelanggan, mesin kasir | Insulasi pelat Lt.2, pintu tangga di Lt.2 |
| Jalan depan | Kendaraan, pedestrian | Fasad double-wall, kaca ganda, shading |
| Tangga | Langkah kaki, suara naik | Pintu tangga Lt.2 |
| Laundry/mesin cuci | Getaran, motor | Anti-vibration pad, dinding ganda, pintu |
| Ruang keluarga/TV | Suara aktivitas | Pintu/partisi ke mushola dan kamar |
| AC outdoor unit | Kompresor | Tempatkan jauh dari kamar tidur |

### B. Bau dan Kelembapan

| Sumber | Mitigasi |
|:---|:---|
| KM | Exhaust, trap floor drain berkualitas |
| Laundry lembap | Exhaust, ventilasi |
| Pantry | Hood/exhaust jika memasak ringan |
| Sepatu/area tangga | Kabinet sepatu berventilasi |
| Ruang kerja (flux) | Fume extractor ducted |

---

## XI. MATERIAL DAN FINISHING KONSEPTUAL

| Area | Material Disarankan |
|:---|:---|
| Toko/open space | Homogeneous tile/keramik kuat, mudah dibersihkan |
| Tangga | Keramik anti-slip atau beton finishing anti-slip |
| Laundry/KM | Keramik anti-slip + waterproofing serius |
| Pantry | Backsplash keramik/solid surface, kabinet tahan lembap |
| Mushola | Lantai hangat/karpet removable, warna tenang |
| Ruang keluarga | Lantai nyaman, storage tertutup |
| Ruang kerja | Lantai mudah dibersihkan, meja tahan panas |
| Kamar tidur | Material akustik lebih lembut, warna tenang |
| Balkon | Keramik outdoor anti-slip, railing aman |

---

## XII. ASPEK REGULASI & KEBERLANJUTAN

### A. Regulasi

| Aspek | Status | Catatan |
|:---|:---:|:---|
| PBG (Persetujuan Bangunan Gedung) | ❓ | Wajib diajukan ke Pemkab Karanganyar |
| KKPR | ❓ | Fungsi komersial perlu konfirmasi |
| IMB/SLF | ❓ | Bangunan komersial-hunian campuran |
| Ketinggian | ✅ | 2 lantai (siap tumbuh 3) — sesuai zona |
| KDB | ⚠️ | 140,80/226 ≈ 62% — perlu cek regulasi lokal |
| KLB | ⚠️ | 281,60/226 ≈ 1,25 — perlu cek regulasi lokal |
| GSB | ❓ | Verifikasi jarak ke jalan |

### B. Keberlanjutan

| Strategi | Implementasi |
|:---|:---|
| Pencahayaan alami | Maksimalkan bukaan depan (balkon) dan belakang |
| Ventilasi alami | Cross ventilation memanfaatkan arah angin dominan |
| Rainwater harvesting | Talang 2 sisi → penampungan → siram tanaman/WC |
| Material lokal | Bata merah, kayu jati (Karanganyar terkenal kayu berkualitas) |
| Iklim mikro | Suhu Karanganyar 24–30°C, relatif sejuk — kurangi ketergantungan AC |
| Green roof | Jika atap dak — potensi untuk roof garden |

---

## XIII. EVALUASI PER RUANG — FORMAT KEPUTUSAN

| Ruang | Dipertahankan? | Alasan | Revisi Penting |
|:---|:---:|:---|:---|
| Toko/open space | ✅ Ya | Fleksibel dan cocok ruko | Tambah akses hunian/servis jelas |
| Tangga belakang | ✅ Ya | Menjaga privasi Lt.2 | Pastikan jumlah step, headroom, balok void |
| R. Tamu dekat tangga | ✅ Ya | Filter sosial bagus | Jangan menghadap langsung toilet |
| Dapur kering dekat tamu | ✅ Ya, kontrol | Sosial dan praktis | Kabinet tertutup, exhaust |
| Laundry dekat tangga | ✅ Ya | Plumbing efisien | Slope, FD, exhaust, storage |
| 2 KM berdekatan | ✅ Ya | Pipa efisien | Privacy door dan shaft |
| Mushola tengah | ✅ Ya | Ruang tenang keluarga | Jangan jadi jalur lewat |
| R. Keluarga depan | ✅ Ya | Paling baik untuk keluarga | Bukaan, shading, akustik |
| R. Kerja kanan | ✅ Ya | Fokus dan privat | **Exhaust soldering, listrik aman** |
| KT Utama | ✅ Ya | Cukup privat | Atur ranjang dan wardrobe |
| KT Tambahan | ✅ Ya | Fungsi keluarga/tamu | Cek panas fasad, ukuran bersih |
| Balkon | ✅ Ya | Nilai psikologis tinggi | Waterproofing, railing, struktur |

---

## XIV. STANDAR UKURAN REKOMENDASI

| Item | Minimum | Nyaman |
|:---|---:|---:|
| Koridor hunian | 900 mm | 1000–1200 mm |
| Pintu kamar | 800 mm | 850–900 mm |
| Pintu KM | 700 mm | 750–800 mm |
| Shower | 800 × 800 mm | 900 × 1200 mm |
| Tangga lebar | 900 mm | 1000–1200 mm |
| Riser tangga | 180 mm maks | 160–175 mm |
| Tread tangga | 260 mm | 280–300 mm |
| Balkon duduk | 1200 mm | 1500 mm |
| Meja kerja solder | 700 mm dalam | 800 mm dalam |
| Pantry bawah | 600 mm dalam | 600–650 mm |
| Lemari pakaian | 600 mm dalam | 600–650 mm |

---

## XV. MATRIKS PRIORITAS REVISI

### Prioritas Tinggi — 🔴 Harus Sebelum Konstruksi

| No | Item | Disiplin |
|:--:|:---|:---|
| 1 | Overlay dinding Lt.2 dengan balok — pastikan semua dinding di atas balok | Struktur |
| 2 | Hitung struktur oleh engineer sipil (beban 3 lantai) | Struktur |
| 3 | Kunci posisi shaft plumbing (laundry + 2 KM) | MEP |
| 4 | Detail balok tepi void tangga | Struktur |
| 5 | Detail waterproofing KM/laundry/balkon Lt.2 | MEP |
| 6 | Pastikan koridor tengah Lt.2 minimal 900 mm bersih | Arsitektur |
| 7 | Cek swing pintu KM — R.Kerja — tangga (tidak bertabrakan) | Arsitektur |

### Prioritas Sedang — 🟡 Sebelum Gambar Kerja Final

| No | Item | Disiplin |
|:--:|:---|:---|
| 8 | Tambahkan grid/as struktur formal (1-3, A-E) | Arsitektur |
| 9 | Rapikan line weight sesuai standar layer | Arsitektur |
| 10 | Tambahkan arah bukaan pintu seluruh ruang | Arsitektur |
| 11 | Layout denah titik lampu, saklar, stopkontak | MEP |
| 12 | Detail balkon: railing, drainase, waterproofing, struktur | Arsitektur + MEP |
| 13 | Buat tampak depan/samping/belakang 1:100 atau 1:50 | Arsitektur |
| 14 | Buat potongan melewati tangga 1:50 | Arsitektur |
| 15 | Buat potongan melewati KM/laundry 1:50 | Arsitektur |

### Prioritas Normal — 🟢 Penyempurnaan

| No | Item | Disiplin |
|:--:|:---|:---|
| 16 | Detail R.Kerja: fume extractor, stopkontak, rak, pencahayaan | MEP + Arsitektur |
| 17 | Isi title block lengkap | Arsitektur |
| 18 | Tambahkan notasi elevasi | Arsitektur |
| 19 | Buat denah atap + kemiringan | Arsitektur |
| 20 | Tambahkan jalur evakuasi kebakaran | Keselamatan |
| 21 | Detail kusen dan bukaan 1:10 | Arsitektur |
| 22 | Detail tangga 1:20 atau 1:10 | Arsitektur |
| 23 | Detail KM 1:20 | Arsitektur |
| 24 | Detail balkon/railing 1:20 atau 1:10 | Arsitektur |

### Prioritas Risiko

| Prio | Risiko | Dampak | Tindakan |
|:---:|:---|:---|:---|
| 1 | Dinding Lt.2 tidak sejajar balok | Retak/struktur tidak efisien | Overlay balok |
| 2 | Void tangga tidak diberi balok tepi | Retak/getaran | Detail balok void |
| 3 | Waterproofing KM/laundry/balkon lemah | Bocor ke Lt.1 | Detail waterproofing |
| 4 | Koridor/pintu bertabrakan | Tidak nyaman harian | Simulasi swing pintu |
| 5 | Exhaust R.Kerja tidak ada | **Risiko kesehatan** | Buat duct/fume extractor |
| 6 | Pantry terlihat berantakan dari tamu | Kualitas ruang turun | Kabinet tertutup/partisi |
| 7 | Lineweight buruk | Gambar sulit dibaca | CTB/layer cleanup |

---

## XVI. DAFTAR GAMBAR KERJA YANG WAJIB DIBUAT

### A. Gambar Arsitektur

- [ ] Denah lantai 1 — skala 1:100
- [ ] Denah lantai 2 — skala 1:100
- [ ] Tampak depan, samping kiri, samping kanan, belakang — 1:100 atau 1:50
- [ ] Potongan melewati tangga — 1:50
- [ ] Potongan melewati KM/laundry — 1:50
- [ ] Detail tangga — 1:20 atau 1:10
- [ ] Detail KM — 1:20
- [ ] Detail balkon/railing — 1:20 atau 1:10
- [ ] Detail kusen dan bukaan — 1:10

### B. Gambar Struktur

- [ ] Denah pondasi
- [ ] Denah sloof
- [ ] Denah kolom
- [ ] Denah balok lantai 2
- [ ] Denah pelat lantai 2
- [ ] Detail tangga struktural
- [ ] Detail balok tepi void
- [ ] Detail balok balkon
- [ ] Detail kolom dan tulangan
- [ ] Catatan mutu beton, tulangan, dan selimut beton

### C. Gambar MEP

- [ ] Denah titik lampu dan saklar
- [ ] Denah stopkontak
- [ ] Single line diagram sederhana
- [ ] Denah air bersih
- [ ] Denah air kotor dan air bekas
- [ ] Denah floor drain
- [ ] Denah exhaust/ventilasi mekanis
- [ ] Denah AC dan drain AC
- [ ] Detail shaft plumbing

---

## XVII. KESIMPULAN

### Kekuatan Desain

1. **Zoning publik-privat yang logis** — Lt.1 fleksibel untuk usaha, Lt.2 privat untuk hunian dengan gradasi yang sehat.
2. **Hierarki privasi yang baik** — tamu tidak langsung masuk ke zona kamar tidur; ruang tamu berfungsi sebagai filter sosial.
3. **Cluster plumbing efisien** — laundry dan KM dikelompokkan, mengurangi panjang pipa dan risiko bocor.
4. **Grid kolom disiplin** — bentang 4.000 × 4.400 mm ideal untuk bangunan 2–3 lantai.
5. **Psikologi ruang yang baik** — mushola sebagai anchor emosional, ruang keluarga dekat balkon sebagai tempat pemulihan, prinsip prospect-refuge terpenuhi.
6. **Persiapan struktural 3 lantai** — kolom utama 400×400 mm, pondasi cakar ayam.
7. **Tangga sebagai transisi psikologis** — potensial menjadi pemisah "dunia kerja" dan "dunia rumah."

### Kelemahan yang Perlu Diatasi

1. **Kelengkapan gambar masih kurang** — grid, elevasi, line weight, detail, layer, dan title block belum lengkap. Gambar **belum bisa digunakan sebagai gambar kerja konstruksi**.
2. **Koordinasi struktur-arsitektur belum terverifikasi** — dinding Lt.2 belum di-overlay dengan balok; ini risiko struktural tertinggi.
3. **MEP belum tergambar** — tidak ada denah plumbing, elektrikal, atau ventilasi dalam paket gambar.
4. **Area tengah Lt.2 berpotensi gelap dan pengap** — perlu strategi skylight, roster, atau void.
5. **Keamanan kebakaran belum dipertimbangkan** — tidak ada jalur evakuasi, APAR, atau smoke detector.
6. **Fume extraction ruang kerja** — untuk fungsi soldering, ini adalah kebutuhan **kesehatan kritis** yang belum terlihat.
7. **Beban kognitif visual** — banyak fungsi dalam ruang terbatas memerlukan storage tertutup yang masif.

### Rekomendasi Akhir

> Desain ini memiliki **fondasi konsep yang kuat dan matang**. Secara arsitektur, karakter yang muncul adalah rumah privat di atas ruang usaha, dengan area keluarga dan balkon sebagai zona pemulihan, ruang tamu dekat tangga sebagai filter sosial, dan mushola sebagai anchor emosional. Ini keputusan psikologis yang baik.
>
> Langkah paling rasional berikutnya adalah:
> 1. **Overlay grid-balok-kolom** di atas denah lantai 2 — pastikan setiap dinding duduk di atas balok.
> 2. **Konsultasi engineer sipil** untuk perhitungan struktur beban 3 lantai.
> 3. **Kunci shaft plumbing** dan buat gambar MEP lengkap.
> 4. **Perbaiki sirkulasi pintu** dan area basah sebelum masuk ke detail fasad/interior.
>
> Setelah keempat hal ini selesai, paket gambar arsitektur, struktur, dan MEP bisa dicetak sebagai dokumen kerja konstruksi.

---

*Dokumen analisis ini dibuat berdasarkan pembacaan visual `emjijsys-Model.pdf`, data dari seluruh dokumen perencanaan terkait, dan prinsip ilmu arsitektur, teknik struktur, psikologi lingkungan (termasuk teori prospect-refuge Jay Appleton), serta standar MEP Indonesia. Dokumen ini bukan pengganti perhitungan struktur/MEP final oleh engineer.*

**Disiapkan oleh:** Antigravity AI — Claude Opus 4.6  
**Tanggal:** 29 Juli 2026  
**Versi:** 2.0  
**Referensi Gambar:** [emjijsys-Model.pdf](file:///d:/cad/emjijsys-Model.pdf) | [emjijsys.dwg](file:///d:/cad/emjijsys.dwg)  
**Dokumen Pendukung:**  
- [emjijsys-analasis.md](file:///d:/cad/emjijsys-analasis.md) — Analisis mendalam arsitektur, struktur, MEP, dan psikologi ruang  
- [emjijsys-antigravity.md](file:///d:/cad/emjijsys-antigravity.md) — Analisis komprehensif V1  
- [analisis_lahan_dasar.md](file:///d:/cad/analisis_lahan_dasar.md) — Data lahan dan lokasi  
- [rencana_ruko_hunian_v1.md](file:///d:/cad/rencana_ruko_hunian_v1.md) — Rencana bangunan  
- [analisis_kenyamanan_tangga.md](file:///d:/cad/analisis_kenyamanan_tangga.md) — Perhitungan tangga  
- [km_kolong_tangga.md](file:///d:/cad/km_kolong_tangga.md) — Analisis KM under-stair  
- [review_km_komersial.md](file:///d:/cad/review_km_komersial.md) — Review ukuran toilet  
- [analisis_kenyamanan_tinggi_km.md](file:///d:/cad/analisis_kenyamanan_tinggi_km.md) — Ergonomi tinggi KM  
