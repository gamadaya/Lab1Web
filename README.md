# Laporan Praktikum HTML Dasar

Bdokumentasi langkah demi langkah dari praktikum HTML dasar, lengkap dengan penjelasan elemen, source (input), dan hasil tampilannya pada browser (output).

---

### 1. Membuat Paragraf
**Penjelasan:** 
Tag `<p>` (paragraph) digunakan untuk membuat sebuah paragraf teks pada halaman web. Setiap tag `<p>` akan secara otomatis membuat blok teks baru dengan jarak (margin) di atas dan di bawahnya.

**Input Code:**
```html
    <!-- 1. Membuat Paragraf -->
    <p>Selamat Datang di website praktikum</p>
    <p>Disini kita akan belajar mengenai HTML dasar</p>
    <p>HTML adalah bahasa markup yang digunakan untuk membuat halaman web</p>
    <p>HTML terdiri dari berbagai elemen yang digunakan untuk menyusun konten web</p>
```

**Capture Output:**
![Output Paragraf](<./screenshots/ss1.png)

---

### 2. Membuat Judul
**Penjelasan:** 
HTML menyediakan tag heading mulai dari `<h1>` hingga `<h6>` untuk membuat judul. `<h1>` adalah judul paling utama dengan ukuran font terbesar, sedangkan `<h2>` hingga `<h6>` digunakan untuk subjudul dengan ukuran yang semakin mengecil.

**Input Code:**
```html
    <!-- 2. Membuat Judul -->

    <!-- Ini Contoh Judul -->
    <h1>Praktikum HTML Dasar</h1>

    <!-- Ini Contoh Subjudul -->
    <h2>Pengenalan HTML</h2>
```

**Capture Outt:**pu
![Output Judul](./assets/output-judul.png)

---

### 3. Membuat Format Teks
**Penjelasan:** 
HTML memiliki berbagai tag untuk memformat teks agar lebih menarik dan memiliki makna semantik:
* `<b>`: Menebalkan teks (*bold*).
* `<i>`: Membuat teks miring (*italic*).
* `<u>`: Memberikan garis bawah (*underline*).
* `<strike>`: Mencoret teks (*strikethrough*).
* `<mark>`: Memberikan efek sorot kuning (*highlight*).
* `<code>`: Menampilkan teks dengan gaya font *monospace*, biasanya untuk kode program.
* `<em>`: Memberikan penekanan pada teks (*emphasis*), secara visual mirip dengan `<i>`.

**Input Code:**
```html
    <!--3. Membuat Format Teks -->
    <p><b>HTML</b> adalah singkatan dari <i>Hypertext Markup Language</i></p>
    <p>HTML digunakan untuk membuat <u>halaman web</u> dan <strike>mengatur konten</strike> di dalamnya</p>
    <p>HTML juga dapat digunakan untuk membuat <mark>tabel</mark>, <code>kode program</code>, dan <em>elemen
            multimedia</em></p>
```

**Capture Output:**
![Output Format Teks](./assets/output-format-teks.png)

---

### 4 & 5. Menyisipkan dan Mengatur Ukuran Gambar
**Penjelasan:** 
Tag `<img>` digunakan untuk menyisipkan gambar. Tag ini tidak memiliki tag penutup (self-closing). 
* Atribut `src` menentukan lokasi/path gambar. 
* Atribut `alt` memberikan teks alternatif jika gambar gagal dimuat.
* Atribut `title` memunculkan *tooltip* saat kursor diarahkan ke gambar.
* Atribut `width` dan `height` digunakan untuk mengatur lebar dan tinggi gambar dalam satuan pixel.

**Input Code:**
```html
    <!-- 4. Menyisipkan Gambar -->

    <!-- 5. Mengatur Ukuran Gambar -->
    <h3>Menambahkan Gambar</h3>
    <img src="images/profil.jpg" alt="Foto profil Mahasiswa" title="Foto Profil Mahasiswa" width="200" height="200">
```

**Capture Output:**
![Output Gambar](./assets/output-gambar.png)

---

### 6. Menambahkan Hyperlink
**Penjelasan:** 
Tag `<a>` (anchor) digunakan untuk membuat tautan (link). Atribut `href` berisi alamat URL tujuan, baik itu file HTML lain di dalam komputer (`index.html`) maupun situs web di internet. Tag `<nav>` adalah elemen semantik yang membungkus sekumpulan link navigasi utama.

**Input Code:**
```html
    <!-- 6. Menambahkan HYPERLINK -->

    <!-- Navigasi Halaman -->
    <nav>
        <a href="index.html">Dasar HTML</a>
        <a href="halaman2.html">Halaman 2</a>
        <a href="https://www.google.com">Website Eksternal</a>
    </nav>
```

**Capture Output:**
![Output Hyperlink](./assets/output-hyperlink.png)

---

### 7. Menambahkan List (Daftar)
**Penjelasan:** 
Terdapat dua jenis list utama yang digunakan:
1. `<ul>` (*Unordered List*): Membuat daftar tanpa urutan spesifik, biasanya ditandai dengan titik hitam (bullet).
2. `<ol>` (*Ordered List*): Membuat daftar yang memiliki urutan, biasanya ditandai dengan angka atau huruf berurutan.
Keduanya menggunakan tag `<li>` (*List Item*) di dalamnya untuk mendefinisikan setiap item dalam daftar tersebut.

**Input Code:**
```html
    <!-- 7. Menambahkan List -->

    <h2>Keahlian</h2>
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>
    <h2>Urutan Belajar</h2>
    <ol>
        <li>Mempelajari struktur HTML</li>
        <li>Mempelajari tag dan atribut</li>
        <li>Membuat halaman HTML</li>
        <li>Menguji halaman pada browser</li>
    </ol>
```

**Capture Output:**

![Output List](./assets/output-list.png)

---

### 8. Menambahkan Komentar
**Penjelasan:** 
Komentar di HTML ditulis di antara tanda `<!--` dan `-->`. Komentar berguna untuk memberikan catatan kepada programmer (dokumentasi kode) atau untuk menonaktifkan sementara sebagian kode. Komentar ini akan diabaikan oleh browser dan tidak akan tampil di halaman web.

**Input Code:**
```html
    <!-- 8. Menambahkan Komentar-->

    <!-- Ini adalah komentar dalam HTML -->
     <!-- Komentar ini tidak akan muncul di browser -->
      <!--Komentar dapat digunakan untuk memberikan catatan atau penjelasan pada kode HTML -->
```

*(Komentar tidak memiliki output visual di layar browser, namun dapat dilihat melalui fitur "Inspect Element" atau "View Page Source" pada browser.)*
