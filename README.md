Daftar tugas/branch
Tugas-git
Tugas-html
Tugas-css
Tugas-js
Tugas-midProject
Tugas-php
Tugas-finalProject

Daftar Perintah GIT

lenovo@DESKTOP-1M4NRT2 MINGW64 ~ (master)
$ cd Documents

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents (master)
$ git clone https://github.com/CORECAVE/belajarGIT
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents (master)
$ cd belajarGIT

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git branch
* main

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-git; git branch Tugas-html; git branch Tugas-css; git branch Tugas-js; git branch Tugas-midProject; git branch Tugas-php; git branch Tugas-finalProject

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m Update Tugas-git.txt
[Tugas-git 6d9ca5c] Update
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-git
Updating 49364be..6d9ca5c
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-git
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 297 bytes | 297.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-git' on GitHub by visiting:
remote:      https://github.com/CORECAVE/belajarGIT/pull/new/Tugas-git
remote:
To https://github.com/CORECAVE/belajarGIT
 * [new branch]      Tugas-git -> Tugas-git

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m Update Tugas-html.txt
[Tugas-html 74f7241] Update
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-html
Merge made by the 'ort' strategy.
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-html
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 299 bytes | 299.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-html' on GitHub by visiting:
remote:      https://github.com/CORECAVE/belajarGIT/pull/new/Tugas-html
remote:
To https://github.com/CORECAVE/belajarGIT
 * [new branch]      Tugas-html -> Tugas-html

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m Update Tugas-css.txt
[Tugas-css 5d7bc08] Update
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-css
Merge made by the 'ort' strategy.
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-css
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 296 bytes | 296.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-css' on GitHub by visiting:
remote:      https://github.com/CORECAVE/belajarGIT/pull/new/Tugas-css
remote:
To https://github.com/CORECAVE/belajarGIT
 * [new branch]      Tugas-css -> Tugas-css

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m Update Tugas-js.txt
[Tugas-js c56e687] Update
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 5 commits.
  (use "git push" to publish your local commits)

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-js
Merge made by the 'ort' strategy.
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-js
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 294 bytes | 147.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-js' on GitHub by visiting:
remote:      https://github.com/CORECAVE/belajarGIT/pull/new/Tugas-js
remote:
To https://github.com/CORECAVE/belajarGIT
 * [new branch]      Tugas-js -> Tugas-js

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m Update Tugas-midProject.txt
[Tugas-midProject 206b592] Update
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 7 commits.
  (use "git push" to publish your local commits)

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-midProject
Merge made by the 'ort' strategy.
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-midProject
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 310 bytes | 310.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-midProject' on GitHub by visiting:
remote:      https://github.com/CORECAVE/belajarGIT/pull/new/Tugas-midProject
remote:
To https://github.com/CORECAVE/belajarGIT
 * [new branch]      Tugas-midProject -> Tugas-midProject

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m Update Tugas-php.txt
[Tugas-php 7840dab] Update
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 9 commits.
  (use "git push" to publish your local commits)

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-php
Merge made by the 'ort' strategy.
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-php
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 297 bytes | 148.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-php' on GitHub by visiting:
remote:      https://github.com/CORECAVE/belajarGIT/pull/new/Tugas-php
remote:
To https://github.com/CORECAVE/belajarGIT
 * [new branch]      Tugas-php -> Tugas-php

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m Update Tugas-finalProject.txt
[Tugas-finalProject 0ce039e] Update
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 11 commits.
  (use "git push" to publish your local commits)

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalProject
Merge made by the 'ort' strategy.
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

lenovo@DESKTOP-1M4NRT2 MINGW64 ~/Documents/belajarGIT (main)
$ git push origin Tugas-finalProject
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 316 bytes | 316.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-finalProject' on GitHub by visiting:
remote:      https://github.com/CORECAVE/belajarGIT/pull/new/Tugas-finalProject
remote:
To https://github.com/CORECAVE/belajarGIT
 * [new branch]      Tugas-finalProject -> Tugas-finalProject



