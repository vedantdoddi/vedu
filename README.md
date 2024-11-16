$ git log --author="vedantdoddi" --since="2024-7-1" --until="2024-11-16"
commit 7ce52943b191c800560c54243574d4308bf82212 (HEAD -> master, origin/master)
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 9 10:00:58 2024 +0530

    commted again

commit 019723adf3642bbff29cd796c774594ec612aeb2 (featurebranch)
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 9 09:57:27 2024 +0530

    commit 5 in feature

commit 918f642dffd957ffe7d904d6cad5bd1ef603dec6
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 9 09:57:04 2024 +0530

    commit 4 in feature

commit b144bdeb168e500b75d5fd0bffa9840e38e6e7b0
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 9 09:56:40 2024 +0530

    commit 3 in feature
commit 7ce52943b191c800560c54243574d4308bf82212 (HEAD -> master, origin/master)
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 9 10:00:58 2024 +0530

    commted again

commit 019723adf3642bbff29cd796c774594ec612aeb2 (featurebranch)
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 9 09:57:27 2024 +0530

    commit 5 in feature

commit 918f642dffd957ffe7d904d6cad5bd1ef603dec6
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 9 09:57:04 2024 +0530

    commit 4 in feature

commit b144bdeb168e500b75d5fd0bffa9840e38e6e7b0
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 9 09:56:40 2024 +0530

    commit 3 in feature

commit 61f42309ddfeb6cd8f5d3869a836f6130216f316
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 9 09:56:14 2024 +0530

    commit 2 in feature

commit 25972ab869f8e6453cf15d298c678cc60714d565
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 9 09:55:55 2024 +0530

    commit 1 in feature

commit 4835f7b765cc3ce96680e5504c6d29f7702b65af
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 9 09:53:22 2024 +0530

    commit 5 in master


EXPT 8:
BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 ~ ((v11.0))
$ cd d:

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d
$ mkdir v4

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d
$ cd v4

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4
$ git init
Initialized empty Git repository in D:/v4/.git/

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (master)
$ nano v4.c

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (master)
$ git add .
warning: in the working copy of 'v4.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (master)
$ git commit -m "added v4.c in master"
[master (root-commit) dda4b40] added v4.c in master
 1 file changed, 1 insertion(+)
 create mode 100644 v4.c

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (master)
$ nano v4.c

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (master)
$ git add .
warning: in the working copy of 'v4.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (master)
$ git commit -m "commit 2 in master"
[master fc71bb0] commit 2 in master
 1 file changed, 1 insertion(+)

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (master)
$ git branch feature

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (master)
$ git checkout feature
Switched to branch 'feature'

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (feature)
$ git log
commit fc71bb0488f7621fe23953076af468e5c89bcc15 (HEAD -> feature, master)
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 16 10:37:09 2024 +0530

    commit 2 in master

commit dda4b407b39180dd2b4026d75758076da01ac6b9
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 16 10:36:20 2024 +0530

    added v4.c in master

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (feature)
$ nano v4a.c

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (feature)
$ git add v4a.c
warning: in the working copy of 'v4a.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (feature)
$ git commit -m "commit in feature"
[feature 77e77f5] commit in feature
 1 file changed, 1 insertion(+)
 create mode 100644 v4a.c

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (feature)
$ nano v4b.c

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (feature)
$ git add v4b.c
warning: in the working copy of 'v4b.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (feature)
$ git commit -m "commit of v4b.c in feature"
[feature 295c682] commit of v4b.c in feature
 1 file changed, 1 insertion(+)
 create mode 100644 v4b.c

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (feature)
$ git log
commit 295c6823a6f95e6875c83dfc20b39e18d028d385 (HEAD -> feature)
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 16 10:41:36 2024 +0530

    commit of v4b.c in feature

commit 77e77f55a236060272d1755fc0f2da00c2f859e8
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 16 10:40:39 2024 +0530

    commit in feature

commit fc71bb0488f7621fe23953076af468e5c89bcc15 (master)
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 16 10:37:09 2024 +0530

    commit 2 in master

commit dda4b407b39180dd2b4026d75758076da01ac6b9
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 16 10:36:20 2024 +0530

    added v4.c in master

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (feature)
$ git checkout master
Switched to branch 'master'

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (master)
$ git log
commit fc71bb0488f7621fe23953076af468e5c89bcc15 (HEAD -> master)
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 16 10:37:09 2024 +0530

    commit 2 in master

commit dda4b407b39180dd2b4026d75758076da01ac6b9
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 16 10:36:20 2024 +0530

    added v4.c in master

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (master)
$ git chery-pick  77e77f55a236060272d1755fc0f2da00c2f859e8
git: 'chery-pick' is not a git command. See 'git --help'.

The most similar command is
        cherry-pick

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (master)
$ git cherry-pick  77e77f55a236060272d1755fc0f2da00c2f859e8
[master 0b80a6e] commit in feature
 Date: Sat Nov 16 10:40:39 2024 +0530
 1 file changed, 1 insertion(+)
 create mode 100644 v4a.c

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (master)
$ git log
commit 0b80a6e8f6e65346388eed5209c94486bb838205 (HEAD -> master)
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 16 10:40:39 2024 +0530

    commit in feature

commit fc71bb0488f7621fe23953076af468e5c89bcc15
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 16 10:37:09 2024 +0530

    commit 2 in master

commit dda4b407b39180dd2b4026d75758076da01ac6b9
Author: vedantdoddi <vedantdoddi@gmail.com>
Date:   Sat Nov 16 10:36:20 2024 +0530

    added v4.c in master

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (master)
$ ls
v4.c  v4a.c

BLDEA-CSE@DESKTOP-ET8ORPC MINGW64 /d/v4 (master)
$
