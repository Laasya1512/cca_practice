
praka@PRAKASH_REDDY MINGW64 ~
$ cd desktop/Practice

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice (master)
$ git init
Initialized empty Git repository in C:/Users/praka/Desktop/Practice/.git/

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice (master)
$ git clone https://github.com/Laasya1512/cca_practice.git
Cloning into 'cca_practice'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice (master)
$ ls
BDA.pdf  cca_practice/

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice (master)
$ cd cca_practice/

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git add BDA.pdf

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git commit -m "Yes"
[main 8c3bc12] Yes
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 BDA.pdf

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git remote add origin https://github.com/Laasya1512/cca_practice.git
error: remote origin already exists.

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.99 MiB | 1.09 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Laasya1512/cca_practice.git
   aaae797..8c3bc12  main -> main
branch 'main' set up to track 'origin/main'.

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

MAKE CHANGES IN THE GITHUB..

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git fetch
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 927 bytes | 84.00 KiB/s, done.
From https://github.com/Laasya1512/cca_practice
   8c3bc12..f810156  main       -> origin/main

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git merge
Updating 8c3bc12..f810156
Fast-forward
 a.txt | 1 +
 1 file changed, 1 insertion(+)

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 1 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 923 bytes | 184.00 KiB/s, done.
From https://github.com/Laasya1512/cca_practice
   f810156..564982f  main       -> origin/main
Updating f810156..564982f
Fast-forward
 a.txt | 1 -
 1 file changed, 1 deletion(-)

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git branch
* main

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git branch -m a1

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (a1)
$ git checkout -b a2
Switched to a new branch 'a2'

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (a2)
$ git branch
  a1
* a2

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (a2)
$ git branch -m main

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git branch -d a2
error: branch 'a2' not found

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git branch -d a1
Deleted branch a1 (was 564982f).

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git branch
* main

praka@PRAKASH_REDDY MINGW64 ~/desktop/Practice/cca_practice (main)
$ git reset --soft main
