# Gym-Git-Exercise-Solutions

# boundle 1

# exercise 1

...bash

$ cd myproject

DeltaC@DESKTOP-TVL8V10 MINGW64 ~/myproject (main)
$ echo " MY Project" > README.md

DeltaC@DESKTOP-TVL8V10 MINGW64 ~/myproject (main)
$ echo "console.log('Hello World!');" > index.js
bash: !': event not found

DeltaC@DESKTOP-TVL8V10 MINGW64 ~/myproject (main)
$ git branch
* main
  master

$ git remote -v
origin  https://github.com/Pu0ch/Gym-Git-Exercise-Solutions (fetch)
origin  https://github.com/Pu0ch/Gym-Git-Exercise-Solutions (push)

DeltaC@DESKTOP-TVL8V10 MINGW64 ~/myproject (main)
$ git push origin main
To https://github.com/Pu0ch/Gym-Git-Exercise-Solutions


$ git remote remove origin

DeltaC@DESKTOP-TVL8V10 MINGW64 ~/myproject (main)
$ git remote add origin https://github.com/Pu0ch/Gym-Git-Exercise-Solutions

DeltaC@DESKTOP-TVL8V10 MINGW64 ~/myproject (main)
$ git remote -v
origin  https://github.com/Pu0ch/Gym-Git-Exercise-Solutions (fetch)
origin  https://github.com/Pu0ch/Gym-Git-Exercise-Solutions (push)

DeltaC@DESKTOP-TVL8V10 MINGW64 ~/myproject (main)
$ git push origin main
To https://github.com/Pu0ch/Gym-Git-Exercise-Solutions

DeltaC@DESKTOP-TVL8V10 MINGW64 ~/myproject (main)
$ git pull --rebase origin main
error: cannot pull with rebase: You have unstaged changes.
error: Please commit or stash them.

DeltaC@DESKTOP-TVL8V10 MINGW64 ~/myproject (main)
$ git push --force origin main
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 8 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (9/9), 952 bytes | 136.00 KiB/s, done.
Total 9 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), done.
To https://github.com/Pu0ch/Gym-Git-Exercise-Solutions
 + 2e52dac...8727d52 main -> main (forced update)

DeltaC@DESKTOP-TVL8V10 MINGW64 ~/myproject (main)
$ git mv readme.md README.md
fatal: not under version control, source=readme.md, destination=README.md

DeltaC@DESKTOP-TVL8V10 MINGW64 ~/myproject (main)
$ git status
On branch main
nothing to commit, working tree clean

DeltaC@DESKTOP-TVL8V10 MINGW64 ~/myproject (main)
$ git pull origin main
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 952 bytes | 29.00 KiB/s, done.
From https://github.com/Pu0ch/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
   8727d52..059a9f3  main       -> origin/main
Updating 8727d52..059a9f3
Fast-forward
 README.md | 1 +
 Readme.md | 0
 2 files changed, 1 insertion(+)
 create mode 100644 README.md
 delete mode 100644 Readme.md

DeltaC@DESKTOP-TVL8V10 MINGW64 ~/myproject (main)
$ git ls-files | grep -i readme
README.md

DeltaC@DESKTOP-TVL8V10 MINGW64 ~/myproject (main)
$
...

# exercise 2