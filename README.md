# belajarGIT
Daftar tugas / branch
  1. Tugas-git
  2. Tugas-html
  3. Tugas-css
  4. Tugas-js
  5. Tugas-midProject
  6. Tugas-php
  7. Tugas-finalProject

Daftar perintah GiT
winat@DESKTOP-8602A3G MINGW64 /d/GIT (master)
$ git clone https://github.com/flowernotflour/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 9 (delta 1), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (9/9), done.
Resolving deltas: 100% (1/1), done.

winat@DESKTOP-8602A3G MINGW64 /d/GIT (master)
$ git init
Reinitialized existing Git repository in D:/GIT/.git/

winat@DESKTOP-8602A3G MINGW64 /d/GIT (master)
$ cd belajarGIT

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-git

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt


winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.email "thessa2705@gmail.com"

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.name "flowernotflour"

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git commit -m "tugasgit"
[Tugas-git 4705f66] tugasgit
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-git
Updating 50399aa..4705f66
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 307 bytes | 102.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/flowernotflour/belajarGIT.git
   50399aa..4705f66  main -> main

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-html

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-html.txt


winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git config --global user.email "thessa2705@gmail.com"

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git config --global user.name "flowernotflour"

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git commit -m "tugashtml"
[Tugas-html dfe9de6] tugashtml
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-html
Updating 4705f66..dfe9de6
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 365 bytes | 182.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/flowernotflour/belajarGIT.git
   4705f66..dfe9de6  main -> main

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-css

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-css.txt


winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git config --global user.email "thessa2705@gmail.com"

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git config --global user.name "flowernotflour"

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git commit -m "tugascss"
[Tugas-css db77c42] tugascss
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
nothing to commit, working tree clean
winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-css
Updating dfe9de6..db77c42
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 368 bytes | 184.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/flowernotflour/belajarGIT.git
   dfe9de6..db77c42  main -> main

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-js

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-js.txt


winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git config --global user.email "thessa2705@gmail.com"

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git config --global user.name "flowernotflour"

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git commit -m "tugasjs"
[Tugas-js 7df5924] tugasjs
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
nothing to commit, working tree clean

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-js
Updating db77c42..7df5924
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 299 bytes | 299.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/flowernotflour/belajarGIT.git
   db77c42..7df5924  main -> main

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-midProject

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-midProject.txt


winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.email "thessa2705@gmail.com"

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.name "flowernotflour"

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "tugasmidProject"
[Tugas-midProject 0a928b3] tugasmidProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
nothing to commit, working tree clean

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-midProject
Updating 7df5924..0a928b3
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 153.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/flowernotflour/belajarGIT.git
   7df5924..0a928b3  main -> main

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-php

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-php.txt


winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git config --global user.email "thessa2705@gmail.com"

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git config --global user.name "flowernotflour"

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git commit -m "tugasphp"
[Tugas-php aee32fc] tugasphp
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
nothing to commit, working tree clean

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-php
Updating 0a928b3..aee32fc
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 307 bytes | 153.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/flowernotflour/belajarGIT.git
   0a928b3..aee32fc  main -> main

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-finalProject

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-finalProject.txt


winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git config --global user.email "thessa2705@gmail.com"

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git config --global user.name "flowernotflour"

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "tugasfinalProject"
[Tugas-finalProject 4546232] tugasfinalProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
nothing to commit, working tree clean

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-finalProject
Updating aee32fc..4546232
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 300 bytes | 150.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/flowernotflour/belajarGIT.git
   aee32fc..4546232  main -> main

winat@DESKTOP-8602A3G MINGW64 /d/GIT/belajarGIT (main)
$
