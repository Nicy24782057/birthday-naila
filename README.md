# Birthday Website Naila

## Cara edit foto
Buka `index.html`, cari bagian `const PHOTOS = { ... }`, lalu isi nama file foto.
Contoh:

```js
const PHOTOS = {
  hero: 'naila1.jpg',
  p1: 'naila2.jpg',
  love: 'naila-love.jpg'
};
```

Upload file foto ke folder yang sama dengan `index.html` di GitHub. Nama file harus sama persis.

## Cara tambah musik
Tambahkan file bernama `music.mp3` di folder yang sama dengan `index.html`.

## Cara deploy ke GitHub Pages
1. Buat repository baru di GitHub, misalnya `birthday-naila`.
2. Upload `index.html` ke repository tersebut.
3. Kalau pakai foto/musik, upload juga file foto dan `music.mp3`.
4. Masuk ke **Settings** repository.
5. Pilih **Pages**.
6. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
7. Pilih branch **main** dan folder **/root**.
8. Klik **Save**.
9. Tunggu beberapa menit sampai link GitHub Pages muncul.
