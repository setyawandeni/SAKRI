---
title: "Metode_penjumlahan"
description: ""
summary: ""
date: 2024-09-04T07:06:46+07:00
lastmod: 2024-09-04T07:06:46+07:00
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

**Aturan Penjumlahan** (Addition Principle) adalah konsep dasar lain dalam pencacahan yang berbeda dengan Aturan Perkalian. Aturan Penjumlahan digunakan saat kita memiliki beberapa pilihan yang saling eksklusif (tidak dapat terjadi secara bersamaan), dan kita ingin menghitung jumlah total kemungkinan dari semua pilihan tersebut.

### Prinsip Dasar Aturan Penjumlahan
Jika ada dua kejadian atau pilihan yang tidak dapat terjadi pada saat yang sama, dan:
- Kejadian pertama bisa terjadi dengan {{< math >}}$m${{< /math >}} cara,
- Kejadian kedua bisa terjadi dengan {{< math >}}$n${{< /math >}} cara,

maka jumlah total cara untuk salah satu dari dua kejadian tersebut terjadi adalah {{< math >}}$m + n${{< /math >}}.

### Notasi Formal
Jika ada {{< math >}}$k${{< /math >}} kejadian yang berbeda, di mana:
- Kejadian pertama dapat terjadi dengan {{< math >}}$n_1${{< /math >}} cara,
- Kejadian kedua dapat terjadi dengan {{< math >}}$n_2${{< /math >}} cara,
- ...
- Kejadian ke-{{< math >}}$k${{< /math >}} dapat terjadi dengan {{< math >}}$n_k${{< /math >}} cara,

maka jumlah total cara untuk salah satu dari kejadian tersebut terjadi adalah:

{{< math class=text-center >}}

$$
n_1 + n_2 + \dots + n_k
$$

{{< /math >}}

### Intuisi di Balik Prinsip Ini
Aturan Penjumlahan digunakan ketika kita memiliki beberapa opsi atau kejadian yang tidak bisa dipilih atau terjadi pada saat yang sama. Dalam situasi ini, kita tidak mengalikan jumlah cara, tetapi menjumlahkannya karena kita memilih antara satu kejadian atau kejadian lainnya.

### Contoh 1: Memilih Makanan
Misalkan kamu pergi ke sebuah acara yang menawarkan:
- 3 jenis makanan pembuka (A, B, C),
- 4 jenis makanan penutup (X, Y, Z, W).

Namun, kamu hanya bisa memilih **salah satu** antara makanan pembuka atau makanan penutup. Berapa banyak pilihan yang kamu miliki?

- **Langkah 1**: Pilih makanan pembuka. Ada 3 cara.
- **Langkah 2**: Pilih makanan penutup. Ada 4 cara.

Karena kamu hanya bisa memilih salah satu (tidak keduanya), maka menurut Aturan Penjumlahan:

{{< math class=text-center >}}

$$
\text{Total Pilihan} = 3 + 4 = 7 \text{ pilihan}
$$

{{< /math >}}

Jadi, ada 7 pilihan yang bisa kamu buat.

### Contoh 2: Memilih Transportasi
Bayangkan kamu ingin pergi ke suatu tempat dan kamu bisa:
- Menggunakan mobil pribadi (1 cara),
- Menggunakan taksi (3 perusahaan taksi yang berbeda),
- Menggunakan bus (2 rute berbeda).

Kamu hanya bisa memilih **salah satu** dari ketiga jenis transportasi tersebut. Berapa banyak cara kamu bisa memilih transportasi?

- **Langkah 1**: Menggunakan mobil pribadi. Ada 1 cara.
- **Langkah 2**: Menggunakan taksi. Ada 3 cara.
- **Langkah 3**: Menggunakan bus. Ada 2 cara.

Karena kamu hanya bisa memilih salah satu jenis transportasi, maka menurut Aturan Penjumlahan:

{{< math class=text-center >}}

$$
\text{Total Cara} = 1 + 3 + 2 = 6 \text{ cara}
$$

{{< /math >}}

Jadi, ada 6 cara yang berbeda untuk memilih jenis transportasi.

### Kombinasi Aturan Penjumlahan dan Aturan Perkalian
Metode penjumlahan sering digunakan bersama dengan **metode perkalian (Rule of Product)** ketika kita memiliki beberapa tahap atau langkah yang perlu dilakukan.

**Metode Perkalian** digunakan saat kita memiliki beberapa tahapan yang harus dilakukan secara berurutan, dan jumlah total cara adalah hasil kali dari jumlah cara dalam setiap tahap.

**Kombinasi Penjumlahan dan Perkalian** digunakan ketika kita harus melakukan beberapa langkah dengan beberapa opsi dalam setiap langkah, tetapi ada juga beberapa pilihan yang saling eksklusif.

### Contoh Kombinasi Penjumlahan dan Perkalian

**Contoh 1: Memilih Pakaian**

- **Pilihan**:

    - Anda memiliki 3 kaos (A, B, C) dan 2 celana panjang (D, E).
    - Atau Anda bisa memilih dari 2 kemeja (F, G) dan 3 rok (H, I, J).
- **Pertanyaan**: Berapa banyak cara untuk memilih satu set pakaian?

- **Jawaban**:

    - Dari kaos dan celana panjang: {{< math >}}$3 \times 2 = 6${{< /math >}} cara.
    - Dari kemeja dan rok: {{< math >}}$2 \times 3 = 6${{< /math >}} cara.

    Karena kedua pilihan ini saling eksklusif (tidak bisa memilih kaos dan kemeja sekaligus), kita gunakan metode penjumlahan:

    {{< math class=text-center >}}

$$
6 + 6 = 12 \text{ cara total untuk memilih satu set pakaian}
$$

{{< /math >}}

**Contoh 2: Memilih Kursi di Bioskop**

- **Pilihan**:

    - Anda bisa duduk di salah satu dari 5 kursi di baris depan.
    - Atau Anda bisa duduk di salah satu dari 3 kursi di baris belakang.
    - Selain itu, Anda bisa memilih untuk duduk di balkon yang memiliki 4 kursi.
- **Pertanyaan**: Berapa banyak cara untuk memilih satu kursi?

- **Jawaban**:

    - Baris depan: 5 kursi.
    - Baris belakang: 3 kursi.
    - Balkon: 4 kursi.

    Karena setiap pilihan saling eksklusif (tidak bisa duduk di lebih dari satu tempat sekaligus), kita gunakan metode penjumlahan:

    {{< math class=text-center >}}

$$
5 + 3 + 4 = 12 \text{ cara untuk memilih satu kursi}
$$

{{< /math >}}

---

