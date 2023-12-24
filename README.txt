개발자 티셔츠 쇼링몰 오픈소스

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat
$ GIT INIT
git: 'INIT' is not a git command. See 'git --help'.

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat
$ git init
Initialized empty Git repository in C:/Users/user/Desktop/Programming/iTshirt-cat/.git/

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$ git config -- global user.email "legalitart@gmail.com"
error: key does not contain a section: global

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$ ^C

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$ ^V
bash: $'\026': command not found

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$ git config --global user.email "legalitart@gmail.com"

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$ git config --global user.name "ds syn"

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$ git add README.txt

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$ git commit -m "git bash workingtools"
[master (root-commit) 68dc85f] git bash workingtools
 1 file changed, 1 insertion(+)
 create mode 100644 README.txt



user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$ git log
commit 80a64f313211ffd72a4e5f983b926694834cb000 (HEAD -> master)
Author: ds syn <legalitart@gmail.com>
Date:   Sun Dec 24 12:34:37 2023 +0900

    설명 업데이트

commit 68dc85ff2a4d0808ee1822ec9ad244cfd24cd293
Author: ds syn <legalitart@gmail.com>
Date:   Sun Dec 24 12:31:19 2023 +0900

    git bash workingtools

