Berikut ini adalah penjelasan yang lebih mendetail mengenai hyperlink di setiap halaman, lengkap dengan sintaksisnya:

### 1. **Home (home.html)**

- **Navigasi Antar Halaman**:
  ```html
  <a href="home.html">Home</a> | <a href="profil.html">Profil</a> | <a href="about.html">About</a> | <a href="galery.html">Gallery</a> | <a href="kontak.html">Kontak</a>
  ```
  **Penjelasan**:
  - Tag `<a>` digunakan untuk membuat hyperlink.
  - Atribut `href` menentukan tujuan dari link. Dalam contoh ini, link menuju halaman internal website seperti `home.html`, `profil.html`, dll.
  - Teks di antara tag `<a>` akan tampil di halaman sebagai link yang bisa diklik oleh pengguna.

- **Hyperlink Eksternal (Google)**:
  ```html
  <a href="http://www.google.com">google</a>
  ```
  **Penjelasan**:
  - `href="http://www.google.com"` adalah link eksternal yang mengarahkan pengguna ke situs Google. Ketika diklik, browser akan membuka situs tersebut.
  
- **Hyperlink untuk Email**:
  ```html
  <a href="mailto:adielzbuser1916@gmail.com">email</a>
  ```
  **Penjelasan**:
  - `mailto:` digunakan untuk membuat hyperlink yang membuka aplikasi email di komputer pengguna dengan alamat email yang sudah diisi otomatis (dalam contoh ini, `adielzbuser1916@gmail.com`).

### 2. **Profil (profil.html)**

- **Navigasi Antar Halaman**:
  ```html
  <a href="home.html">Home</a> | <a href="profil.html">Profil</a> | <a href="about.html">About</a> | <a href="galery.html">Gallery</a> | <a href="kontak.html">Kontak</a>
  ```
  **Penjelasan**: Sama seperti pada halaman Home, tag `<a>` digunakan untuk membuat tautan navigasi antar halaman website.

- **Hyperlink Eksternal (LinkedIn)**:
  ```html
  <a href="https://www.linkedin.com">LinkedIn</a>
  ```
  **Penjelasan**:
  - `href="https://www.linkedin.com"` adalah contoh link eksternal menuju situs LinkedIn. Ketika diklik, akan membuka halaman LinkedIn di browser.

### 3. **About (about.html)**

- **Navigasi Antar Halaman**:
  ```html
  <a href="home.html">Home</a> | <a href="profil.html">Profil</a> | <a href="about.html">About</a> | <a href="galery.html">Gallery</a> | <a href="kontak.html">Kontak</a>
  ```
  **Penjelasan**: Tag `<a>` di sini mengarahkan ke halaman Home, Profil, About, Gallery, dan Kontak di situs Anda.

- **Hyperlink Internal ke Halaman Profil**:
  ```html
  <a href="profil.html">Lihat Profil Lengkap</a>
  ```
  **Penjelasan**:
  - Link ini adalah contoh hyperlink internal yang mengarahkan pengguna ke halaman profil (`profil.html`) ketika diklik.

### 4. **Gallery (galery.html)**

- **Navigasi Antar Halaman**:
  ```html
  <a href="home.html">Home</a> | <a href="profil.html">Profil</a> | <a href="about.html">About</a> | <a href="galery.html">Gallery</a> | <a href="kontak.html">Kontak</a>
  ```
  **Penjelasan**: Sama seperti halaman lain, hyperlink navigasi ini menghubungkan halaman Home, Profil, About, Gallery, dan Kontak.

- **Hyperlink untuk Gambar (Opsional)**:
  ```html
  <a href="travel1.jpg">
    <img src="travel1.jpg" alt="Perjalanan ke Gunung">
  </a>
  ```
  **Penjelasan**:
  - `href="travel1.jpg"` memungkinkan gambar dijadikan hyperlink. Ketika pengguna mengklik gambar, gambar tersebut akan terbuka dalam ukuran penuh atau akan diarahkan ke file gambar yang lebih besar.

### 5. **Kontak (kontak.html)**

- **Navigasi Antar Halaman**:
  ```html
  <a href="home.html">Home</a> | <a href="profil.html">Profil</a> | <a href="about.html">About</a> | <a href="galery.html">Gallery</a> | <a href="kontak.html">Kontak</a>
  ```
  **Penjelasan**: Seperti halaman lain, bar navigasi ini memungkinkan pengguna berpindah antar halaman di situs Anda.

- **Formulir dengan Hyperlink Email (mailto)**:
  ```html
  <form action="mailto:adielzbuser1916@gmail.com" method="post" enctype="text/plain">
    <label for="name">Nama:</label>
    <input type="text" id="name" name="name"><br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br>
    <label for="message">Pesan:</label><br>
    <textarea id="message" name="message"></textarea><br>
    <input type="submit" value="Kirim">
  </form>
  ```
  **Penjelasan**:
  - `action="mailto:adielzbuser1916@gmail.com"` memungkinkan formulir dikirimkan ke email tertentu menggunakan aplikasi email default pengguna.
  - `method="post"` menentukan bahwa data formulir akan dikirimkan menggunakan metode POST.
  - `enctype="text/plain"` memastikan bahwa data dikirimkan dalam bentuk teks biasa (plain text).
  - Pengguna bisa mengisi nama, email, dan pesan, kemudian mengklik tombol "Kirim" untuk mengirimkan pesan ke alamat email yang ditentukan.

### **Sintaksis Hyperlink (`<a>`)**:
- **Struktur dasar**: 
  ```html
  <a href="URL atau Nama File">Teks atau Elemen</a>
  ```
  - **`href`**: Atribut yang menentukan tujuan hyperlink. Ini bisa berupa URL lengkap (untuk link eksternal) atau nama file halaman (untuk link internal).
  - **Teks atau Elemen di dalam tag `<a>`**: Ini adalah teks atau elemen (misalnya gambar) yang akan menjadi bagian yang bisa diklik oleh pengguna.
