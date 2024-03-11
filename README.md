# belajarGIT
Tugas Pemograman Web

Daftar tugas / branch
   1. Tugas-git
   2. Tugas-html
   3. Tugas-css
   4. Tugas-js
   5. Tugas-midProject
   6. Tugas-php
   7. Tugas-finalProject

Daftar perintah GiT
louis@Louisa MINGW64 ~
$ pwd
/c/Users/louis

louis@Louisa MINGW64 ~
$ cd 'Pemograman Web ~ Semester 4'

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4
$ ls
T01-Git/

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4
$ cd 'T01-Git'

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git
$ git config --global user.email "lolonglaw31@gmail.com"


louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git
$ git init
Initialized empty Git repository in C:/Users/louis/Pemograman Web ~ Semester 4/T01-Git/.git/

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git (master)
$ git clone https://github.com/llouisawl/belajarGIT
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git (master)
$ cd belajarGIT

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git branch Tugas-git

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
[Tugas-git 882eeef] Menambahkan file Tugas-git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git merge Tugas-git
Updating e3ede06..882eeef
Fast-forward
 Tugas-git.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 305 bytes | 305.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/llouisawl/belajarGIT
   e3ede06..882eeef  main -> main

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git branch Tugas-html

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html 93f7c2c] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git merge Tugas-html
Updating 882eeef..93f7c2c
Fast-forward
 Tugas-html.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 304 bytes | 304.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/llouisawl/belajarGIT
   882eeef..93f7c2c  main -> main

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git branch Tugas-css

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css 840f1ca] Menambahkan file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git push origin main
Everything up-to-date

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git merge Tugas-css
Updating 93f7c2c..840f1ca
Fast-forward
 Tugas-css.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 258 bytes | 258.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/llouisawl/belajarGIT
   93f7c2c..840f1ca  main -> main

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git branch Tugas-js

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js 4c97c7d] Menambahkan file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git merge Tugas-js
Updating 840f1ca..4c97c7d
Fast-forward
 Tugas-js.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git push origin
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 251 bytes | 251.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/llouisawl/belajarGIT
   840f1ca..4c97c7d  main -> main

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git branch Tugas-midProject

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git checout Tugas-midProject
git: 'checout' is not a git command. See 'git --help'.

The most similar command is
        checkout

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject d1a2155] Menambahkan file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git merge Tugas-midProject
Updating 4c97c7d..d1a2155
Fast-forward
 Tugas-midProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git push origin
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 271 bytes | 271.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/llouisawl/belajarGIT
   4c97c7d..d1a2155  main -> main

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git branch Tugas-php

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php dc98164] Menambahkan file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git merge Tugas-php
Updating d1a2155..dc98164
Fast-forward
 Tugas-php.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git push origin
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 259 bytes | 259.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/llouisawl/belajarGIT
   d1a2155..dc98164  main -> main

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git branch Tugas-finalProject

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject 7f74e7d] Menambahkan file Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git merge Tugas-finalProject
Updating dc98164..7f74e7d
Fast-forward
 Tugas-finalProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

louis@Louisa MINGW64 ~/Pemograman Web ~ Semester 4/T01-Git/belajarGIT (main)
$ git push origin
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 273 bytes | 273.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/llouisawl/belajarGIT
   dc98164..7f74e7d  main -> main
