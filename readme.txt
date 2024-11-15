Microsoft Windows [Versión 10.0.22631.4317]
(c) Microsoft Corporation. Todos los derechos reservados.

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>code .

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git init
Initialized empty Git repository in C:/Users/luisv/Documents/Talento Tech/Programación Basica/2. Trabajando con Git/Sesión 6/Laboratorio/.git/

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git init
Reinitialized existing Git repository in C:/Users/luisv/Documents/Talento Tech/Programación Basica/2. Trabajando con Git/Sesión 6/Laboratorio/.git/

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git add index.html

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html


C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git commit -m "Version con index.html y titulo primario"
[master (root-commit) 3abfc02] Version con index.html y titulo primario
 1 file changed, 12 insertions(+)
 create mode 100644 index.html

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git status
On branch master
nothing to commit, working tree clean

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git add .

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html


C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git branch rama-ves
ion-3

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git branch
* master
  rama-vesion-3

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git checkout rama-v
ersion-3
error: pathspec 'rama-version-3' did not match any file(s) known to git

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git checkout rama-v
ersion-3
error: pathspec 'rama-version-3' did not match any file(s) known to git

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git checkout rama-v
esion-3
M       index.html
Switched to branch 'rama-vesion-3'

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git add .

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git log
commit 3abfc02d893fd02bf1ed5dad7a77745aab5bb495 (HEAD -> rama-vesion-3, master)
Author: Luis Carlos Velaides Rincon <luis.velaidesrincon.ttc.273@unilibre.edu.co>
Date:   Fri Nov 15 09:11:16 2024 -0500

    Version con index.html y titulo primario

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git commit git stat
us
error: pathspec 'git' did not match any file(s) known to git
error: pathspec 'status' did not match any file(s) known to git

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git status
On branch rama-vesion-3
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html


C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git checkout master

M       index.html
Switched to branch 'master'

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>code .

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git merge rama-vesion-3
Already up to date.

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git log
commit 3abfc02d893fd02bf1ed5dad7a77745aab5bb495 (HEAD -> master, rama-vesion-3)
Author: Luis Carlos Velaides Rincon <luis.velaidesrincon.ttc.273@unilibre.edu.co>
Date:   Fri Nov 15 09:11:16 2024 -0500

    Version con index.html y titulo primario

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git remote add origin https://github.com/LuisCarlos2025/Talento-Tech.git

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git global --list
git: 'global' is not a git command. See 'git --help'.

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git push -u origin
master
remote: Permission to LuisCarlos2025/Talento-Tech.git denied to luisk0009.
fatal: unable to access 'https://github.com/LuisCarlos2025/Talento-Tech.git/': The requested URL returned error: 403

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git log
commit 3abfc02d893fd02bf1ed5dad7a77745aab5bb495 (HEAD -> master, rama-vesion-3)
Author: Luis Carlos Velaides Rincon <luis.velaidesrincon.ttc.273@unilibre.edu.co>
Date:   Fri Nov 15 09:11:16 2024 -0500

    Version con index.html y titulo primario

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git push -u origin
master
remote: Permission to LuisCarlos2025/Talento-Tech.git denied to luisk0009.
fatal: unable to access 'https://github.com/LuisCarlos2025/Talento-Tech.git/': The requested URL returned error: 403

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git credential-mana
ger erase

fatal: Missing 'protocol' input argument

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git credential mana
ger erase
usage: git credential (fill|approve|reject)

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git push -u origin
master  https://github.com/LuisCarlos2025/Talento-Tech.git
fatal: invalid refspec 'https://github.com/LuisCarlos2025/Talento-Tech.git'

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git remote add origin https://github.com/LuisCarlos2025/Talento-Tech.git
error: remote origin already exists.

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>push -u origin mast
er
"push" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git push -u origin
master
remote: Permission to LuisCarlos2025/Talento-Tech.git denied to luisk0009.
fatal: unable to access 'https://github.com/LuisCarlos2025/Talento-Tech.git/': The requested URL returned error: 403

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git remote add orig
in https://github.com/LuisCarlos2025/Talento-Tech.git
error: remote origin already exists.

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git push -u origin
masater
error: src refspec masater does not match any
error: failed to push some refs to 'https://github.com/LuisCarlos2025/Talento-Tech.git'

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git push origin mas
ter
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 460 bytes | 460.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/LuisCarlos2025/Talento-Tech.git
 * [new branch]      master -> master

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>https://github.com/LuisCarlos2025/Talento-Tech.git

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git commit -a "codigo de laboratorio
fatal: paths 'codigo de laboratorio ...' with -a does not make sense

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git commit -a "codigo de laboratorio"
fatal: paths 'codigo de laboratorio ...' with -a does not make sense

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git push --set-upstream origin master
branch 'master' set up to track 'origin/master'.
Everything up-to-date

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git add .

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git commit -m "codigo de ejemplo de laboratorio"
[master 40c2da7] codigo de ejemplo de laboratorio
 2 files changed, 2 insertions(+)
 create mode 100644 readme.txt

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git push -u origin
master
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 459 bytes | 459.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/LuisCarlos2025/Talento-Tech.git
   3abfc02..40c2da7  master -> master
branch 'master' set up to track 'origin/master'.

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git push -u origin
master
branch 'master' set up to track 'origin/master'.
Everything up-to-date

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>git push -u origin
master
branch 'master' set up to track 'origin/master'.
Everything up-to-date

C:\Users\luisv\Documents\Talento Tech\Programación Basica\2. Trabajando con Git\Sesión 6\Laboratorio>