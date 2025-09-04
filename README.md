y28@cy28-Precision-3660:~/Documents/devops/lab1$ git int
git: 'int' is not a git command. See 'git --help'.

The most similar command is
	init
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git init
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
Initialized empty Git repository in /home/cy28/Documents/devops/lab1/.git/
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git add . && git commit -m "app file added" && git push
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git config -- global user.email "tomsoman45@gmail.com"
error: key does not contain a section: global
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git config --global user.email "tomsoman45@gmail.com"
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git add . && git commit -m "app file added" && git push
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git config --global user.email "Soman-1"
cy28@cy28-Precision-3660:~/Documents/devops/lab1$  remote add origin https://github.com/Soman-1/lab1.git~
Command 'remote' not found, but can be installed with:
sudo snap install remote
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ sudo apt install remote
[sudo] password for cy28: 
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done

No apt package "remote", but there is a snap with that name.
Try "snap install remote"

E: Unable to locate package remote
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git remote add origin https://github.com/Soman-1/lab1.git
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git push - u origin master
error: src refspec u does not match any
error: src refspec origin does not match any
error: src refspec master does not match any
error: failed to push some refs to '-'
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git branch
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/Soman-1/lab1.git'
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git checkout-b main
git: 'checkout-b' is not a git command. See 'git --help'.
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git checkout -b main
Switched to a new branch 'main'
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/Soman-1/lab1.git'
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git checkout -b main
Switched to a new branch 'main'
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/Soman-1/lab1.git'
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Soman-1/lab1.git'
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git branch
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git checkout -b main
Switched to a new branch 'main'
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git branch
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Soman-1/lab1.git'
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ ls
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ gedit hello
^C
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ gedit hello.html
^C
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ ls
hello.html
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	hello.html

nothing added to commit but untracked files present (use "git add" to track)
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git branch
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git add . && git commit -m "app file added" && git push
[main (root-commit) 1185c38] app file added
 1 file changed, 1 insertion(+)
 create mode 100644 hello.html
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

cy28@cy28-Precision-3660:~/Documents/devops/lab1$ it remote add origin https://github.com/Soman-1/lab1.gi^C
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ ^C
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git push --set-upstream origin main
Username for 'https://github.com': ^[^[^C
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git push --set-upstream origin main

Username for 'https://github.com': Password for 'https://github.com': 
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git push --set-upstream origin main
Username for 'https://github.com': Soman-1
Password for 'https://Soman-1@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal: Authentication failed for 'https://github.com/Soman-1/lab1.git/'
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git push --set-upstream origin main
 Username for 'https://github.com':^C
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git push --set-upstream origin main
Username for 'https://github.com': Soman-1
Password for 'https://Soman-1@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 206 bytes | 206.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Soman-1/lab1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git checkout -b login
Switched to a new branch 'login'
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git push -u branch login
fatal: 'branch' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git push -u origin login
Username for 'https://github.com': Soman-1
Password for 'https://Soman-1@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal: Authentication failed for 'https://github.com/Soman-1/lab1.git/'
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ gedit login
^C
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ gedit login.html
^C
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git add . && git commit -m "app file added" && git push
[login 4b1831c] app file added
 1 file changed, 1 insertion(+)
 create mode 100644 login.html
fatal: The current branch login has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin login

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git push --set-upstream origin login
Username for 'https://github.com': ^C
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ ls
hello.html  login.html
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git branch
* login
  main
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git merge
fatal: No remote for the current branch.
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git merge login
Already up to date.
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ ls
hello.html  login.html
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git checkout -b logout
Switched to a new branch 'logout'
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ ls
hello.html  login.html
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git branch
  login
* logout
  main
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ ls
hello.html  login.html
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ gedit logout.html
^C
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git branch
  login
* logout
  main
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ ls
hello.html  login.html  logout.html
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git status
On branch logout
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	logout.html

nothing added to commit but untracked files present (use "git add" to track)
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ ^Ct add . && git commit -m "app file added" &&
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git add . && git commit -m "logout page  added" && git push
[logout 8b89711] logout page  added
 1 file changed, 2 insertions(+)
 create mode 100644 logout.html
fatal: The current branch logout has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin logout

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

cy28@cy28-Precision-3660:~/Documents/devops/lab1$  git push --set-upstream origin logout
Username for 'https://github.com': Soman-1
Password for 'https://Soman-1@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal: Authentication failed for 'https://github.com/Soman-1/lab1.git/'
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git add . && git commit -m "logout page  added" && git push
On branch logout
nothing to commit, working tree clean
cy28@cy28-Precision-3660:~/Documents/devops/lab1$  git push --set-upstream origin logout 
Username for 'https://github.com': Soman-1
Password for 'https://Soman-1@github.com': 
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 20 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 464 bytes | 464.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote: 
remote: Create a pull request for 'logout' on GitHub by visiting:
remote:      https://github.com/Soman-1/lab1/pull/new/logout
remote: 
To https://github.com/Soman-1/lab1.git
 * [new branch]      logout -> logout
branch 'logout' set up to track 'origin/logout'.
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git branch
  login
* logout
  main
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git checkout master
error: pathspec 'master' did not match any file(s) known to git
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ ls
hello.html  login.html  logout.html
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ hit checkout main
Command 'hit' not found, did you mean:
  command 'hi' from snap hi (1.1)
  command 'hot' from deb hopenpgp-tools (0.23.7-1)
  command 'vit' from deb vit (2.3.2-1)
  command 'git' from deb git (1:2.43.0-1ubuntu7.3)
  command 'hitc' from deb pvm-examples (3.4.6-5)
  command 'hkt' from deb hopenpgp-tools (0.23.7-1)
  command 'wit' from deb wit (3.01a-4.1)
  command 'hist' from deb loki (2.4.7.4-10)
  command 'hut' from deb hut (0.4.0-1ubuntu0.3)
  command 'ht' from deb texlive-plain-generic (2023.20231207-3)
See 'snap info <snapname>' for additional versions.
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ ls
hello.html
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ cat hello.html
he
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git fetch
remote: Enumerating objects: 8, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (4/4), 1.79 KiB | 914.00 KiB/s, done.
From https://github.com/Soman-1/lab1
   1185c38..8dd3a0b  main       -> origin/main
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ cat hello.html
he
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git merge
Updating 1185c38..8dd3a0b
Fast-forward
 hello.html  | 4 +++-
 login.html  | 1 +
 logout.html | 2 ++
 3 files changed, 6 insertions(+), 1 deletion(-)
 create mode 100644 login.html
 create mode 100644 logout.html
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ cat hello.html
hedjjd]
jwjd
dkkdk
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 974 bytes | 974.00 KiB/s, done.
From https://github.com/Soman-1/lab1
   8dd3a0b..14d57ff  main       -> origin/main
Updating 8dd3a0b..14d57ff
Fast-forward
 hello.html | 4 ++++
 1 file changed, 4 insertions(+)
cy28@cy28-Precision-3660:~/Documents/devops/lab1$ cat hello.html
hedjjd]
jwjd
dkkdk

hi 
hello
