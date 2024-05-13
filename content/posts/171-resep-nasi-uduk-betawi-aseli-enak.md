---
description: "Variable"
title: "Variable"
slug: variable
future: true
lang: id
language: id
languageCode: id
publishDate: 2021-11-14T17:22:44.865Z 
thumbnail: https://img-global.cpcdn.com/recipes/ab24abffd092d052/682x484cq65/nasi-uduk-betawi-aseli-foto-resep-utama.webp
images:
- https://img-global.cpcdn.com/recipes/ab24abffd092d052/682x484cq65/nasi-uduk-betawi-aseli-foto-resep-utama.webp
image: https://img-global.cpcdn.com/recipes/ab24abffd092d052/682x484cq65/nasi-uduk-betawi-aseli-foto-resep-utama.webp
cover: https://img-global.cpcdn.com/recipes/ab24abffd092d052/682x484cq65/nasi-uduk-betawi-aseli-foto-resep-utama.webp
author: Julian Roy
ratingvalue: 3.5
reviewcount: 13
recipeingredient:
- "beras 3 L"
- "bawang merah 20 siung"
- "jahe 4 ruas"
- "daun salam 10 lembar"
- "sereh 7 batang"
- "santan dari kelapa parut 1 butir"
- "garam secukupnya"
- "penyedap secukupnya"
recipeinstructions:
- "Cuci beras sampai bersih."
- "Siapkan dandang beri saringan beras yg terbuat dari kain, kukus selama 20 mnt"
- "Haluskan bawang merah dan jahe."
- "Masak santan dan bumbu halus tambahkan salam sereh, garam dan penyedap sampai mendidih"
- "Aron beras yg sdh dikukus tadi sampai santam asat."
- "Setelah asat pindahkan ke dandang dan masak sampai matang"
- "Selamat mencoba dan selamat ketagihan"
- "Kalau mau simpel bisa masak dg magic com kok,, tdk merubah rassa..... 😆😀"
categories:
- Resep
tags:
- nasi
- uduk
- betawi

katakunci: nasi uduk betawi 
nutrition: 119 calories
recipecuisine: Indonesian
preptime: "PT16M"
cooktime: "PT35M"
recipeyield: "1"
recipecategory: Lunch
---
## Aturan Dasar Penulisan Variabel

Seperti yang telah dijelaskan sebelumnya, variabel dalam PHP digunakan untuk menyimpan nilai sementara. Variabel ini dapat menampung berbagai jenis data, seperti angka (integer), teks (string), nilai logika (boolean), dan lain sebagainya. Berikut adalah aturan dasar penulisan variabel yang baik dan benar dalam PHP:

* **Diawali dengan Tanda Dollar `$` :** Tanda dollar `$` digunakan untuk menandai awal dari sebuah variabel. Hal ini memberitahu interpreter PHP bahwa teks yang mengikutinya adalah sebuah variabel.
* **Nama Variabel Harus Bermakna dan Mudah Dipahami:** Nama variabel sebaiknya mencerminkan isi data yang disimpannya. Hindari penggunaan nama yang terlalu panjang, rumit, atau tidak relevan. Gunakan nama yang singkat, jelas, dan mudah dipahami agar kode Anda lebih mudah dibaca dan dipahami oleh orang lain.
* **Nama Variabel Tidak Boleh Diawali dengan Angka:** Nama variabel tidak boleh diawali dengan angka. Hal ini karena PHP dapat salah mengartikannya sebagai nilai numerik. 
* **Nama Variabel Boleh Mengandung Angka, Huruf, dan Underscore (_):** Selain tanda dollar ($), nama variabel boleh mengandung huruf, angka, dan underscore (_). Hindari penggunaan karakter lain seperti spasi, tanda baca, dan simbol lainnya.
* **Nama Variabel Case Sensitive:** Perlu diingat bahwa PHP bersifat case sensitive. Artinya, variabel `$nama` berbeda dengan `$Nama`. Oleh karena itu, perhatikan penggunaan huruf besar dan kecil saat mendeklarasikan dan menggunakan variabel.

## Contoh Penulisan Variabel yang Baik dan Salah

**Contoh Penulisan Variabel yang Baik:**

```php
$namaLengkap = "Feri Irawan"; // Menyimpan nama lengkap
$umur = 17; // Menyimpan usia
$hargaBarang = 100000; // Menyimpan harga barang
$isMember = true; // Menyimpan status keanggotaan
$totalBelanja = $hargaBarang * 2; // Menghitung total belanja
```

### **Contoh Penulisan Variabel yang Salah:**

```php
$1nama = "Belajar PHP"; // Salah, diawali dengan angka
$_harga = 25000; // Salah, mengandung karakter yang tidak boleh
$ gaji = 5000000; // Salah, nama tidak mencerminkan isi data
```

### **3. Tips Tambahan untuk Penulisan Variabel yang Baik**

* **Gunakan camelCase atau snake_case:** 
    * **camelCase:** Nama variabel dimulai dengan huruf kecil, diikuti dengan huruf besar di awal setiap kata berikutnya. Contoh: `$namaLengkap`, `$totalBelanja`.
    * **snake_case:** Nama variabel terdiri dari kata-kata yang dipisahkan dengan underscore (_), dan semua hurufnya kecil. Contoh: `$nama_lengkap`, `$total_belanja`.
* **Hindari penggunaan variabel dengan nama yang terlalu panjang atau kompleks:** Gunakan nama yang singkat dan mudah dipahami untuk memudahkan pembacaan kode.
* **Berikan komentar pada kode Anda:** Jelaskan fungsi dan isi variabel dengan komentar untuk meningkatkan keterbacaan kode.
* **Gunakan konstanta untuk nilai yang tidak berubah:** Gunakan kata kunci `const` untuk mendefinisikan nilai yang tidak berubah (konstanta) dan gunakan nama yang jelas dan deskriptif.

## 4. Manfaat Menulis Variabel dengan Baik**

Menulis variabel dengan baik memberikan beberapa manfaat, antara lain:

* **Meningkatkan Keterbacaan Kode:** Kode yang mudah dibaca lebih mudah dipahami dan dipelihara, baik oleh Anda sendiri maupun oleh programmer lain.
* **Meminimalkan Kesalahan:** Penulisan variabel yang konsisten dan terstruktur membantu mengurangi kemungkinan kesalahan ketik dan logis.
* **Meningkatkan Kualitas Kode:** Kode yang rapi dan terstruktur dengan baik menunjukkan profesionalisme dan meningkatkan kualitas keseluruhan kode Anda.

## 5. Kesimpulan**

Menulis variabel dengan baik dan benar merupakan aspek penting dalam pemrograman PHP. Dengan mengikuti aturan dan tips yang telah dijelaskan, Anda dapat meningkatkan keterbacaan, keandalan, dan kualitas kode Anda. 

**Ingatlah:** 
* Konsistensi adalah kunci. Gunakan gaya penamaan yang sama di seluruh kode Anda.
* Dokumentasikan kode Anda dengan jelas dan ringkas.
* Teruslah belajar dan perbarui pengetahuan Anda tentang pemrograman PHP.