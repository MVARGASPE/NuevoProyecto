# NuevoProyecto
Pagina web con wencomponents, boostrap, js, css, y html

Se procede a realizar un nuevo proyecto git, ya que los anteriores a la hora de hacer push se caían, o presentaba error
se sube maquetación, del avance, aún no conlcuido con las imagenes y el contenido




Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/Wish
$ git init
Initialized empty Git repository in C:/Users/Marcelo/Desktop/Wish/.git/

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/Wish (master)
$ git remote add origin https://github.com/MVARGASPE/NuevoProyecto.git

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/Wish (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        package-lock.json
        package.json
        public/
        src/
        webpack/

nothing added to commit but untracked files present (use "git add" to track)

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/Wish (master)
$ git add *

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/Wish (master)
$ git commit -m "resubiendo archivos"
[master (root-commit) 03a6cd6] resubiendo archivos
 9 files changed, 11527 insertions(+)
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 public/.gitkeep
 create mode 100644 src/index.html
 create mode 100644 src/scripts/index.js
 create mode 100644 src/styles/index.scss
 create mode 100644 webpack/webpack.common.js
 create mode 100644 webpack/webpack.config.dev.js
 create mode 100644 webpack/webpack.config.prod.js

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/Wish (master)
$ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master


Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/Wish (master)
$ git push --set-upstream origin master

To https://github.com/MVARGASPE/NuevoProyecto.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/MVARGASPE/NuevoProyecto.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/Wish (master)
$

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/Wish (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

nothing added to commit but untracked files present (use "git add" to track)

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/Wish (master)
$ git add .gitignore

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/Wish (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore


Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/Wish (master)
$ git commit -m "resubiendo"
[master 1d41005] resubiendo
 1 file changed, 5 insertions(+)
 create mode 100644 .gitignore

Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/Wish (master)
$ git pull
warning: no common commits
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), 1.36 KiB | 8.00 KiB/s, done.
From https://github.com/MVARGASPE/NuevoProyecto
 * [new branch]      master     -> origin/master
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> master


Marcelo@DESKTOP-JRHQF6T MINGW64 ~/Desktop/Wish (master)
$ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master
