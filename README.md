Daftar tugas / branch
  1. Tugas-git
  2. Tugas-html
  3. Tugas-css
  4. Tugas-js
  5. Tugas-midProject
  6. Tugas-php
  7. Tugas-finalProject
  
Daftar perintah GiT

fachs@Yayan MINGW64 ~
$ cd "C:\Users\fachs\Downloads\Semester 4\Pemrograman Web\Tugas01"

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01
$ git clone https://github.com/Fachsyan/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01
$ git checkout -b Tugas-git
fatal: not a git repository (or any of the parent directories): .git

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01
$ cd belajarGIT

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Git.txt

nothing added to commit but untracked files present (use "git add" to track)

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Git.txt


fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
[Tugas-git a7538f3] Menambahkan Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git merge Tugas-git
Updating 9c0cb65..a7538f3
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 316 bytes | 158.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Fachsyan/belajarGIT.git
   9c0cb65..a7538f3  main -> main

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git branch
  Tugas-git
* main

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-html)
$ touch Tugas-Html.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Html.txt

nothing added to commit but untracked files present (use "git add" to track)

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Html.txt


fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-Html.txt"
[Tugas-html f4e319f] Menambahkan Tugas-Html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git merge Tugas-html
Updating a7538f3..f4e319f
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 347 bytes | 347.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Fachsyan/belajarGIT.git
   a7538f3..f4e319f  main -> main

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-css)
$ touch Tugas-Css.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Css.txt

nothing added to commit but untracked files present (use "git add" to track)

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Css.txt


fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-Css.txt"
[Tugas-css 426219b] Menambahkan Tugas-Css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git merge Tugas-css
Updating f4e319f..426219b
Fast-forward
 Tugas-Css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 373 bytes | 373.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Fachsyan/belajarGIT.git
   f4e319f..426219b  main -> main

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
* main

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-js)
$ touch Tugas-Js.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-Js.txt"
[Tugas-js 8b7b1f3] Menambahkan Tugas-Js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git merge Tugas-js
Updating 426219b..8b7b1f3
Fast-forward
 Tugas-Js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 306.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Fachsyan/belajarGIT.git
   426219b..8b7b1f3  main -> main

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* main

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-midProject)
$ touch Tugas-MidProject.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-MidProject.txt

nothing added to commit but untracked files present (use "git add" to track)

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-MidProject.txt


fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-MidProject.txt"
[Tugas-midProject 59bbe52] Menambahkan Tugas-MidProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git merge Tugas-midProject
Updating 8b7b1f3..59bbe52
Fast-forward
 Tugas-MidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 331 bytes | 331.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Fachsyan/belajarGIT.git
   8b7b1f3..59bbe52  main -> main

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
* main

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-php)
$ touch Tugas-Php.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-Php.txt"
[Tugas-php 29016c4] Menambahkan Tugas-Php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git merge Tugas-php
Updating 59bbe52..29016c4
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 312 bytes | 312.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Fachsyan/belajarGIT.git
   59bbe52..29016c4  main -> main

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-finalProject)
$ touch Tugas-FinalProject.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-FinalProject.txt

nothing added to commit but untracked files present (use "git add" to track)

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-FinalProject.txt


fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-FinalProject.txt"
[Tugas-finalProject 34398a1] Menambahkan Tugas-FinalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 29016c4..34398a1
Fast-forward
 Tugas-FinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 318 bytes | 159.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Fachsyan/belajarGIT.git
   29016c4..34398a1  main -> main

fachs@Yayan MINGW64 ~/Downloads/Semester 4/Pemrograman Web/Tugas01/belajarGIT (main)
$


