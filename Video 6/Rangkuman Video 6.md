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

### Percobaan