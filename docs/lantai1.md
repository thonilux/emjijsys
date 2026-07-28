# Ringkasan Lantai 1 - Ruko Hunian

## Data Umum

| Item | Ukuran / Keterangan |
|---|---:|
| Luas lahan | 9.80 m x 23.06 m = +/- 225.99 m2 |
| Area parkir depan | 9.80 m x 4.00 m = 39.20 m2 |
| Bangunan lantai 1 | 8.80 m x 16.00 m = 140.80 m2 |
| Talang kiri | 0.50 m x 16.00 m |
| Talang kanan | 0.50 m x 16.00 m |
| Sisa belakang | +/- 3.06 m |
| Elevasi lantai utama | +/- 0.00 |
| Toilet bawah bordes | elevasi lantai -0.50 m |

## Grid Struktur

- Grid vertikal/arah lebar: 1, 2, 3.
- Grid horizontal/arah panjang: A, B, C, D, E.
- Jarak grid arah lebar: 4400 mm + 4400 mm.
- Jarak grid arah panjang: 4000 mm + 4000 mm + 4000 mm + 4000 mm.
- Total titik kolom: 3 x 5 = 15 titik.

## Kolom

| Jenis Kolom | Posisi | Ukuran |
|---|---|---:|
| Kolom utama | Sudut bangunan: K1, K3, K13, K15 | 400 x 400 mm |
| Kolom antara | Grid tengah dan sisi antara | 350 x 350 mm |

Catatan: ukuran 350 x 350 mm dan 400 x 400 mm adalah asumsi konseptual konservatif untuk ruko 2 lantai yang disiapkan tumbuh 3 lantai. Final tetap perlu perhitungan struktur oleh insinyur struktur.

## Balok

Balok belum digambar sebagai detail struktur final. Secara layout konseptual, balok mengikuti garis grid utama:

- Balok arah lebar: sepanjang grid A, B, C, D, E dengan bentang antar kolom 4400 mm.
- Balok arah panjang: sepanjang grid 1, 2, 3 dengan bentang antar kolom 4000 mm.
- Balok tepi mengikuti perimeter bangunan 8.80 m x 16.00 m.
- Balok anak kemungkinan diperlukan di area tangga, toilet bawah bordes, dan bukaan fasad depan.

| Elemen | Ukuran Awal Konseptual |
|---|---:|
| Balok induk bentang 4.00-4.40 m | 250 x 500 mm atau 300 x 500 mm |
| Balok tepi/perimeter | minimum konseptual 250 x 450 mm |
| Balok bordes/tangga | 200 x 350 mm sampai 250 x 400 mm |
| Pelat lantai 2 | 120 mm konseptual |

## Zona Ruang Lantai 1

| Zona | Ukuran | Luas |
|---|---:|---:|
| Open space komersial kasar dalam bangunan | +/- 8.50 m x +/- 15.70 m setelah dinding | +/- 133.45 m2 |
| Open space efektif setelah servis/partisi | perkiraan | +/- 120 m2 |
| Tangga U | 3.72 m x 2.50 m | 9.30 m2 |
| Toilet bawah bordes | 1.20 m x 2.50 m | 3.00 m2 |
| Ruang partisi sementara | 3.00 m x 4.00 m | 12.00 m2 |
| Sisa belakang/service yard | 9.80 m x +/- 3.06 m | +/- 29.99 m2 |

## Tangga

- Tipe awal: tangga belok U.
- Revisi konsep: tangga siku / L-shape agar lebih hemat area.
- Zona tangga U awal: 3720 x 2500 mm.
- Zona tangga L konseptual: +/- 3400 x 3200 mm termasuk bordes dan run bawah.
- Bordes: minimum konseptual +/- 1200 mm.
- Riser: 180 mm.
- Tread: 280 mm.
- Total riser: 20.
- Tinggi lantai ke lantai: 3.60 m.
- Bordes berada di elevasi sekitar +1.80 m.

Catatan revisi:

- Tangga U memakan area melebar di belakang kiri.
- Tangga L lebih mudah ditempelkan ke sudut/service block.
- Toilet direvisi menjadi powder room linear 1200 x 2000 mm yang terselip rapi di bawah/tepi run tangga pertama, dengan akses dari open space.
- Detail final perlu cek headroom, jumlah anak tangga, dan ruang bordes.

## Varian Terbaru: Tangga L 20 Step + KM Bawah Tangga

Varian terbaru mengikuti referensi toilet bawah tangga, tetapi tetap memperhitungkan jumlah anak tangga dan headroom.

| Elemen | Ukuran / Perhitungan |
|---|---:|
| Tinggi lantai ke lantai | 3600 mm |
| Jumlah riser | 20 riser |
| Tinggi riser | 180 mm |
| Tread | 280 mm |
| Run bawah | 10 tread x 280 = 2800 mm |
| Bordes | 1200 x 1200 mm |
| Run atas | 10 tread x 280 = 2800 mm |
| Footprint tangga L | +/- 4000 x 4000 mm |
| KM bawah tangga | 1500 x 1200 mm |

Catatan:

- Area bawah anak tangga awal tidak dipakai untuk ruang berdiri karena headroom rendah.
- KM diletakkan di dalam footprint tangga, tepat di bawah zona run atas yang lebih tinggi, bukan di luar tangga dan bukan di bawah step awal.
- Area rendah di bawah run awal lebih cocok untuk storage.
- Pintu KM memakai konsep pintu geser/out-swing agar tidak memakan ruang dalam.

## Revisi Arah Naik untuk Privasi

Varian privasi menukar arah naik tangga:

- Arah naik: dari timur ke barat.
- Tujuan: akses lantai 2 tidak terlalu terbuka dari area toko/open space.
- Run awal berada di sisi timur footprint tangga.
- Setelah bordes, arah tangga bergerak ke barat.
- KM tetap berada di dalam footprint tangga, di bawah run atas.

File DXF varian ini:

- `lantai1_A3_L_stair_east_to_west_privacy.dxf`

## Varian Revisi: Tangga Linear Nempel Tembok

Arahan terbaru:

- Bukan tangga L yang belok keluar ke tengah ruang.
- Semua anak tangga dibuat linear dan menempel ke tembok belakang/utara.
- Arah naik dari timur ke barat.
- KM berada di bawah bagian tangga yang lebih tinggi, tetap di dalam footprint tangga.
- Area bawah anak tangga awal di sisi timur dipakai storage karena headroom rendah.

Perhitungan:

| Elemen | Ukuran / Perhitungan |
|---|---:|
| Tinggi lantai ke lantai | 3600 mm |
| Riser | 20 x 180 mm |
| Tread aktif | 19 x 280 mm |
| Panjang run tangga | 5320 mm |
| Lebar tangga | 1200 mm |
| KM bawah tangga | 1500 x 1200 mm |

File DXF varian ini:

- `lantai1_A3_wall_stair_east_to_west.dxf`

## Toilet Bawah Bordes

- Ukuran: 1200 x 2500 mm.
- Lantai toilet turun: -500 mm dari lantai utama.
- Plafon bersih di bawah bordes: 2180 mm.
- Fungsi disarankan sebagai powder room, bukan kamar mandi penuh.

## MEP Awal

### Plumbing

- Toilet berada di belakang kiri, dekat zona servis.
- Perlu jalur pipa air kotor, air bekas wastafel, floor drain, dan vent.
- Idealnya pipa dibawa ke area belakang/service yard.
- Toilet bawah tangga memerlukan exhaust fan atau ducting bila tidak memiliki bukaan langsung.

### Elektrikal

- Titik lampu sudah dibuat sebagai grid konseptual di open space.
- Belum ada detail saklar, stopkontak, panel listrik, dan jalur conduit.

## Line Weight Gambar Kerja

| Elemen | Ketebalan Garis |
|---|---:|
| Kolom/dinding terpotong | 0.50-0.70 mm |
| Tangga, fixture, pintu, elemen tampak | 0.25-0.35 mm |
| Grid, dimensi, arsir, notasi | 0.13-0.18 mm |

## Status

Denah lantai 1 saat ini cukup sebagai gambar arsitektur awal dan layout struktur grid/kolom. Gambar belum menjadi gambar struktur final karena belum ada detail pondasi, sloof, balok, pelat, tulangan, dan perhitungan beban.
