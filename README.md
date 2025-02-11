SAPCT@CC-PC090 MINGW64 /d
$ git clone https://github.com/varun7537/GitPracticalno4.git
Cloning into 'GitPracticalno4'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

SAPCT@CC-PC090 MINGW64 /d
$ cd GitPracticalno4

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (main)
$ git checkout -b mynewgitbranch
Switched to a new branch 'mynewgitbranch'

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (mynewgitbranch)
$ touch index.html

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (mynewgitbranch)
$ touch style.css

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (mynewgitbranch)
$ touch script.js

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (mynewgitbranch)
$ touch config.php

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (mynewgitbranch)
$ ls
README.md  config.php  index.html  script.js  style.css

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (mynewgitbranch)
$ git add --all

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (mynewgitbranch)
$ git status
On branch mynewgitbranch
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   config.php
        new file:   index.html
        new file:   script.js
        new file:   style.css


SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (mynewgitbranch)
$ git commit -m "Describe your changes"
[mynewgitbranch 5f4697d] Describe your changes
 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 config.php
 create mode 100644 index.html
 create mode 100644 script.js
 create mode 100644 style.css

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (mynewgitbranch)
$ git push origin
fatal: The current branch mynewgitbranch has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin mynewgitbranch

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (mynewgitbranch)
$ git push origin mynewgitbranch
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/varun7537/GitPracticalno4.git/'

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (mynewgitbranch)
$ git add remote origin https://github.com/varun7537/GitPracticalno4.git
fatal: pathspec 'remote' did not match any files

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (mynewgitbranch)
$ git remote add origin https://github.com/varun7537/GitPracticalno4.git
error: remote origin already exists.

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (mynewgitbranch)
$ git push origin mynewgitbranch
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 321 bytes | 321.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'mynewgitbranch' on GitHub by visiting:
remote:      https://github.com/varun7537/GitPracticalno4/pull/new/mynewgitbranch
remote:
To https://github.com/varun7537/GitPracticalno4.git
 * [new branch]      mynewgitbranch -> mynewgitbranch

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (mynewgitbranch)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (main)
$ git pull origin main
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 910 bytes | 910.00 KiB/s, done.
From https://github.com/varun7537/GitPracticalno4
 * branch            main       -> FETCH_HEAD
   4db299b..6d0cd6b  main       -> origin/main
Updating 4db299b..6d0cd6b
Fast-forward
 config.php | 0
 index.html | 0
 script.js  | 0
 style.css  | 0
 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 config.php
 create mode 100644 index.html
 create mode 100644 script.js
 create mode 100644 style.css

SAPCT@CC-PC090 MINGW64 /d/GitPracticalno4 (main)
$
