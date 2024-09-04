# CSS Lanjutan

## Penjelasan Kode

### Variabel CSS

- `:root { --main-color: #4CAF50; }`
  - Variabel CSS (`--main-color`) didefinisikan di dalam `:root` sehingga dapat digunakan di seluruh dokumen CSS.

### Border-radius

- `.box { border-radius: var(--border-radius); }`
  - Properti `border-radius` digunakan untuk membuat sudut elemen menjadi melengkung.

### Overflow

- `.box { overflow: hidden; }`
  - Properti `overflow` mengatur bagaimana konten yang melampaui batas elemen akan ditampilkan. Dalam contoh ini, konten yang melampaui akan disembunyikan.

### Display

- `.inline-box { display: inline-block; }`

  - Properti `display` diatur menjadi `inline-block` sehingga elemen bisa berada di satu baris tetapi masih memiliki ukuran lebar dan tinggi.

- `.hidden-box { display: none; }`
  - Elemen dengan `display: none` tidak akan ditampilkan dan tidak mengambil ruang di halaman.

### Pseudo-class

- `.box:hover { background-color: #8BC34A; }`

  - Pseudo-class `:hover` digunakan untuk mengubah warna latar belakang saat pengguna mengarahkan kursor ke elemen.

- `.input-field:focus { border-color: var(--main-color); }`
  - Pseudo-class `:focus` digunakan untuk mengubah warna border saat elemen input sedang dalam fokus.

### Media Query

- `@media (max-width: 768px) { ... }`
  - Media query digunakan untuk membuat desain responsif, sehingga tampilan elemen akan menyesuaikan dengan lebar layar perangkat.

### Spesifisitas CSS

- `.important-text { color: yellow !important; }`
  - Aturan CSS dengan `!important` memiliki spesifisitas tinggi dan akan mengesampingkan aturan CSS lainnya untuk properti yang sama.

### Komentar CSS

- `/* Ini adalah komentar CSS */`
  - Komentar digunakan untuk memberikan catatan atau penjelasan dalam kode CSS dan tidak akan ditampilkan di browser.

## Kesimpulan

Teknik dan properti yang ditampilkan dalam proyek ini memberikan wawasan tentang bagaimana Anda dapat menggunakan CSS lanjutan untuk menciptakan desain web yang lebih dinamis dan responsif. Dengan memahami konsep-konsep seperti pseudo-class, variabel CSS, media query, dan lainnya, Anda dapat meningkatkan kemampuan dalam mengatur tampilan halaman web.
