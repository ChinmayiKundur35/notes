msis@msis-Lenovo-V310z:~$ sudo mkdir bankapplications
[sudo] password for msis: 
Sorry, try again.
[sudo] password for msis: 
msis@msis-Lenovo-V310z:~$ cd bankapplications/
msis@msis-Lenovo-V310z:~/bankapplications$ sudo git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint: 	git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint: 	git branch -m <name>
Initialized empty Git repository in /home/msis/bankapplications/.git/
msis@msis-Lenovo-V310z:~/bankapplications$ ls -a
.  ..  .git
msis@msis-Lenovo-V310z:~/bankapplications$ sudo git remote add origin "git@github.com:ChinmayiKundur/bankappications.git"
msis@msis-Lenovo-V310z:~/bankapplications$ ls -a
.  ..  .git
msis@msis-Lenovo-V310z:~/bankapplications$ sudo git pull origin main
The authenticity of host 'github.com (20.207.73.82)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? y
Please type 'yes', 'no' or the fingerprint: y
Please type 'yes', 'no' or the fingerprint: y
Please type 'yes', 'no' or the fingerprint: y
Please type 'yes', 'no' or the fingerprint: yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
msis@msis-Lenovo-V310z:~/bankapplications$ ls
msis@msis-Lenovo-V310z:~/bankapplications$ ls -a
.  ..  .git
msis@msis-Lenovo-V310z:~/bankapplications$ sudo git pull origin main
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
msis@msis-Lenovo-V310z:~/bankapplications$ sudo git remote add origin "git@github.com:ChinmayiKundur/bankappications.git"
error: remote origin already exists.
msis@msis-Lenovo-V310z:~/bankapplications$ sudo git pull origin main
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
msis@msis-Lenovo-V310z:~/bankapplications$ ls
msis@msis-Lenovo-V310z:~/bankapplications$ cd ..
msis@msis-Lenovo-V310z:~$ sudo mkdir bankapp
msis@msis-Lenovo-V310z:~$ cd bankapp/
msis@msis-Lenovo-V310z:~/bankapp$ ls
msis@msis-Lenovo-V310z:~/bankapp$ ls -a
.  ..
msis@msis-Lenovo-V310z:~/bankapp$ sudo git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint: 	git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint: 	git branch -m <name>
Initialized empty Git repository in /home/msis/bankapp/.git/
msis@msis-Lenovo-V310z:~/bankapp$ ls -a
.  ..  .git
msis@msis-Lenovo-V310z:~/bankapp$ sudo git remote add origin "git@github.com:ChinmayiKundur/bankapp.git"
msis@msis-Lenovo-V310z:~/bankapp$ ls
msis@msis-Lenovo-V310z:~/bankapp$ ls -a
.  ..  .git
msis@msis-Lenovo-V310z:~/bankapp$ sudo git pull origin main
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
msis@msis-Lenovo-V310z:~/bankapp$ ls
msis@msis-Lenovo-V310z:~/bankapp$ sudo git pull origin main
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
msis@msis-Lenovo-V310z:~/bankapp$ sudo git branch
msis@msis-Lenovo-V310z:~/bankapp$ ls
msis@msis-Lenovo-V310z:~/bankapp$ ls -l
total 0
msis@msis-Lenovo-V310z:~/bankapp$ ls -a
.  ..  .git
msis@msis-Lenovo-V310z:~/bankapp$ sudo git checkout main
error: pathspec 'main' did not match any file(s) known to git
msis@msis-Lenovo-V310z:~/bankapp$ sudo git checkout main
error: pathspec 'main' did not match any file(s) known to git
msis@msis-Lenovo-V310z:~/bankapp$ sudo git pull origin git@github.com:ChinmayiKundur/bankapp.git
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
msis@msis-Lenovo-V310z:~/bankapp$ sudo git remote -v
origin	git@github.com:ChinmayiKundur/bankapp.git (fetch)
origin	git@github.com:ChinmayiKundur/bankapp.git (push)
msis@msis-Lenovo-V310z:~/bankapp$ sudo git pull origin main
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
msis@msis-Lenovo-V310z:~/bankapp$ sudo git --global user.email "rchinmayi352002@gmail.com"
unknown option: --global
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]
msis@msis-Lenovo-V310z:~/bankapp$ sudo git pull origin main
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
msis@msis-Lenovo-V310z:~/bankapp$ sudo git remote add git@github.com:ChinmayiKundur/bankapp.git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from

msis@msis-Lenovo-V310z:~/bankapp$ sudo git pull origin main
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
msis@msis-Lenovo-V310z:~/bankapp$ 
msis@msis-Lenovo-V310z:~/bankapp$ cd 
msis@msis-Lenovo-V310z:~$ ls
a.out             bookapp      Cafe_Dynamic_Website  Downloads       largest  mysite   operation.c   Public          Templates
bankapp           bubble_sort  Desktop               header.h        main.c   mysite1  phpmysql-app  selection_sort  tourweb
bankapplications  cafeapp      Documents             insertion_sort  Music    onepage  Pictures      snap            Videos
msis@msis-Lenovo-V310z:~$ sudo mkdir bankapp01
msis@msis-Lenovo-V310z:~$ cd bankapp01
msis@msis-Lenovo-V310z:~/bankapp01$ ls -a
.  ..
msis@msis-Lenovo-V310z:~/bankapp01$ sudo git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint: 	git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint: 	git branch -m <name>
Initialized empty Git repository in /home/msis/bankapp01/.git/
msis@msis-Lenovo-V310z:~/bankapp01$ sudo git remote add origin git@github.com:ChinmayiKundur/bankapp01.git 
msis@msis-Lenovo-V310z:~/bankapp01$ sudo git remote -v
origin	git@github.com:ChinmayiKundur/bankapp01.git (fetch)
origin	git@github.com:ChinmayiKundur/bankapp01.git (push)
msis@msis-Lenovo-V310z:~/bankapp01$ sudo git pull origin main
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
msis@msis-Lenovo-V310z:~/bankapp01$ sudo git pull origin main
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
msis@msis-Lenovo-V310z:~/bankapp01$ ls -a
.  ..  .git
msis@msis-Lenovo-V310z:~/bankapp01$ sudo git log
fatal: your current branch 'master' does not have any commits yet
msis@msis-Lenovo-V310z:~/bankapp01$ sudo git checkout origin
error: pathspec 'origin' did not match any file(s) known to git
msis@msis-Lenovo-V310z:~/bankapp01$ sudo git checkout main
error: pathspec 'main' did not match any file(s) known to git
msis@msis-Lenovo-V310z:~/bankapp01$ sudo git checkout master
error: pathspec 'master' did not match any file(s) known to git
msis@msis-Lenovo-V310z:~/bankapp01$ sudo git branch
msis@msis-Lenovo-V310z:~/bankapp01$ sudo git pull origin main
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
msis@msis-Lenovo-V310z:~/bankapp01$ sudo git pull origin main
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
msis@msis-Lenovo-V310z:~/bankapp01$ sudo git remote add origin https://github.com/praneshragavendar/bankapp.git
error: remote origin already exists.
msis@msis-Lenovo-V310z:~/bankapp01$ sudo git remote -v
origin	git@github.com:ChinmayiKundur/bankapp01.git (fetch)
origin	git@github.com:ChinmayiKundur/bankapp01.git (push)
msis@msis-Lenovo-V310z:~/bankapp01$ cd  
msis@msis-Lenovo-V310z:~$ sudo mkdir newrepo
msis@msis-Lenovo-V310z:~$ cd newrepo
msis@msis-Lenovo-V310z:~/newrepo$ sudo git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint: 	git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint: 	git branch -m <name>
Initialized empty Git repository in /home/msis/newrepo/.git/
msis@msis-Lenovo-V310z:~/newrepo$ sudo git remote add origin https://github.com/praneshragavendar/bankapp.git
msis@msis-Lenovo-V310z:~/newrepo$ sudo git remote -v
origin	https://github.com/praneshragavendar/bankapp.git (fetch)
origin	https://github.com/praneshragavendar/bankapp.git (push)
msis@msis-Lenovo-V310z:~/newrepo$ sudo git pull origin main
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 3 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), 1.10 KiB | 1.10 MiB/s, done.
From https://github.com/praneshragavendar/bankapp
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
msis@msis-Lenovo-V310z:~/newrepo$ ls
home.php  README.md
msis@msis-Lenovo-V310z:~/newrepo$ cd ..
msis@msis-Lenovo-V310z:~$ sudo mkdir bookapp
mkdir: cannot create directory ‘bookapp’: File exists
msis@msis-Lenovo-V310z:~$ sudo mkdir bookapp12
msis@msis-Lenovo-V310z:~$ cd bookapp12/
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint: 	git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint: 	git branch -m <name>
Initialized empty Git repository in /home/msis/bookapp12/.git/
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git remote add origin https://github.com/ChinmayiKundur35/bookapp.git
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git pull origin main
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 854 bytes | 854.00 KiB/s, done.
From https://github.com/ChinmayiKundur35/bookapp
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
msis@msis-Lenovo-V310z:~/bookapp12$ ls
README.md
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git remote -v
origin	https://github.com/ChinmayiKundur35/bookapp.git (fetch)
origin	https://github.com/ChinmayiKundur35/bookapp.git (push)
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git branch
* master
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git branch -a
* master
  remotes/origin/main
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git checkout main
Branch 'main' set up to track remote branch 'main' from 'origin'.
Switched to a new branch 'main'
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git branch -a
* main
  master
  remotes/origin/main
msis@msis-Lenovo-V310z:~/bookapp12$ ls
README.md
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git log
commit 35f01f0c2e2f14aadfb7a8e6ab331ab7e7077379 (HEAD -> main, origin/main, master)
Author: ChinmayiKundur35 <rchinmayikundur@gmail.com>
Date:   Mon Aug 5 15:53:54 2024 +0530

    Initial commit
msis@msis-Lenovo-V310z:~/bookapp12$ sudo touch home.php
msis@msis-Lenovo-V310z:~/bookapp12$ ls
home.php  README.md
msis@msis-Lenovo-V310z:~/bookapp12$ sudo cat > home.php 
bash: home.php: Permission denied
msis@msis-Lenovo-V310z:~/bookapp12$ sudo ls -l
total 4
-rw-r--r-- 1 root root 0 Aug  5 16:00 home.php
-rw-r--r-- 1 root root 9 Aug  5 15:56 README.md
msis@msis-Lenovo-V310z:~/bookapp12$ sudo chown -R msis:msis home.php 
msis@msis-Lenovo-V310z:~/bookapp12$ ls -l
total 4
-rw-r--r-- 1 msis msis 0 Aug  5 16:00 home.php
-rw-r--r-- 1 root root 9 Aug  5 15:56 README.md
msis@msis-Lenovo-V310z:~/bookapp12$ sudo cat > home.php 
welcome to bank account ^C
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git add home.php
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   home.php

msis@msis-Lenovo-V310z:~/bookapp12$ sudo cat > home.php 
welcome bank
^C
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   home.php

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   home.php

msis@msis-Lenovo-V310z:~/bookapp12$ sudo git commit home.php
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'root@msis-Lenovo-V310z.(none)')
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git commit -a -m "added the homepage"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'root@msis-Lenovo-V310z.(none)')
msis@msis-Lenovo-V310z:~/bookapp12$ sudo cat > home.php 
welcome to bankaccount
^C
msis@msis-Lenovo-V310z:~/bookapp12$ ^C
msis@msis-Lenovo-V310z:~/bookapp12$ sudo https://github.com/ChinmayiKundur35/bookapp.git
sudo: https://github.com/ChinmayiKundur35/bookapp.git: command not found
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git config --global user.email "rchinmayikundurgmail.com" 
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git commit -a -m "added the homepage"
[sudo] password for msis: 
[main afe6054] added the homepage
 1 file changed, 1 insertion(+)
 create mode 100644 home.php
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git log
commit afe6054ec578e8279d23bc0f2b214739328d4b97 (HEAD -> main)
Author: root <rchinmayikundurgmail.com>
Date:   Mon Aug 5 16:36:17 2024 +0530

    added the homepage

commit 35f01f0c2e2f14aadfb7a8e6ab331ab7e7077379 (origin/main, master)
Author: ChinmayiKundur35 <rchinmayikundur@gmail.com>
Date:   Mon Aug 5 15:53:54 2024 +0530

    Initial commit
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git cat-file -p afe6054ec578e8279d23bc0f2b214739328d4b97
tree 0800d0e577915e9362a15042e680b36bfbfca1b9
parent 35f01f0c2e2f14aadfb7a8e6ab331ab7e7077379
author root <rchinmayikundurgmail.com> 1722855977 +0530
committer root <rchinmayikundurgmail.com> 1722855977 +0530

added the homepage
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git cat-file -p 0800d0e577915e9362a15042e680b36bfbfca1b9
100644 blob 303a8c535aef9752223c67c4be5129cb490491b3	README.md
100644 blob 44d07a36e89b8031715910d9d69195b76b712a4d	home.php
msis@msis-Lenovo-V310z:~/bookapp12$ cd git
bash: cd: git: No such file or directory
msis@msis-Lenovo-V310z:~/bookapp12$ cd git/
bash: cd: git/: No such file or directory
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git log
commit afe6054ec578e8279d23bc0f2b214739328d4b97 (HEAD -> main)
Author: root <rchinmayikundurgmail.com>
Date:   Mon Aug 5 16:36:17 2024 +0530

    added the homepage

commit 35f01f0c2e2f14aadfb7a8e6ab331ab7e7077379 (origin/main, master)
Author: ChinmayiKundur35 <rchinmayikundur@gmail.com>
Date:   Mon Aug 5 15:53:54 2024 +0530

    Initial commit
msis@msis-Lenovo-V310z:~/bookapp12$ cd .git
msis@msis-Lenovo-V310z:~/bookapp12/.git$ ls
branches  COMMIT_EDITMSG  config  description  FETCH_HEAD  HEAD  hooks  index  info  logs  objects  refs
msis@msis-Lenovo-V310z:~/bookapp12/.git$ sudo git log
commit afe6054ec578e8279d23bc0f2b214739328d4b97 (HEAD -> main)
Author: root <rchinmayikundurgmail.com>
Date:   Mon Aug 5 16:36:17 2024 +0530

    added the homepage

commit 35f01f0c2e2f14aadfb7a8e6ab331ab7e7077379 (origin/main, master)
Author: ChinmayiKundur35 <rchinmayikundur@gmail.com>
Date:   Mon Aug 5 15:53:54 2024 +0530

    Initial commit
msis@msis-Lenovo-V310z:~/bookapp12/.git$ cd ..
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git push origin main
Username for 'https://github.com': chinmayikundur35
Password for 'https://chinmayikundur35@github.com': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 299 bytes | 299.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ChinmayiKundur35/bookapp.git
   35f01f0..afe6054  main -> main
msis@msis-Lenovo-V310z:~/bookapp12$ sudo touch about.php contact.php
msis@msis-Lenovo-V310z:~/bookapp12$ sudo chown -R msis:msis about.php contact.php 
msis@msis-Lenovo-V310z:~/bookapp12$ sudo cat > about.php 
welcome about^C
msis@msis-Lenovo-V310z:~/bookapp12$ sudo cat > contact.php 
welcome contact ^C
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git add -A
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   about.php
	new file:   contact.php

msis@msis-Lenovo-V310z:~/bookapp12$ sudo git commit -a -m "added about and contect page"
[main 16d3651] added about and contect page
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 about.php
 create mode 100644 contact.php
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git log
commit 16d3651ca0b4c6279155353e712a53af6af024a2 (HEAD -> main)
Author: root <rchinmayikundurgmail.com>
Date:   Mon Aug 5 16:52:11 2024 +0530

    added about and contect page

commit afe6054ec578e8279d23bc0f2b214739328d4b97 (origin/main)
Author: root <rchinmayikundurgmail.com>
Date:   Mon Aug 5 16:36:17 2024 +0530

    added the homepage

commit 35f01f0c2e2f14aadfb7a8e6ab331ab7e7077379 (master)
Author: ChinmayiKundur35 <rchinmayikundur@gmail.com>
Date:   Mon Aug 5 15:53:54 2024 +0530

    Initial commit
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git push origin main
Username for 'https://github.com': chinmayikundur35
Password for 'https://chinmayikundur35@github.com': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 324 bytes | 324.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ChinmayiKundur35/bookapp.git
   afe6054..16d3651  main -> main
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git branch trans
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git checkout trans 
Switched to branch 'trans'
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git branch 
  main
  master
* trans
msis@msis-Lenovo-V310z:~/bookapp12$ ls
about.php  contact.php  home.php  README.md
msis@msis-Lenovo-V310z:~/bookapp12$ sudo touch trans.php
msis@msis-Lenovo-V310z:~/bookapp12$ sudo chrown -R msis:msis trans.php 
sudo: chrown: command not found
msis@msis-Lenovo-V310z:~/bookapp12$ s
s: command not found
msis@msis-Lenovo-V310z:~/bookapp12$ sudo chown -R msis:msis trans.php 
msis@msis-Lenovo-V310z:~/bookapp12$ ls -l
total 8
-rw-r--r-- 1 msis msis  0 Aug  5 16:49 about.php
-rw-r--r-- 1 msis msis  0 Aug  5 16:49 contact.php
-rw-r--r-- 1 msis msis 23 Aug  5 16:10 home.php
-rw-r--r-- 1 root root  9 Aug  5 15:56 README.md
-rw-r--r-- 1 msis msis  0 Aug  5 16:56 trans.php
msis@msis-Lenovo-V310z:~/bookapp12$ sudo cat >trans.php 
welcome trans
^C
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git add -A
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git status
On branch trans
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   trans.php

msis@msis-Lenovo-V310z:~/bookapp12$ sudo git commit -a -m "add the trans page from trans"
[trans d65a2d4] add the trans page from trans
 1 file changed, 1 insertion(+)
 create mode 100644 trans.php
msis@msis-Lenovo-V310z:~/bookapp12$ ls
about.php  contact.php  home.php  README.md  trans.php
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git branch
  main
  master
* trans
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git log
commit 16d3651ca0b4c6279155353e712a53af6af024a2 (HEAD -> main, origin/main)
Author: root <rchinmayikundurgmail.com>
Date:   Mon Aug 5 16:52:11 2024 +0530

    added about and contect page

commit afe6054ec578e8279d23bc0f2b214739328d4b97
Author: root <rchinmayikundurgmail.com>
Date:   Mon Aug 5 16:36:17 2024 +0530

    added the homepage

commit 35f01f0c2e2f14aadfb7a8e6ab331ab7e7077379 (master)
Author: ChinmayiKundur35 <rchinmayikundur@gmail.com>
Date:   Mon Aug 5 15:53:54 2024 +0530

    Initial commit
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git merge trans 
Updating 16d3651..d65a2d4
Fast-forward
 trans.php | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 trans.php
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git log
commit d65a2d4d5b5a11416774e2b25251b4364ad476e0 (HEAD -> main, trans)
Author: root <rchinmayikundurgmail.com>
Date:   Mon Aug 5 17:00:06 2024 +0530

    add the trans page from trans

commit 16d3651ca0b4c6279155353e712a53af6af024a2 (origin/main)
Author: root <rchinmayikundurgmail.com>
Date:   Mon Aug 5 16:52:11 2024 +0530

    added about and contect page

commit afe6054ec578e8279d23bc0f2b214739328d4b97
Author: root <rchinmayikundurgmail.com>
Date:   Mon Aug 5 16:36:17 2024 +0530

    added the homepage

commit 35f01f0c2e2f14aadfb7a8e6ab331ab7e7077379 (master)
Author: ChinmayiKundur35 <rchinmayikundur@gmail.com>
Date:   Mon Aug 5 15:53:54 2024 +0530

    Initial commit
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git checkout trans 
Switched to branch 'trans'
msis@msis-Lenovo-V310z:~/bookapp12$ sudo touch imps.php
msis@msis-Lenovo-V310z:~/bookapp12$ sudo chown -R msis:msis imps.php 
msis@msis-Lenovo-V310z:~/bookapp12$ sudo cat > imps.php 
welcome ^C
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git checkout trans 
Switched to branch 'trans'
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git add -A
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git shash
git: 'shash' is not a git command. See 'git --help'.

The most similar command is
	stash
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git stash
Saved working directory and index state WIP on trans: d65a2d4 add the trans page from trans
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)
msis@msis-Lenovo-V310z:~/bookapp12$ ls
about.php  contact.php  home.php  README.md  trans.php
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git checkout trans 
Switched to branch 'trans'
msis@msis-Lenovo-V310z:~/bookapp12$ ls
about.php  contact.php  home.php  README.md  trans.php
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git stash apply
On branch trans
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   imps.php

msis@msis-Lenovo-V310z:~/bookapp12$ sudo git commit -a -m "add the imps page"
[trans c4e62cd] add the imps page
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 imps.php
msis@msis-Lenovo-V310z:~/bookapp12$ ls
about.php  contact.php  home.php  imps.php  README.md  trans.php
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git push imps.php
fatal: invalid gitfile format: imps.php
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
msis@msis-Lenovo-V310z:~/bookapp12$ sudo git push origin trans 
Username for 'https://github.com': chinmayikundur35
Password for 'https://chinmayikundur35@github.com': 
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 475 bytes | 475.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote: 
remote: Create a pull request for 'trans' on GitHub by visiting:
remote:      https://github.com/ChinmayiKundur35/bookapp/pull/new/trans
remote: 
To https://github.com/ChinmayiKundur35/bookapp.git
 * [new branch]      trans -> trans
msis@msis-Lenovo-V310z:~/bookapp12$ 

