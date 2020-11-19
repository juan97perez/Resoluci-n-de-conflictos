CarpetaCasa en la carpetaCasa he hecho un pull, he hecho un cambio en el main.java y lo he subido a un repositorio online.


Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/Resoluci-n-de-conflictos (master)
$ git init
Reinitialized existing Git repository in C:/Users/Juanma/Desktop/CarpetaCasa/Resoluci-n-de-conflictos/.git/

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/Resoluci-n-de-conflictos (master)
$ git pull
Already up to date.

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/Resoluci-n-de-conflictos (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/Resoluci-n-de-conflictos (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   EJ1.java

no changes added to commit (use "git add" and/or "git commit -a")

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/Resoluci-n-de-conflictos (master)
$ git add *

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/Resoluci-n-de-conflictos (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   EJ1.java


Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/Resoluci-n-de-conflictos (master)
$ git push https://github.com/juan97perez/Resoluci-n-de-conflictos master
Everything up-to-date

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/Resoluci-n-de-conflictos (master)
$ git commit -m "nueva version"
[master f164b83] nueva version
 1 file changed, 1 insertion(+), 1 deletion(-)

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/Resoluci-n-de-conflictos (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/Resoluci-n-de-conflictos (master)
$ git push https://github.com/juan97perez/Resoluci-n-de-conflictos master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 287 bytes | 287.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/juan97perez/Resoluci-n-de-conflictos
   c6a2dec..f164b83  master -> master

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/Resoluci-n-de-conflictos (master)
$
