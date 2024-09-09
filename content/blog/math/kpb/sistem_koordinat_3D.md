---
title: "Sistem Koordinat 3D"
description: ""
summary: ""
date: 2024-09-09T09:58:37+07:00
lastmod: 2024-09-09T09:58:37+07:00
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

### Sistem Koordinat 3 Dimensi

Sistem koordinat tiga dimensi (3D) memungkinkan kita untuk menggambarkan posisi titik dalam ruang. Tidak seperti sistem dua dimensi (2D) yang menggunakan dua sumbu (x dan y), sistem 3D melibatkan tiga sumbu yang saling tegak lurus: sumbu-x, sumbu-y, dan sumbu-z. Sumbu-z ini memberikan dimensi tambahan yang memungkinkan kita menggambarkan ketinggian atau kedalaman dalam ruang.

#### Konsep Pembagian Wilayah: Oktan
{{< picture src="pembagian_wilayah.png" alt="Pembagian wilayah oktan" >}}

Dalam sistem koordinat dua dimensi, kita mengenal empat **kuadran**, yang merupakan hasil pembagian oleh sumbu-x dan sumbu-y. Pada sistem koordinat tiga dimensi, ruang dibagi menjadi delapan wilayah yang dikenal sebagai **oktan**. Oktan adalah hasil dari pembagian oleh ketiga sumbu (x, y, dan z), yang masing-masing bisa bernilai positif atau negatif.

Setiap oktan merepresentasikan kombinasi tanda positif dan negatif dari ketiga sumbu tersebut. Misalnya:
- Oktan pertama adalah wilayah di mana semua nilai koordinat x, y, dan z positif.
- Oktan kedua memiliki nilai x negatif, tetapi y dan z positif.
- Dan seterusnya hingga kita mencakup semua kombinasi.

Pembagian ini membantu kita mengidentifikasi secara tepat di mana sebuah titik berada di ruang tiga dimensi. Misalnya, titik {{< math >}}${(2, 3, -4)}${{< /math >}} berada di oktan keempat karena nilai x dan y positif, tetapi z negatif.

#### Komponen Titik pada Sistem Koordinat

Untuk lebih memahami bagaimana posisi titik bekerja dalam ruang tiga dimensi, mari kita perhatikan bagaimana sebuah komponen koordinat berubah dalam berbagai dimensi.

Misalkan {{< math >}}${x = 1}${{< /math >}}:
- **Dimensi 1**: Jika hanya satu sumbu yang digunakan (misalnya {{< math >}}$x${{< /math >}}), maka {{< math >}}$x = 1${{< /math >}} hanya merepresentasikan **satu titik** di sepanjang sumbu-x. Ini adalah titik spesifik di mana {{< math >}}$x = 1${{< /math >}}, tanpa mempertimbangkan sumbu lain.

- **Dimensi 2**: Ketika kita menambahkan sumbu-y dan mempertahankan {{< math >}}$x = 1${{< /math >}}, posisi ini sekarang membentuk **sebuah garis** vertikal yang sejajar dengan sumbu-y. Setiap nilai {{< math >}}$y${{< /math >}} memungkinkan titik tetap berada pada garis ini dengan {{< math >}}$x${{< /math >}} tetap konstan.

- **Dimensi 3**: Dalam tiga dimensi, dengan {{< math >}}$x = 1${{< /math >}}, kita sekarang memiliki **bidang** yang sejajar dengan sumbu-y dan sumbu-z, yang dikenal sebagai bidang{{< math >}}${yz}${{< /math >}}. Bidang ini mencakup semua nilai {{< math >}}$y${{< /math >}} dan {{< math >}}$z${{< /math >}}, sementara {{< math >}}$x${{< /math >}} tetap konstan.

Hal yang sama berlaku untuk komponen y dan z:
- **1 komponen** titik akan membentuk sebuah bidang, karena dua sumbu lainnya bisa bervariasi tanpa batas.
- **2 komponen** titik akan membentuk sebuah garis, karena hanya satu sumbu yang bervariasi.
- **3 komponen** titik akan menunjukkan posisi **spesifik** dalam ruang 3D, karena tidak ada sumbu yang tersisa untuk bervariasi.

##### Contoh Kasus

1. Jika kita menetapkan {{< math >}}$x = 2${{< /math >}} dalam ruang tiga dimensi, maka kita menciptakan **bidang** di mana semua titik di bidang tersebut memiliki nilai {{< math >}}$x = 2${{< /math >}}, sementara {{< math >}}$y${{< /math >}} dan {{< math >}}$z${{< /math >}} bisa bervariasi.
{{< picture src="contoh1.png" alt="contoh 1" >}}

2. Jika kita menetapkan {{< math >}}$x = 2${{< /math >}} dan {{< math >}}$y = 3${{< /math >}}, maka kita mendapatkan **garis** yang sejajar dengan sumbu-z, karena hanya nilai {{< math >}}$z${{< /math >}} yang bisa berubah.
{{< picture src="contoh2.png" alt="contoh 2" >}}

1. Jika kita menetapkan {{< math >}}$x = 2${{< /math >}}, {{< math >}}$y = 3${{< /math >}}, dan {{< math >}}$z = 5${{< /math >}}, maka kita telah menentukan **satu titik spesifik** di ruang tiga dimensi: {{< math >}}$(2, 3, 5)${{< /math >}}.
{{< picture src="contoh3.png" alt="contoh 3" >}}

#### Kesimpulan:
- **1 komponen** titik (misalnya, {{< math >}}$x${{< /math >}}) akan membentuk sebuah **bidang** yang sejajar dengan dua sumbu lainnya.
- **2 komponen** titik (misalnya, {{< math >}}$x${{< /math >}} dan {{< math >}}$y${{< /math >}}) akan membentuk sebuah **garis** yang sejajar dengan satu sumbu lainnya.
- **3 komponen** titik (misalnya, {{< math >}}$x${{< /math >}}, {{< math >}}$y${{< /math >}}, dan {{< math >}}$z${{< /math >}}) akan menunjukkan **titik** spesifik di ruang tiga dimensi.

#### Rumus pada Dimensi 2 yang Masih Relevan di Dimensi 3

Beberapa rumus dalam sistem koordinat dua dimensi tetap berlaku di tiga dimensi, hanya dengan sedikit penyesuaian. Berikut adalah dua di antaranya yang masih sangat relevan:

1. **Rumus Jarak antara Dua Titik**: Dalam dua dimensi, jarak antara dua titik {{< math >}}$(x_1, y_1)${{< /math >}} dan {{< math >}}$(x_2, y_2)${{< /math >}} dihitung menggunakan rumus Pythagoras:

{{< math class="text-center" >}}
$$
d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}
$$
{{< /math >}}

{{< callout context="tip" title="Did you know?" icon="outline/rocket" >}}

Di dalam tiga dimensi, rumus ini diperluas dengan menambahkan komponen z, sehingga jarak antara dua titik {{< math >}}$(x_1, y_1, z_1)${{< /math >}} dan {{< math >}}$(x_2, y_2, z_2)${{< /math >}} dihitung dengan rumus:

{{< math class="text-center" >}}
$$
d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2 + (z_2 - z_1)^2}
$$
{{< /math >}}

{{< /callout >}}


Contoh: Misalkan kita ingin menghitung jarak antara dua titik {{< math >}}$(1, 2, 3)${{< /math >}} dan {{< math >}}$(4, 6, 8)${{< /math >}}. Dengan menggunakan rumus ini, kita mendapatkan:

{{< math class="text-center" >}}
$$
d = \sqrt{(4 - 1)^2 + (6 - 2)^2 + (8 - 3)^2} = \sqrt{9 + 16 + 25} = \sqrt{50} \approx 7.07
$$
{{< /math >}}

1. **Persamaan Standar Bola**: Sama seperti dalam dua dimensi di mana lingkaran direpresentasikan dengan persamaan:

{{< math class="text-center" >}}
$$
(x - x_0)^2 + (y - y_0)^2 = r^2
$$
{{< /math >}}

{{< callout context="tip" title="Did you know?" icon="outline/rocket" >}}

Dalam tiga dimensi, bentuk bola bisa direpresentasikan dengan persamaan standar:

{{< math class="text-center" >}}
$$
(x - x_0)^2 + (y - y_0)^2 + (z - z_0)^2 = r^2
$$
{{< /math >}}

{{< /callout >}}


Di sini, {{< math >}}$(x_0, y_0, z_0)${{< /math >}} adalah pusat bola dan {{< math >}}$r${{< /math >}} adalah jari-jarinya.

Contoh: Jika bola memiliki pusat di {{< math >}}$(2, -1, 3)${{< /math >}} dan jari-jarinya 5, maka persamaan bola tersebut adalah:

{{< math class="text-center" >}}
$$
(x - 2)^2 + (y +

1)^2 + (z - 3)^2 = 25
$$
{{< /math >}}

---

