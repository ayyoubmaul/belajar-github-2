1. Make directory
2. masuk ke dir baru
3. git init
4. git config user.name isiin username GitHub
5. git config user.email email GitHub
6. git checkout -b main

Project:
1. create repository baru
2. bikin file baru
3. modify existing file
4. create branch baru: `git checkout -b add/file`
5. add new file ke staging: `git add .` atau `git add nama_file1 nama_file2`
5. commit branch baru: `git commit -m "adding readme file"`
6. lihat log: `git log -n2` `-n`: untuk mendefinisikan banyak log commit id yang mau dilihat
7. Menyimpan perubahan ke stash sementara karna masih WIP(work in progress): `git stash`
8. Pindah branch dari add/file ke main:
    - `git checkout -b main` (branch main baru)
    - `git checkout main` (untuk yang udah ada branch main-nya)
9. Kembalikan stash WIP: `git stash pop`
10. Tambahkan beberapa line di test.txt
11. `git add test.txt`
12. Commit perubahan di text.txt: `git commit -m "menambahkan beberapa lines"`
13. Melihat perubahan line di file Readme.md: `git diff Readme.md`
14. Add Readme.md ke staging: `git add Readme.md`
15. Commit perubahan di Readme.md: `git commit -m "menambahkan step git"`
16. Melihat log lebih simple: `git log --oneline`
6. push branch baru ke remote
7. merge branch baru itu ke main
line 5
line 6
line 7
line 8
