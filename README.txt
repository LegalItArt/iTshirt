
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
$ git add README.txt

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$ git commit -m "설명 업데이트"
[master 80a64f3] 설명 업데이트
 1 file changed, 35 insertions(+), 1 deletion(-)

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

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$ git add README.txt

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$ git commit -m "git log"
[master 247d2fa] git log
 1 file changed, 17 insertions(+)

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$ git log
commit 247d2faae0fdd4bfc91f7f7fd39626ab90f50a39 (HEAD -> master)
Author: ds syn <legalitart@gmail.com>
Date:   Sun Dec 24 13:03:06 2023 +0900

    git log

commit 80a64f313211ffd72a4e5f983b926694834cb000
Author: ds syn <legalitart@gmail.com>
Date:   Sun Dec 24 12:34:37 2023 +0900

    설명 업데이트

commit 68dc85ff2a4d0808ee1822ec9ad244cfd24cd293
Author: ds syn <legalitart@gmail.com>
Date:   Sun Dec 24 12:31:19 2023 +0900

    git bash workingtools

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$ git checkout 68dc85f
Note: switching to '68dc85f'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 68dc85f git bash workingtools

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat ((68dc85f...))
$

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat ((68dc85f...))
$ git switch -
Previous HEAD position was 68dc85f git bash workingtools
Switched to branch 'master'

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$ git switch -
fatal: a branch is expected, got commit '68dc85ff2a4d0808ee1822ec9ad244cfd24cd293'
hint: If you want to detach HEAD at the commit, try again with the --detach option.

user@Synitart MINGW64 ~/Desktop/Programming/iTshirt-cat (master)
$
