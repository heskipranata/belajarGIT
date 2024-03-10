Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
…
ACER@MrH MINGW64 /c
$ cd /c/Users/ACER/OneDrive/Dokumen/Informatika\ Sems4/Pemrograman\ Web/Tugas

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas
$ git clone https://github.com/heskipranata/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git remote -v
origin  https://github.com/heskipranata/belajarGIT.git (fetch)
origin  https://github.com/heskipranata/belajarGIT.git (push)

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ code .

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas
$ ls
Quiz.pdf  T01.Git-Github.pdf  belajarGIT/

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas
$ cd belajarGIT

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ ls
README.md

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-git)
$ git branch
* Tugas-git
  main

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-git)
$ ls
README.md  Tugas-Git.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Git.txt

nothing added to commit but untracked files present (use "git add" to track)

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Git.txt


ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-git)
$ git commit -m "Add Tugas-Git.txt"
[Tugas-git 54db571] Add Tugas-Git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Git.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-git)
$ git log --oneline
54db571 (HEAD -> Tugas-git) Add Tugas-Git.txt
86b7277 (origin/main, origin/HEAD, main) Update README
99e49d3 Initial commit

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git merge Tugas-git
Updating 86b7277..54db571
Fast-forward
 Tugas-Git.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Git.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ ls
README.md  Tugas-Git.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 290 bytes | 290.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/heskipranata/belajarGIT.git
   86b7277..54db571  main -> main
ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-html)
$ touch Tugas-HTML.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-html)
$ echo "Ini adalah template pengumpulan tugas HTML" > Tugas-HTML.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-html)
$ git add Tugas-HTML.txt
warning: in the working copy of 'Tugas-HTML.txt', LF will be replaced by CRLF the next time Git touches it

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-HTML.txt


ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-html)
$ git commit m "Add Tugas-HTML.txt(file)"
error: pathspec 'm' did not match any file(s) known to git
error: pathspec 'Add Tugas-HTML.txt(file)' did not match any file(s) known to git

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-html)
$ git commit -m "Add Tugas-HTML.txt(file)"
[Tugas-html 1f59c7e] Add Tugas-HTML.txt(file)
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-HTML.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-html)
$ git log --oneline
1f59c7e (HEAD -> Tugas-html) Add Tugas-HTML.txt(file)
54db571 (origin/main, origin/HEAD, main, Tugas-git) Add Tugas-Git.txt
86b7277 Update README
99e49d3 Initial commit

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git merge Tugas-html
Updating 54db571..1f59c7e
Fast-forward
 Tugas-HTML.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-HTML.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ ls
README.md  Tugas-Git.txt  Tugas-HTML.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-css)
$ touch Tugas-CSS.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-css)
$ ls
README.md  Tugas-CSS.txt  Tugas-Git.txt  Tugas-HTML.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-css)
$ git add Tugas-CSS.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-CSS.txt


ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-css)
$ git commit -m "Add and init tugas-css.txt(file)"
[Tugas-css 38c96ca] Add and init tugas-css.txt(file)
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-CSS.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git merge Tugas-css
Updating 1f59c7e..38c96ca
Fast-forward
 Tugas-CSS.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-CSS.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-js)
$ touch Tugas-JS.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-js)
$ git add Tugas-JS.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-js)
$ git commit -m "Add tugas-js.txt"
[Tugas-js b21477c] Add tugas-js.txt
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-JS.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
nothing to commit, working tree clean

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git merge Tugas-js
Updating 38c96ca..b21477c
Fast-forward
 Tugas-JS.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-JS.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-midProject)
$ git commit -m "Add file tugas-midproject.txt"
[Tugas-midProject 4c5e212] Add file tugas-midproject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
nothing to commit, working tree clean

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git merge Tugas-midProject
Updating b21477c..4c5e212
Fast-forward
 Tugas-midProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ ls
README.md  Tugas-CSS.txt  Tugas-Git.txt  Tugas-HTML.txt  Tugas-JS.txt  Tugas-midProject.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-php)
$ touch Tugas-PHP.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-php)
$ git add .

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-PHP.txt


ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-php)
$ git commit -m "Add tugas-php.txt"
[Tugas-php 49d7aea] Add tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-PHP.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 4 commits.
  (use "git push" to publish your local commits)

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git merge Tugas-php
Updating 4c5e212..49d7aea
Fast-forward
 Tugas-PHP.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-PHP.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-finalProject)
$ git add .

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-finalProject)
$ git commit -m "Add tugas-project.txt"
[Tugas-finalProject 3f4353b] Add tugas-project.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
nothing to commit, working tree clean

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-finalProject)
$ git log --oneline
3f4353b (HEAD -> Tugas-finalProject) Add tugas-project.txt
49d7aea (main, Tugas-php) Add tugas-php.txt
4c5e212 (Tugas-midProject) Add file tugas-midproject.txt
b21477c (Tugas-js) Add tugas-js.txt
38c96ca (Tugas-css) Add and init tugas-css.txt(file)
1f59c7e (Tugas-html) Add Tugas-HTML.txt(file)
54db571 (origin/main, origin/HEAD, Tugas-git) Add Tugas-Git.txt
86b7277 Update README
99e49d3 Initial commit

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
M       README.md
Your branch is ahead of 'origin/main' by 5 commits.
  (use "git push" to publish your local commits)

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 49d7aea..3f4353b
Fast-forward
 Tugas-finalProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

ACER@MrH MINGW64 ~/OneDrive/Dokumen/Informatika Sems4/Pemrograman Web/Tugas/belajarGIT (main)
$ ls
README.md  Tugas-CSS.txt  Tugas-Git.txt  Tugas-HTML.txt  Tugas-JS.txt  Tugas-PHP.txt  Tugas-finalProject.txt  Tugas-midProject.txt


