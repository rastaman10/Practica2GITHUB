# Practica2GITHUB
Segunda practica 
Last login: Tue Nov 26 19:38:20 on ttys000
-bash: Export: command not found

The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ ls
app.js		index.html
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git init
Initialized empty Git repository in /Users/rasmanroots/Desktop/Practica entornos git hub/.git/
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	app.js
	index.html

nothing added to commit but untracked files present (use "git add" to track)
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git add app.js
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   app.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	index.html

MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git add index.html
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   app.js
	new file:   index.html

MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   app.js
	new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	style.css

MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git add style.css
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   app.js
	new file:   index.html
	new file:   style.css

MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git commit
[master (root-commit) acc16ad] ***************Practica de git hub por VICTOR BALLADARES*****************
 Committer: Rasman <rasmanroots@MacBook-Pro-de-Rasman.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 3 files changed, 2 insertions(+)
 create mode 100644 app.js
 create mode 100644 index.html
 create mode 100644 style.css
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
nothing to commit, working tree clean
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git commit
On branch master
nothing to commit, working tree clean
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git log
commit acc16ad308c3048ba7e9e5987544b022fc04c928 (HEAD -> master)
Author: Rasman <rasmanroots@MacBook-Pro-de-Rasman.local>
Date:   Tue Nov 26 19:52:05 2019 +0100

    ***************Practica de git hub por VICTOR BALLADARES*****************
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git config --global user.email
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ 
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git config --global user.email
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git config --global user.email"selasilay10@hotmail.com"
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git config --global user.name "rastaman10"
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
nothing to commit, working tree clean
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git commit
On branch master
nothing to commit, working tree clean
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git commit
On branch master
nothing to commit, working tree clean
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   style.css

no changes added to commit (use "git add" and/or "git commit -a")
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git add style.css
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git commit
[master abe0460] ***************************VICTOR BALLADARES*******************
 Committer: rastaman10 <rasmanroots@MacBook-Pro-de-Rasman.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git config --global user.name "rastaman10"
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git config --global user.email"selasilay10@hotmail.com"
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
nothing to commit, working tree clean
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git log
commit abe04603a89a7813309a03094e2e10f67e230208 (HEAD -> master)
Author: rastaman10 <rasmanroots@MacBook-Pro-de-Rasman.local>
Date:   Tue Nov 26 20:01:07 2019 +0100

    ***************************VICTOR BALLADARES*******************

commit acc16ad308c3048ba7e9e5987544b022fc04c928
Author: Rasman <rasmanroots@MacBook-Pro-de-Rasman.local>
Date:   Tue Nov 26 19:52:05 2019 +0100

    ***************Practica de git hub por VICTOR BALLADARES*****************
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ 
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git config --global user.email "selasilay10@hotmail.com"
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ 
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git config --global user.name "rastaman10"
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git config --global user.password "Dondev@mos1987"
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git log
commit abe04603a89a7813309a03094e2e10f67e230208 (HEAD -> master)
Author: rastaman10 <rasmanroots@MacBook-Pro-de-Rasman.local>
Date:   Tue Nov 26 20:01:07 2019 +0100

    ***************************VICTOR BALLADARES*******************

commit acc16ad308c3048ba7e9e5987544b022fc04c928
Author: Rasman <rasmanroots@MacBook-Pro-de-Rasman.local>
Date:   Tue Nov 26 19:52:05 2019 +0100

    ***************Practica de git hub por VICTOR BALLADARES*****************
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ 
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git checkout index.html
Updated 1 path from the index
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
nothing to commit, working tree clean
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git diff index.html
diff --git a/index.html b/index.html
index c6b171a..1418ed8 100644
--- a/index.html
+++ b/index.html
@@ -1 +1,12 @@
-texto
+<!DOCTYPE html>
+<html lang="en">
+<head>
+    <meta charset="UTF-8">
+    <meta name="viewport" content="width=device-width, initial-scale=1.0">
+    <meta http-equiv="X-UA-Compatible" content="ie=edge">
+    <title>Esto es codigo html</title>
+</head>
+<body>
+    
+</body>
+</html>
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$  git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git add index.html
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   index.html

MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git commit
[master f8cd826] ************* Ahora el index.html tiene codigo html
 1 file changed, 12 insertions(+), 1 deletion(-)
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git log
commit f8cd82658d18e798ff310707805e610534442289 (HEAD -> master)
Author: rastaman10 <selasilay10@hotmail.com>
Date:   Tue Nov 26 20:11:48 2019 +0100

    ************* Ahora el index.html tiene codigo html

commit abe04603a89a7813309a03094e2e10f67e230208
Author: rastaman10 <rasmanroots@MacBook-Pro-de-Rasman.local>
Date:   Tue Nov 26 20:01:07 2019 +0100

    ***************************VICTOR BALLADARES*******************

commit acc16ad308c3048ba7e9e5987544b022fc04c928
Author: Rasman <rasmanroots@MacBook-Pro-de-Rasman.local>
Date:   Tue Nov 26 19:52:05 2019 +0100

    ***************Practica de git hub por VICTOR BALLADARES*****************
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	test/

nothing added to commit but untracked files present (use "git add" to track)
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	test/

nothing added to commit but untracked files present (use "git add" to track)
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	test/

nothing added to commit but untracked files present (use "git add" to track)
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	test/

nothing added to commit but untracked files present (use "git add" to track)
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	test/

nothing added to commit but untracked files present (use "git add" to track)
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	test/

nothing added to commit but untracked files present (use "git add" to track)
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	test/

nothing added to commit but untracked files present (use "git add" to track)
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git add test
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   test/.gitignore
	new file:   test/pruebas.js

MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git commit -m "he hagragado un gitignore"
[master 4e13587] he hagragado un gitignore
 2 files changed, 1 insertion(+)
 create mode 100644 test/.gitignore
 create mode 100644 test/pruebas.js
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git branch
* master
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git branch login
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git branch
  login
* master
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git checkout login
Switched to branch 'login'
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git branch
* login
  master
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch login
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	test/hola+/

nothing added to commit but untracked files present (use "git add" to track)
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch login
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	test/hola+/
	test/indispensable/
	test/solo

nothing added to commit but untracked files present (use "git add" to track)
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git add .
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch login
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   test/hola+/cambios
	new file:   test/indispensable/comotu
	new file:   test/solo

MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git commit -m "version alternativa con login"
[login 755cb8e] version alternativa con login
 3 files changed, 3 insertions(+)
 create mode 100644 test/hola+/cambios
 create mode 100644 test/indispensable/comotu
 create mode 100644 test/solo
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch login
nothing to commit, working tree clean
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git log
commit 755cb8e9ba12a704fbac48ddfe5f77ce5aaf9ede (HEAD -> login)
Author: rastaman10 <selasilay10@hotmail.com>
Date:   Tue Nov 26 20:24:54 2019 +0100

    version alternativa con login

commit 755cb8e9ba12a704fbac48ddfe5f77ce5aaf9ede (HEAD -> login)
Author: rastaman10 <selasilay10@hotmail.com>
Date:   Tue Nov 26 20:24:54 2019 +0100

    version alternativa con login

commit 755cb8e9ba12a704fbac48ddfe5f77ce5aaf9ede (HEAD -> login)
Author: rastaman10 <selasilay10@hotmail.com>
Date:   Tue Nov 26 20:24:54 2019 +0100

    version alternativa con login

commit 4e13587d9147142137ec45e83cffc4753e48a129 (master)
Author: rastaman10 <selasilay10@hotmail.com>
Date:   Tue Nov 26 20:19:04 2019 +0100

    he hagragado un gitignore

commit f8cd82658d18e798ff310707805e610534442289
Author: rastaman10 <selasilay10@hotmail.com>
Date:   Tue Nov 26 20:11:48 2019 +0100

    ************* Ahora el index.html tiene codigo html

commit abe04603a89a7813309a03094e2e10f67e230208
Author: rastaman10 <rasmanroots@MacBook-Pro-de-Rasman.local>
Date:   Tue Nov 26 20:01:07 2019 +0100

    ***************************VICTOR BALLADARES*******************
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ 
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git checkout master
Switched to branch 'master'
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git log
commit 4e13587d9147142137ec45e83cffc4753e48a129 (HEAD -> master)
Author: rastaman10 <selasilay10@hotmail.com>
Date:   Tue Nov 26 20:19:04 2019 +0100

    he hagragado un gitignore

commit f8cd82658d18e798ff310707805e610534442289
Author: rastaman10 <selasilay10@hotmail.com>
Date:   Tue Nov 26 20:11:48 2019 +0100

    ************* Ahora el index.html tiene codigo html

commit abe04603a89a7813309a03094e2e10f67e230208
Author: rastaman10 <rasmanroots@MacBook-Pro-de-Rasman.local>
Date:   Tue Nov 26 20:01:07 2019 +0100

    ***************************VICTOR BALLADARES*******************

commit acc16ad308c3048ba7e9e5987544b022fc04c928
Author: Rasman <rasmanroots@MacBook-Pro-de-Rasman.local>
Date:   Tue Nov 26 19:52:05 2019 +0100

    ***************Practica de git hub por VICTOR BALLADARES*****************
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ 
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ 
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git remote add origin https://github.com/rastaman10/Practica2GITHUB.git
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git status
On branch master
nothing to commit, working tree clean
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ git push -u origin master
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 4 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (15/15), 1.38 KiB | 705.00 KiB/s, done.
Total 15 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/rastaman10/Practica2GITHUB.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
MacBook-Pro-de-Rasman:Practica entornos git hub rasmanroots$ 
