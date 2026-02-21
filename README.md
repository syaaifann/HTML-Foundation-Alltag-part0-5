## 🛠️ Part 0: Instalasi & Anatomi Kerangka

Sebelum kita membuat teks menjadi tebal atau memasukkan video seperti di file `alltag.html`, kita harus menyiapkan "bengkel" kerja kita dan memahami tulang punggung dari sebuah halaman web.

### 📚 Teori Singkat

Berdasarkan file `alltag.html`, setiap dokumen HTML yang benar wajib memiliki lima elemen "Wajib Fardu" agar bisa dibaca dengan sempurna oleh browser:

1. **`<!doctype html>`**: Deklarasi untuk memberi tahu browser bahwa kita menggunakan standar HTML5 terbaru.
2. **`<html>`**: Akar dari semua elemen. Semua kode webmu harus "hidup" di dalam tag ini.
3. **`<head>`**: Bagian "otak" atau metadata. Apapun yang ada di sini tidak akan terlihat langsung di halaman web, tapi sangat penting untuk pengaturan (seperti judul tab).
4. **`<title>`**: Memberi nama pada tab browser kamu.
5. **`<body>`**: Bagian "tubuh". Semua konten (teks, gambar, tombol) yang ingin kamu tunjukkan ke dunia harus diletakkan di sini.

---

### 🛠️ Praktek: "The Setup & First Skeleton"

Mari kita siapkan lingkungan kerjamu agar mirip dengan profesional.

**Langkah 1: Siapkan Senjata**

1. Download dan Install **VS Code** (Visual Studio Code).
2. Buka VS Code, buat folder baru di komputermu bernama `Belajar_HTML`.
3. Di dalam folder tersebut, buat file baru bernama `index.html`.

**Langkah 2: Menulis Kerangka Utama**
Ketikkan kode di bawah ini ke dalam file `index.html` (Ingat, mengetik secara manual akan membuat tanganmu lebih cepat hafal daripada _copy-paste_):

```html
<!doctype html>
<html>
  <head>
    <title>Halaman Pertamaku</title>
  </head>
  <body>
    <h1>Halo Dunia!</h1>
    <p>Saya sedang menyiapkan pondasi web saya sendiri.</p>
  </body>
</html>
```

---

### 🔍 Analisis Kerangka `alltag.html`

Jika kita bedah file `alltag.html` yang kamu unggah, struktur dasarnya adalah:

- **Baris 1-7**: Adalah kerangka standar (Boilerplate). Tanpa baris-baris ini, file HTML-mu hanyalah sekumpulan teks biasa tanpa identitas web.
- **Baris 8-150+**: Adalah isi dari `<body>` yang memberikan tampilan visual ke pengunjung.

---

### 💡 Tantangan untuk Kamu (Challenge)

1. Buka file `index.html` kamu di Google Chrome.
2. Ganti teks di dalam `<title>` menjadi **"Markas Besar [Namamu]"**.
3. Simpan (Ctrl+S) dan Refresh browser. Perhatikan bagian paling atas (Tab Browser), apakah judulnya sudah berubah?
4. Coba tambahkan satu kalimat lagi di bawah tag `<p>`, lalu lihat hasilnya.

---

Gaspol! Kita masuk ke materi yang akan membuat halaman webmu mulai punya "isi". Kalau tadi baru tulang, sekarang kita pasang otot-ototnya.

---

## 🏗️ Part 1: Hierarki Judul & Paragraf

Dalam sebuah koran, ada judul besar, sub-judul, dan isi berita. Di HTML, kita menggunakan **Heading** dan **Paragraph** untuk mengatur tingkatan informasi agar pembaca (dan Google) paham mana yang paling penting.

### 📚 Teori Singkat

Berdasarkan file `alltag.html`, ada dua pemeran utama di sini:

1. **Heading (`<h1>` sampai `<h6>`)**: HTML menyediakan 6 tingkatan judul. `<h1>` adalah yang paling utama (biasanya judul halaman), sementara `<h6>` adalah yang terkecil. Ingat, jangan pilih `h` hanya karena ukuran hurufnya, tapi karena kepentingannya!
2. **Paragraph (`<p>`)**: Digunakan untuk membungkus teks panjang atau isi konten. Browser secara otomatis memberikan sedikit ruang kosong (margin) di atas dan bawah paragraf agar teks tidak terlihat sesak.
3. **Atribut Align**: Di filemu, terdapat penggunaan `align="center"`, `right`, dan `justify`. Meskipun sekarang lebih disarankan pakai CSS, atribut ini adalah cara instan untuk mengatur posisi teks di HTML dasar.

---

### 🛠️ Praktek: Membuat Artikel Sederhana

Mari kita coba menyusun struktur artikel yang rapi di dalam file `index.html` kamu.

**Langkah 1: Edit Isi Body**
Hapus isi `<body>` yang lama, lalu ganti dengan kode berikut:

```html
<h1>Petualangan Menjadi Web Developer</h1>

<h2>Bab 1: Perkenalan Tag Dasar</h2>
<p align="justify">
  HTML adalah langkah awal yang sangat seru. Dengan memahami struktur judul dan
  paragraf, kita bisa membuat konten yang enak dibaca oleh manusia maupun mesin
  pencari.
</p>

<h3>Kenapa Belajar Heading?</h3>
<p align="right">
  Karena struktur yang rapi adalah kunci website yang profesional.
</p>

<hr />
<p align="center">Halaman 1 dari 10</p>
```

---

### 🔍 Analisis "The Power of Hierarchy"

Jika kamu perhatikan di file `alltag.html`:

- **Baris 9-14**: Memperlihatkan perbedaan visual yang mencolok antara `<h1>` (Sangat Besar) hingga `<h6>` (Sangat Kecil).
- **Baris 23-31**: Menunjukkan bagaimana paragraf bisa digeser-geser posisinya hanya dengan satu kata kunci seperti `justify` atau `center`.

> **Tips:** Di satu halaman web, sangat disarankan hanya ada **satu** `<h1>` agar mesin pencari tidak bingung menentukan judul utama websitemu.

---

### 💡 Tantangan untuk Kamu (Challenge)

1. Coba buat sebuah daftar "Top 3 Makanan Favorit".
2. Gunakan `<h2>` sebagai judul daftar.
3. Gunakan `<h4>` untuk nama makanannya, dan `<p>` untuk penjelasan singkat kenapa kamu suka makanan itu.
4. Gunakan `align="right"` khusus pada penjelasan makanan peringkat ke-3.

**Sudah terlihat seperti artikel betulan, kan? Kalau sudah aman, kabari ya, kita lanjut ke Part 2 untuk belajar cara bikin teks jadi Tebal, Miring, dan Bergaris Bawah!**

---

## 🔗 Part 2: Memberi Gaya pada Teks (Text Formatting)

Setelah membuat kerangka dan paragraf, sekarang kita akan belajar cara memberi "tekanan" pada kata-kata tertentu. Di HTML, kita bisa membuat teks menjadi tebal, miring, atau bergaris bawah agar poin penting dalam tulisanmu lebih menonjol.

### 📚 Teori Singkat

Berdasarkan file `alltag.html`, ada dua cara untuk mengubah tampilan teks:

1. **Tag Fisik (Hanya Gaya Visual):**

- **`<b>` (Bold)**: Membuat teks menjadi tebal.
- **`<i>` (Italic)**: Membuat teks menjadi miring.
- **`<u>` (Underline)**: Memberi garis bawah pada teks.

2. **Tag Semantik (Memberi Makna/Penekanan):**

- **`<strong>`**: Secara visual terlihat tebal, namun secara makna memberi tahu browser/mesin pencari bahwa kata tersebut **sangat penting**.
- **`<em>` (Emphasis)**: Secara visual terlihat miring, namun memberi makna bahwa kata tersebut diberi penekanan suara saat dibaca.

3. **Garis Pemisah (`<hr />`)**: Tag ini digunakan untuk membuat garis horizontal guna memisahkan antar bagian materi agar lebih rapi.

---

### 🛠️ Praktek: "The Style Lab"

Mari kita modifikasi file `index.html` kamu untuk mencoba berbagai kombinasi gaya teks.

**Langkah 1: Tambahkan Konten Baru**
Di bawah materi Part 1 sebelumnya, tambahkan kode ini:

```html
<hr />
<h2>Materi Belajar: Gaya Teks</h2>
<p>
  Kadang kita perlu menulis istilah asing dengan <i>miring (italic)</i> atau
  menandai <u>poin yang sudah selesai</u> dengan garis bawah.
</p>

<p>
  <strong>Peringatan:</strong> Jangan lupa untuk
  <b>menyimpan (Save)</b> pekerjaanmu <em>setiap saat</em> agar tidak hilang!
</p>

<p>
  Kombinasi juga bisa:
  <b
    ><i><u>Tebal, Miring, dan Bergaris Bawah sekaligus!</u></i></b
  >
</p>
```

---

### 🔍 Analisis Visual vs Semantik

Jika kamu melihat file `alltag.html`:

- **Baris 16-19**: Menggunakan `<b>`, `<i>`, dan `<u>` untuk modifikasi standar.
- **Baris 36-39**: Menggunakan `<strong>` dan `<em>`.

**Pertanyaannya: Kapan pakai `<b>` dan kapan pakai `<strong>`?**
Secara tampilan, keduanya sama-sama tebal. Namun, bagi pengguna tuna netra yang menggunakan _screen reader_, tag `<strong>` akan dibaca dengan nada bicara yang lebih menekankan, sedangkan `<b>` hanya dianggap teks biasa yang kebetulan tebal.

---

### 💡 Tantangan untuk Kamu (Challenge)

1. Buatlah satu kalimat yang menceritakan hobi kamu.
2. Gunakan tag `<b>` untuk nama hobi kamu.
3. Gunakan tag `<em>` untuk alasan mengapa kamu menyukai hobi tersebut.
4. Tambahkan tag `<hr />` di paling bawah hasil kerjamu hari ini.

**Apakah teks di browsermu sudah berubah gayanya? Jika sudah "tampil beda", kabari ya! Kita akan lanjut ke Part 3 untuk belajar cara memasukkan kutipan (Quotes) dan istilah definisi.**

---

Wah, jeli banget pengamatanmu! Itu terjadi karena di langkah praktek tadi, kita menggunakan **tag sarang (nesting)**.

Coba perhatikan baris ini di kode praktek Part 2 tadi:
`<b><i><u>Tebal, Miring, dan Bergaris Bawah sekaligus!</u></i></b>`

Di situ ada tag `<u>` (**Underline**). Sesuai dengan fungsinya di file `alltag.html`, tag `<u>` akan memberikan garis bawah pada teks yang dibungkusnya.

---

## 🔗 Part 3: Kutipan & Identitas Konten (Quotes & Semantics)

Sekarang kita masuk ke cara "bercerita" yang lebih elegan. Di HTML, kita tidak hanya menulis teks, tapi kita memberi tahu browser: "Hey, ini adalah kata-kata orang bijak!" atau "Ini adalah singkatan!".

### 📚 Teori Singkat

Berdasarkan file `alltag.html`, ada beberapa tag khusus untuk kutipan dan identitas:

1. **`<blockquote>`**: Digunakan untuk kutipan panjang. Browser biasanya akan memberikan margin kiri yang menjorok ke dalam agar terlihat beda dari paragraf biasa.
2. **`<q>` (Short Quote)**: Untuk kutipan pendek di dalam kalimat. Hebatnya, tag ini otomatis akan memberikan tanda petik dua (`"..."`) tanpa perlu kamu ketik manual!
3. **`<cite>`**: Digunakan untuk menyebutkan sumber atau judul buku/karya. Tampilannya biasanya miring secara otomatis.
4. **`<abbr>` (Abbreviation)**: Untuk singkatan. Kamu bisa menambahkan atribut `title` agar ketika kursor diarahkan ke teks tersebut, muncul kepanjangannya.
5. **`<dfn>` (Definition)**: Digunakan untuk menandai istilah yang sedang dijelaskan atau didefinisikan dalam kalimat.

---

### 🛠️ Praktek: "The Wise Page"

Mari kita buat sebuah kutipan keren di file `index.html` kamu agar terlihat seperti blog profesional.

**Langkah 1: Tambahkan Konten Baru**
Letakkan kode ini di bawah materi sebelumnya:

```html
<hr />

<h2>Inspirasi Hari Ini</h2>

<blockquote>
  "Ilmu itu seperti air. Jika ia berhenti mengalir, ia akan menjadi keruh."
</blockquote>

<p>
  Seperti yang tertulis dalam buku <cite>Filosofi Air</cite>, seorang guru
  pernah berkata, <q>Belajarlah setiap hari walau satu baris kode</q>.
</p>

<p>
  Hari ini kita belajar tentang <dfn>HTML</dfn>, yang merupakan singkatan dari
  <abbr title="Hyper Text Markup Language">HTML</abbr>.
</p>
```

---

### 🔍 Analisis "The Auto-Magic"

Jika kamu melihat hasil praktekmu:

- Coba arahkan kursor (hover) ke kata **HTML**. Muncul tulisan kecil "Hyper Text Markup Language" kan? Itu berkat atribut `title` pada tag `<abbr>`.
- Lihat teks di dalam `<q>`. Meskipun kamu tidak mengetik tanda petik, browser akan menambahkannya untukmu.
- Di file `alltag.html` baris 41-55, kamu bisa melihat bagaimana tag-tag ini bekerja sama menciptakan konten yang punya struktur informasi yang kuat.

---

### 💡 Tantangan untuk Kamu (Challenge)

1. Cari satu kutipan favoritmu di internet.
2. Gunakan `<blockquote>` untuk menuliskannya.
3. Di bawahnya, buat kalimat: "Kutipan ini diambil dari [Nama Sumber]". Gunakan tag `<cite>` untuk nama sumbernya.
4. Gunakan tag `<abbr>` untuk menulis singkatan namamu (Misal: `<abbr title="Budi Santoso">BS</abbr>`).

**Gimana? Sudah muncul tanda petik otomatisnya? Kalau sudah, kabari ya! Kita lanjut ke Part 4 untuk belajar rumus kimia dan harga diskon (Subscript & Superscript)!**

---

Siap! Saya mengerti. Garis bawah tersebut muncul karena kita menggabungkan tag `<u>` di akhir contoh tadi. Sesuai permintaanmu, kita hilangkan saja bagian bergaris bawah agar tampilan instruksinya lebih bersih.

Mari kita lanjut ke **Part 4**. Di sini kita akan belajar cara menulis teks yang "naik" atau "turun", serta cara membuat efek coretan untuk harga diskon.

---

## 🔗 Part 4: Transformasi Teks (Del, Ins, Sub, Sup)

Pernah lihat harga coret di toko online atau rumus matematika di buku sekolah? HTML punya tag khusus untuk menangani itu semua tanpa perlu aplikasi desain.

### 📚 Teori Singkat

Berdasarkan file `alltag.html`, ada empat tag penting untuk transformasi posisi dan status teks:

1. **`<del>` (Deleted)**: Memberikan efek coretan garis tengah (strikethrough). Biasanya dipakai untuk harga lama atau informasi yang sudah tidak berlaku.
2. **`<ins>` (Inserted)**: Memberikan garis bawah untuk menandakan teks baru yang ditambahkan. Sering dipasangkan dengan `<del>`.
3. **`<sub>` (Subscript)**: Membuat teks menjadi kecil dan sedikit turun ke bawah. Sangat berguna untuk rumus kimia (seperti ).
4. **`<sup>` (Superscript)**: Membuat teks menjadi kecil dan sedikit naik ke atas. Digunakan untuk pangkat matematika (seperti ) atau catatan kaki.

---

### 🛠️ Praktek: "Toko Kimia & Matematika"

Mari kita coba terapkan tag ini ke dalam file `index.html` kamu.

**Langkah 1: Tambahkan Konten Baru**
Masukkan kode ini di bawah materi sebelumnya:

```html
<hr />

<h2>Promo Laboratorium</h2>
<p>
  Dapatkan cairan <b>H<sub>2</sub>SO<sub>4</sub></b> (Asam Sulfat) sekarang!
</p>

<p>
  Harga Lama: <del>Rp100.000</del> <br />
  Harga Baru: <ins>Rp85.000</ins>
</p>

<p>
  Luas tanah laboratorium ini adalah 100m<sup>2</sup>, hasil dari perhitungan
  10<sup>2</sup>.
</p>
```

---

### 🔍 Analisis "Posisi Tentukan Arti"

Jika kamu melihat file `alltag.html`:

- **Baris 61**: Memperlihatkan harga coret menggunakan `<del>` dan `<ins>`. Ini adalah standar untuk menunjukkan perubahan data.
- **Baris 64-65**: Menunjukkan perbedaan letak antara `sub` (di bawah) dan `sup` (di atas).

> **Tips:** Jangan tertukar! **Sub** (seperti _Submarine_ / Kapal Selam) berarti di bawah, sementara **Sup** (seperti _Superman_ yang terbang) berarti di atas.

---

### 💡 Tantangan untuk Kamu (Challenge)

1. Buatlah sebuah pengumuman diskon untuk barang impianmu.
2. Gunakan `<del>` untuk harga asli dan `<ins>` untuk harga setelah diskon.
3. Tuliskan rumus kimia air () menggunakan tag yang benar.
4. Tuliskan kalimat "Juara ke-1" di mana angka "1" nya berada agak ke atas (menggunakan `sup`).

**Sudah berhasil membuat harga coret dan rumus kimianya? Jika sudah, kabari ya! Kita akan lanjut ke Part 5 untuk belajar cara membuat daftar atau List!**

---

Siap, mari kita naikkan levelnya! Sekarang kita akan belajar cara merapikan informasi yang tadinya berantakan menjadi daftar yang terstruktur. Di HTML, ini disebut sebagai **Lists**.

---

## 🏗️ Part 5: Macam-Macam List (Daftar)

Bayangkan kamu sedang membuat daftar belanja atau langkah-langkah memasak. Jika hanya ditulis dalam satu paragraf, orang akan pusing membacanya. HTML menyediakan tiga cara untuk merapikan data tersebut.

### 📚 Teori Singkat

Berdasarkan file `alltag.html`, ada tiga jenis daftar yang bisa kita gunakan:

1. **Ordered List (`<ol>`)**: Daftar berurutan yang menggunakan angka (1, 2, 3). Cocok untuk tutorial atau langkah-langkah yang tidak boleh tertukar.
2. **Unordered List (`<ul>`)**: Daftar tidak berurutan yang menggunakan simbol (poin/bullet). Cocok untuk daftar barang atau fitur.
3. **Definition List (`<dl>`)**: Daftar yang berisi istilah (`<dt>`) dan penjelasannya (`<dd>`). Ini sangat unik karena tampilannya mirip kamus.
4. **List Item (`<li>`)**: Ini adalah tag wajib di dalam `<ol>` dan `<ul>` untuk membungkus setiap poin daftar.

---

### 🛠️ Praktek: "The Task Master"

Mari kita buat kombinasi daftar di file `index.html` kamu.

**Langkah 1: Tambahkan Konten Baru**
Masukkan kode ini di bawah materi sebelumnya:

```html
<hr />

<h2>Rencana Belajar Web</h2>

<h5>Langkah-langkah (Ordered List):</h5>
<ol>
  <li>Pelajari tag dasar HTML</li>
  <li>
    Praktek membuat struktur halaman
    <ul>
      <li>Gunakan VS Code (Nested List)</li>
    </ul>
  </li>
  <li>Lanjut belajar CSS</li>
</ol>

<h5>Peralatan yang dibutuhkan (Unordered List):</h5>
<ul>
  <li>Laptop atau PC</li>
  <li>Koneksi Internet</li>
  <li>Niat yang kuat</li>
</ul>

<h5>Glosarium Kecil (Definition List):</h5>
<dl>
  <dt>Browser</dt>
  <dd>Aplikasi untuk membuka halaman web (contoh: Chrome).</dd>
  <dt>Tag</dt>
  <dd>Kode penanda dalam HTML yang diapit kurung sudut.</dd>
</dl>
```

---

### 🔍 Analisis "Daftar di Dalam Daftar"

Jika kamu perhatikan file `alltag.html`:

- **Baris 70-80**: Memperlihatkan teknik **Nested List**, yaitu memasukkan daftar ke dalam daftar lainnya. Ini sangat berguna untuk membuat sub-bab atau menu navigasi yang bercabang.
- **Baris 88-93**: Memperlihatkan `<dl>`, `<dt>`, dan `<dd>`. Perhatikan bagaimana browser memberikan ruang menjorok (indentasi) secara otomatis pada bagian `<dd>` (deskripsi).

---

### 💡 Tantangan untuk Kamu (Challenge)

1. Buatlah sebuah **Ordered List** berisi 3 langkah cara membuat kopi/teh favoritmu.
2. Di dalam salah satu langkahnya, masukkan **Unordered List** berisi bahan-bahan yang diperlukan (Gula, Air, dsb).
3. Buat satu **Definition List** untuk menjelaskan apa itu "Kopi" menurut pendapatmu.

**Bagaimana hasilnya? Apakah poin-poinnya sudah muncul dengan rapi? Kalau sudah, kabari ya! Kita akan lanjut ke Part 6 untuk belajar salah satu materi yang paling menantang: Tabel!**

---

Siap! Mari kita masuk ke materi yang akan membuat data kamu terlihat sangat rapi dan profesional. Kita akan belajar tentang **Tabel**.
