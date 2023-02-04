# Rangkuman Video 5:
## Bekerja dengan Git
### Instalasi Git (Windows)
Untuk menginstal Git, kita dapat mengikuti langkah-langkah berikut:
1. Buka situs resmi Git
2. Klik tombol download
3. Klik tombol download for windows
4. Klik tombol next sampai selesai

### Membuat Repository
Repository adalah tempat penyimpanan file yang akan kita gunakan untuk bekerja. Untuk membuat repository, kita dapat run code
```bash
git init
```

### Commit File
```bash
git add (nama file) # menambahkan file ke staging area
git commit -m "(pesan commit)" # mengirim file dari staging area ke repository
git config --global user.name "(nama pengguna)" # mengatur nama pengguna
git config --global user.email "(email pengguna)" # mengatur email pengguna
```

### Checkout
```bash
git log # melihat riwayat commit
git checkout (nama commit) # kembali ke commit sebelumnya
```
### Percobaan
![git-commit](https://user-images.githubusercontent.com/108047880/216768012-e77c40e6-3b07-429e-bc22-bbc0f5bf5743.jpeg)
![git-log](https://user-images.githubusercontent.com/108047880/216768016-76ff52eb-8609-432f-808b-60950ae2d32d.jpeg)
