'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

C:\Users\Denis>echo "# 1" >> README.md

C:\Users\Denis>git init
Initialized empty Git repository in C:/Users/Denis/.git/

C:\Users\Denis>cd dd

C:\Users\Denis\dd>echo "asdsad" README.md
"asdsad" README.md

C:\Users\Denis\dd>echo "asdsad" >> README.md

C:\Users\Denis\dd>git init
Initialized empty Git repository in C:/Users/Denis/dd/.git/

C:\Users\Denis\dd>git add README.md

C:\Users\Denis\dd>git commit -m "first commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Denis@DESKTOP-C9P6BVJ.(none)')

C:\Users\Denis\dd>git config --global user.email "gesong49@gmail.com"

C:\Users\Denis\dd>git config --global user.name "prix11"

C:\Users\Denis\dd>git commit -m "first commit"
[master (root-commit) 6db6f46] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

C:\Users\Denis\dd>git branch -M master

C:\Users\Denis\dd>git remote add origin https://github.com/prix11/1.git

C:\Users\Denis\dd>git push -u origin master

C:\Users\Denis\dd>git push -u origin master
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 216 bytes | 216.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/prix11/1.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

C:\Users\Denis\dd>git push -u origin master
Everything up-to-date
Branch 'master' set up to track remote branch 'master' from 'origin'.

C:\Users\Denis\dd>git push -u origin master
Everything up-to-date
Branch 'master' set up to track remote branch 'master' from 'origin'.

C:\Users\Denis\dd>asd
"asd" не является внутренней или внешней
командой, исполняемой программой или пакетным файлом.

C:\Users\Denis\dd>
C:\Users\Denis\dd>git push -u origin master
Everything up-to-date
Branch 'master' set up to track remote branch 'master' from 'origin'.

C:\Users\Denis\dd>asd
"asd" не является внутренней или внешней
командой, исполняемой программой или пакетным файлом.

C:\Users\Denis\dd>git push -u origin master
Everything up-to-date
Branch 'master' set up to track remote branch 'master' from 'origin'.

C:\Users\Denis\dd>git commit -m "first commit
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

C:\Users\Denis\dd>git init
Reinitialized existing Git repository in C:/Users/Denis/dd/.git/

C:\Users\Denis\dd>git pull
Already up to date.

C:\Users\Denis\dd>git commit -m "first commit
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        sdsd.txt

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\Denis\dd>git add .

C:\Users\Denis\dd>git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

C:\Users\Denis\dd>git add .

C:\Users\Denis\dd>git commit -m "first commit
[master 84dce2c] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 sdsd.txt

C:\Users\Denis\dd>git commit -m "first commit"
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\Denis\dd>git push -u origin master
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 282 bytes | 141.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/prix11/1.git
   6db6f46..84dce2c  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

C:\Users\Denis\dd>git add .

C:\Users\Denis\dd>git commit -m "second commit"
[master 4d444e6] second commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 asdsad.rar

C:\Users\Denis\dd>git push -u origin master
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 327 bytes | 327.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/prix11/1.git
   84dce2c..4d444e6  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.