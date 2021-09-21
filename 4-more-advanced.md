### 04. More Advanced ###  

1. * git reset untuk mengatur ulang (me-reset) index dan bekerja dengan kondisi commit paling baru. Git reset digunakan ketika mempunyai commit baru yang belum dibagikan ke teman kita tetapi saya sudah tidak membutuhkan commit tsb.  
    * git revert digunakan untuk undo perubahan pada commit sebelumnya, dan juga menambahkan perubahan pada project yang telah dimodifikasi. Git revert digunakan ketika commit sudah dilakukan namun ternyata terdapat kesalahan dan harus di-undo.  
2. * git rebase digunakan untuk menerapkan ulang commit ke branch yang lainnya.  
    * git merge digunakan untuk menggabungkan sebuah branch ke branch yang lainnya.  
3. git stash pop membuang stash setelah menerapkannya dan dapat dilakukan bila ingin melakukan apply dan drop sekaligus. Sedangkan stash apply meninggalkannya di stash list karena mungkin dipakai kembali.  
4. Interactive dapat mengubah individual commit pada proses tanpa memindahkan semua commit pada base baru.