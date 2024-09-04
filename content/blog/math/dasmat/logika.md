---
title: "Logika"
description: ""
summary: ""
date: 2024-08-22T08:45:19+07:00
lastmod: 2024-08-22T08:45:19+07:00
draft: true
weight: 50
categories: [math]
tags: []
contributors: []
pinned: false
homepage: false
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---
Dalam mempelajari Logika Matematika, kita selayaknya harus mengetahui tentang macam macam kata yang digunakan untuk menghubungkan kalimat khususnya dalam konteks matematika. Dalam kesempatan ini, saya akan menjelaskan 5 kata hubung, yaitu: *negasi, konjungsi, disjungsi, implikasi, serta biimplikasi*. Berikut ini akan dibahas masing-masing kata hubung kalimat tersebut.

## 1. Negasi (Ingkaran)
---
 <!-- arti dalam bahasa inggris: "The negation of a statement is the denial of the truth value of the statement itself" -->

**Negasi adalah suatu kata yang digunakan untuk menyangkal nilai kebenaran pernyataan yang dinegasikan**. Jika suatu pernyataan bernilai benar, maka negasinya akan bernilai salah, dan sebaliknya. Dalam bahasa sehari-hari, negasi sering diartikan sebagai penyangkalan atau peniadaan.

{{< callout context="note" title="**Definisi Formal**" icon="outline/info-circle" >}}

Jika *p* adalah suatu pernyataan, maka negasi dari *p*, yang dinotasikan dengan ~*p*, adalah pernyataan yang bernilai benar jika dan hanya jika *p* bernilai salah.

{{< /callout >}}

**Contoh:**

* **Pernyataan:** Semua bilangan prima adalah ganjil.
* **Negasi:** Tidak semua bilangan prima adalah ganjil (atau, ada bilangan prima yang genap).

**Simbolisasi:**

Simbol "~" digunakan untuk menyatakan negasi. Misalnya, jika *p* menyatakan "Hari ini hujan", maka ~*p* menyatakan "Hari ini tidak hujan".

**Negasi dari Pernyataan Majemuk:**

* **Konjungsi (dan):** Negasi dari "p dan q" adalah "tidak benar bahwa p dan q", atau setara dengan "~p atau ~q".
* **Disjungsi (atau):** Negasi dari "p atau q" adalah "tidak benar bahwa p atau q", atau setara dengan "~p dan ~q".

**Tabel Kebenaran:**

| p   | ~p  |
|-----|-----|
| B   | S   |
| S   | B   |

**Penerapan dalam Pembuktian:**

Negasi sering digunakan dalam metode pembuktian tidak langsung (proof by contradiction) sayangnya pada kesempatan ini saya hanya akan membahas tentang kata hubung, sehingga materi pembuktian akan saya bahas pada materi berikutnya.

## 2. Konjungsi
---

Konjungsi adalah sebuah operasi logika yang menghubungkan dua atau lebih pernyataan dengan kata penghubung "dan". Dalam notasi logika, konjungsi sering dilambangkan dengan simbol ∧. Konjungsi hanya bernilai benar jika **semua** pernyataan yang dihubungkan bernilai benar. Jika salah satu saja bernilai salah, maka seluruh konjungsi akan bernilai salah.

**Tabel Kebenaran Konjungsi:**

| p   | q   | p ∧ q |
|---|---|---|
| B   | B   | B   |
| B   | S   | S   |
| S   | B   | S   |
| S   | S   | S   |

**Contoh:**

- *x > 5 ∧ x < 10* artinya "x lebih besar dari 5 dan x kurang dari 10". Pernyataan ini hanya benar jika nilai x berada di antara 5 dan 10.

{{< callout context="tip" title="**Negasi dari Konjungsi**" icon="outline/rocket" >}}

Negasi dari konjungsi p ∧ q adalah ~(p ∧ q), yang menurut hukum De Morgan setara dengan ~p ∨ ~q. Artinya, negasi dari "p dan q" adalah "tidak p atau tidak q".

{{< /callout >}}

**Aplikasi Konjungsi:**

Konjungsi memiliki banyak aplikasi dalam berbagai bidang, termasuk:

* **Logika Matematika:** Membentuk pernyataan majemuk, membuktikan teorema.
* **Pemrograman:** Membuat kondisi dalam program, mengontrol aliran program.
* **Basis Data:** Menentukan relasi antara data.
* **Kecerdasan Buatan:** Membangun aturan-aturan dalam sistem pakar.

**Kesimpulan:**

Konjungsi adalah konsep dasar dalam logika matematika yang sangat penting untuk memahami struktur dan kebenaran argumen. Dengan memahami konjungsi, kita dapat menganalisis pernyataan yang lebih kompleks dan membuat keputusan yang lebih baik berdasarkan informasi yang ada.

## 3. Disjungsi

## 4. Implikasi

## 5. Biimplikasi
