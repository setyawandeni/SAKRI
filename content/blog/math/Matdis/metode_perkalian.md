---
title: "Metode Perkalian"
description: ""
summary: ""
date: 2024-09-04T06:41:10+07:00
lastmod: 2024-09-04T06:41:10+07:00
draft: false
weight: 50
categories: [math]
tags: []
contributors: []
pinned: false
homepage: false
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---

Metode Fundamental Pencacahan (Fundamental Principle of Counting) adalah prinsip dasar dalam matematika diskrit yang digunakan untuk menghitung jumlah total kemungkinan dari serangkaian pilihan atau langkah. Prinsip ini sangat penting dalam kombinatorika, yaitu cabang matematika yang berkaitan dengan penghitungan, pengaturan, dan kombinasi objek.

### Prinsip Dasar
---
Ketika kita menghadapi situasi di mana kita harus membuat beberapa pilihan secara berurutan, dan setiap pilihan tidak bergantung pada pilihan sebelumnya, maka jumlah total cara untuk membuat semua pilihan tersebut adalah hasil kali dari jumlah cara untuk setiap pilihan.

Jika ada dua langkah atau kejadian yang harus dilakukan secara berurutan, dan:
- Langkah pertama bisa dilakukan dengan {{< math >}}$m${{< /math >}} cara,
- Langkah kedua bisa dilakukan dengan {{< math >}}$n${{< /math >}} cara,

maka jumlah total cara untuk melakukan kedua langkah tersebut secara berurutan adalah {{< math >}}$m \times n${{< /math >}}.

### Generalisasi
Jika ada {{< math >}}$k${{< /math >}} langkah, di mana langkah ke-1 bisa dilakukan dengan {{< math >}}$n_1${{< /math >}} cara, langkah ke-2 dengan {{< math >}}$n_2${{< /math >}} cara, ..., dan langkah ke-{{< math >}}$k${{< /math >}} dengan {{< math >}}$n_k${{< /math >}} cara, maka jumlah total cara untuk melakukan semua langkah tersebut adalah:

{{< math class=text-center >}}

$$
n_1 \times n_2 \times \dots \times n_k
$$

{{< /math >}}

#### Notasi Formal
Jika ada {{< math >}}$k${{< /math >}} langkah atau kejadian, dan:
- Langkah pertama dapat dilakukan dengan {{< math >}}$n_1${{< /math >}} cara,
- Langkah kedua dapat dilakukan dengan {{< math >}}$n_2${{< /math >}} cara,
- ...
- Langkah ke-{{< math >}}$k${{< /math >}} dapat dilakukan dengan {{< math >}}$n_k${{< /math >}} cara,

maka jumlah total cara untuk melakukan semua langkah tersebut adalah:

{{< math class=text-center >}}

$$
n_1 \times n_2 \times \dots \times n_k
$$

{{< /math >}}

#### Intuisi di Balik Prinsip Ini
Intuisi di balik prinsip ini adalah bahwa setiap kali kita membuat sebuah pilihan, pilihan tersebut “membuka” sekumpulan pilihan baru. Oleh karena itu, untuk menghitung semua kombinasi yang mungkin, kita perlu mempertimbangkan semua kemungkinan pada setiap langkah.

Misalkan kita memiliki dua langkah:
1. Langkah pertama: Memilih warna (Merah, Hijau).
2. Langkah kedua: Memilih ukuran (Kecil, Besar).

Jika kita memilih warna Merah, kita masih harus memilih ukuran, yang bisa Kecil atau Besar. Demikian pula, jika kita memilih Hijau, kita juga masih harus memilih antara Kecil dan Besar.

Secara grafis, ini bisa digambarkan sebagai berikut:

- Merah
  - Kecil
  - Besar
- Hijau
  - Kecil
  - Besar

Ini berarti ada 2 cara untuk memilih warna, dan untuk setiap warna, ada 2 cara untuk memilih ukuran. Jadi, total ada {{< math >}}$2 \times 2 = 4${{< /math >}} kombinasi yang mungkin.

### Contoh Rinci

#### Contoh 1: Pilihan Menu Restoran
Bayangkan kamu pergi ke restoran yang menawarkan menu sebagai berikut:
- 3 jenis hidangan pembuka: Sup, Salad, Roti.
- 4 jenis hidangan utama: Ayam, Ikan, Daging Sapi, Vegetarian.
- 2 jenis hidangan penutup: Kue, Es Krim.

Berapa banyak kombinasi yang bisa kamu pilih untuk makan malam 3-kursus?

- **Langkah 1**: Pilih hidangan pembuka. Ada 3 pilihan.
- **Langkah 2**: Pilih hidangan utama. Ada 4 pilihan.
- **Langkah 3**: Pilih hidangan penutup. Ada 2 pilihan.

Menurut Prinsip Dasar:

{{< math class=text-center >}}

$$
\text{Total Kombinasi} = 3 \times 4 \times 2 = 24 \text{ kombinasi}
$$

{{< /math >}}

Jadi, ada 24 kombinasi berbeda dari hidangan pembuka, hidangan utama, dan hidangan penutup yang bisa dipilih.

#### Contoh 2: Nomor Pelat Kendaraan
Misalkan nomor pelat kendaraan terdiri dari:
- 3 huruf, di mana setiap huruf bisa A-Z (26 kemungkinan),
- 4 digit, di mana setiap digit bisa 0-9 (10 kemungkinan).

Berapa banyak kombinasi nomor pelat yang bisa dibuat?

- **Langkah 1**: Pilih huruf pertama. Ada 26 cara.
- **Langkah 2**: Pilih huruf kedua. Ada 26 cara.
- **Langkah 3**: Pilih huruf ketiga. Ada 26 cara.
- **Langkah 4**: Pilih digit pertama. Ada 10 cara.
- **Langkah 5**: Pilih digit kedua. Ada 10 cara.
- **Langkah 6**: Pilih digit ketiga. Ada 10 cara.
- **Langkah 7**: Pilih digit keempat. Ada 10 cara.

Menurut Prinsip Dasar:

{{< math class=text-center >}}

$$
\text{Total Kombinasi} = 26 \times 26 \times 26 \times 10 \times 10 \times 10 \times 10 = 17,576,000 \text{ kombinasi}
$$

{{< /math >}}

Jadi, ada 17.576.000 kemungkinan kombinasi nomor pelat kendaraan.

### Contoh 3: Memilih Pakaian
Misalkan kamu memiliki:
- 3 pilihan baju (A, B, C),
- 2 pilihan celana (X, Y),
- 4 pilihan sepatu (1, 2, 3, 4).

Berapa banyak kombinasi pakaian yang bisa kamu pakai?

- **Langkah 1**: Memilih baju. Ada 3 cara untuk memilih baju.
- **Langkah 2**: Memilih celana. Ada 2 cara untuk memilih celana.
- **Langkah 3**: Memilih sepatu. Ada 4 cara untuk memilih sepatu.

Menurut Metode Fundamental Pencacahan:

{{< math class=text-center >}}

$$
\text{Total Kombinasi} = 3 \times 2 \times 4 = 24 \text{ kombinasi}
$$

{{< /math >}}

Jadi, ada 24 cara berbeda untuk memilih kombinasi baju, celana, dan sepatu.

### Contoh 4: Membuat Kata Sandi
Misalkan kamu ingin membuat kata sandi dengan format:
- 1 huruf kapital (A-Z),
- 1 angka (0-9),
- 1 simbol (misal: @, #, $, %).

Berapa banyak kata sandi yang mungkin?

- **Langkah 1**: Memilih huruf kapital. Ada 26 huruf (A-Z).
- **Langkah 2**: Memilih angka. Ada 10 angka (0-9).
- **Langkah 3**: Memilih simbol. Misalkan ada 4 simbol yang bisa digunakan.

Menurut Metode Fundamental Pencacahan:

{{< math class=text-center >}}

$$
\text{Total Kombinasi} = 26 \times 10 \times 4 = 1040 \text{ kombinasi}
$$

{{< /math >}}

Jadi, ada 1040 kemungkinan kata sandi yang bisa dibuat.

---
