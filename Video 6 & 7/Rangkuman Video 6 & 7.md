# Rangkuman Video 6:
## Git Branch dan Merge
### Branch
```bash
git branch (nama branch) # membuat branch baru
git checkout (nama branch) # pindah ke branch yang dituju
```

### Merge
Merge dibagi menjadi 2 jenis, yaitu fast-forward merge dan 3-way merge. Fast-forward merge terjadi ketika branch yang akan digabungkan tidak memiliki commit baru. Sedangkan 3-way merge terjadi ketika branch yang akan digabungkan memiliki commit baru.

Fast-forward merge:
```bash
git merge (nama branch) # menggabungkan branch yang dituju ke branch yang sedang aktif
```

Three-way merge:
```bash
git merge --no-ff (nama branch) # menggabungkan branch yang dituju ke branch yang sedang aktif
```

## Git Merge Conflict
### Apa itu Git Merge Conflict?
Git Merge Conflict terjadi ketika ada perubahan pada file yang sama pada branch yang berbeda. Git tidak dapat menentukan mana yang akan digunakan, sehingga kita perlu memilih mana yang akan kita gunakan.

### Mengatasi Git Merge Conflict
Untuk mengatasi Git Merge Conflict, kita dapat mengikuti langkah-langkah berikut:
1. Lakukan perubahan pada file yang sama pada branch yang berbeda
2. Lakukan merge
3. Git akan menunjukkan perubahan yang terjadi pada file yang sama
4. Pilih mana yang akan kita gunakan
5. Lakukan commit

### Percobaan

