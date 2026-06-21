# Cara Pakai dan Deploy Website Ulang Tahun Naila ke GitHub Pages

## 1. Isi folder yang kamu butuhkan
Pastikan folder berisi file berikut:

```text
birthday-naila/
├── index.html
├── README.md
├── CARA_DEPLOY_GITHUB.md
├── naila-hero.jpg        # opsional, foto opening
├── naila-love.jpg        # opsional, foto ending
├── naila1.jpg            # opsional, foto galeri
├── naila2.jpg            # opsional, foto galeri
└── music.mp3             # opsional, musik
```

File wajib hanya `index.html`. Foto dan musik boleh ditambahkan nanti.

## 2. Cara mengganti foto
Buka `index.html`, lalu cari bagian berikut:

```js
const PHOTOS = {
  hero: '',
  p1: '', p2: '', p3: '', p4: '', p5: '', p6: '', p7: '', p8: '', p9: '',
  kampus1: '', kampus2: '', kampus3: '',
  rank2a: '', rank2b: '', rank2c: '',
  r1: '', r2: '', r3: '', r4: '',
  love: ''
};
```

Isi dengan nama file foto kamu, contohnya:

```js
const PHOTOS = {
  hero: 'naila-hero.jpg',
  p1: 'naila1.jpg', p2: 'naila2.jpg', p3: 'naila3.jpg', p4: 'naila4.jpg', p5: 'naila5.jpg', p6: 'naila6.jpg', p7: 'naila7.jpg', p8: 'naila8.jpg', p9: 'naila9.jpg',
  kampus1: 'kampus1.jpg', kampus2: 'kampus2.jpg', kampus3: 'kampus3.jpg',
  rank2a: 'rank2a.jpg', rank2b: 'rank2b.jpg', rank2c: 'rank2c.jpg',
  r1: 'rank1-1.jpg', r2: 'rank1-2.jpg', r3: 'rank1-3.jpg', r4: 'rank1-4.jpg',
  love: 'naila-love.jpg'
};
```

Catatan penting:
- Nama file harus sama persis.
- Jangan pakai spasi supaya aman. Contoh bagus: `naila-hero.jpg`.
- Huruf besar dan kecil berpengaruh di GitHub Pages.

## 3. Cara menambahkan musik
Masukkan file musik ke folder yang sama dengan `index.html`, lalu beri nama:

```text
music.mp3
```

Tombol musik di website akan membaca file tersebut.

## 4. Cara cek di laptop sebelum upload
Cara paling mudah:
1. Klik dua kali file `index.html`.
2. Website akan terbuka di browser.
3. Cek tombol, challenge bunga, quiz, rank section, dan bagian to love.

Cara lebih rapi:
1. Buka folder dengan VS Code.
2. Install extension **Live Server**.
3. Klik kanan `index.html`.
4. Pilih **Open with Live Server**.

## 5. Cara upload ke GitHub
1. Masuk ke GitHub.
2. Klik tombol **New repository**.
3. Isi nama repository, contoh: `birthday-naila`.
4. Pilih **Public**.
5. Klik **Create repository**.
6. Klik **uploading an existing file** atau **Add file > Upload files**.
7. Upload `index.html`, semua foto, dan `music.mp3` kalau ada.
8. Jangan upload ZIP-nya. Yang diupload adalah isi foldernya.
9. Klik **Commit changes**.

## 6. Cara mengaktifkan GitHub Pages
1. Buka repository kamu.
2. Masuk ke **Settings**.
3. Klik menu **Pages**.
4. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
5. Pada bagian **Branch**, pilih:
   - Branch: `main`
   - Folder: `/root`
6. Klik **Save**.
7. Tunggu beberapa menit.
8. Link publik akan muncul di halaman Pages.

Format link biasanya:

```text
https://usernamegithub.github.io/birthday-naila/
```

## 7. Kalau muncul 404
Cek ini:
- File utama harus bernama `index.html`, bukan `Index.html` atau `index.HTML`.
- File `index.html` harus ada di root repository, bukan di dalam folder ZIP.
- GitHub Pages sudah diaktifkan dari branch `main` folder `/root`.
- Tunggu 1 sampai 5 menit setelah deploy.

## 8. Setelah jadi publik
Kirim link GitHub Pages ke Naila.

Contoh pesan:

```text
Naila, aku ada bikin sesuatu kecil buat kamu. Bukanya pelan-pelan yaa:
https://usernamegithub.github.io/birthday-naila/
```
