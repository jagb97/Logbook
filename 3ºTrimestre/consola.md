
juan@DESKTOP-2N8KECL MINGW64 /logbook/1ºTrimestre (master)
$ cd ..

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ cd 2ºTrimestre/

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   "../1\302\272Trimestre/.gitignore"

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        "../1\302\272Trimestre/1\302\272Trimestre.zip"
        "../1\302\272Trimestre/consola.md"
        211210.md


juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git add 211210.md

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ mkdir dosfotos

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git add
.gitignore  211210.md   dosfotos/

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git add dos
fatal: pathspec 'dos' did not match any files

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git add dosfotos/

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   "../1\302\272Trimestre/.gitignore"
        new file:   211210.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        "../1\302\272Trimestre/1\302\272Trimestre.zip"
        "../1\302\272Trimestre/consola.md"


juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git add
.gitignore  211210.md   dosfotos/

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git add 211210.md

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ cd ..

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ cd 1ºTrimestre/

juan@DESKTOP-2N8KECL MINGW64 /logbook/1ºTrimestre (master)
$ git add consola.md

juan@DESKTOP-2N8KECL MINGW64 /logbook/1ºTrimestre (master)
$ git commit -m "Los comandos del primer trimestre y la corrección"
[master 2353de4] Los comandos del primer trimestre y la corrección
 3 files changed, 1511 insertions(+), 1 deletion(-)
 create mode 100644 "1\302\272Trimestre/consola.md"
 create mode 100644 "2\302\272Trimestre/211210.md"

juan@DESKTOP-2N8KECL MINGW64 /logbook/1ºTrimestre (master)
$ git push
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 6.77 KiB | 6.77 MiB/s, done.
Total 7 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:jagb97/Logbook.git
   ca73000..2353de4  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook/1ºTrimestre (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore

no changes added to commit (use "git add" and/or "git commit -a")

juan@DESKTOP-2N8KECL MINGW64 /logbook/1ºTrimestre (master)
$ git add .gitignore

juan@DESKTOP-2N8KECL MINGW64 /logbook/1ºTrimestre (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   .gitignore


juan@DESKTOP-2N8KECL MINGW64 /logbook/1ºTrimestre (master)
$ git add .gitignore

juan@DESKTOP-2N8KECL MINGW64 /logbook/1ºTrimestre (master)
$ git commit -m "ignorando el .zip"
[master 4b4c1a4] ignorando el .zip
 1 file changed, 1 insertion(+), 1 deletion(-)

juan@DESKTOP-2N8KECL MINGW64 /logbook/1ºTrimestre (master)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 386 bytes | 386.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:jagb97/Logbook.git
   2353de4..4b4c1a4  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook/1ºTrimestre (master)
$ cd ..

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ cd 2ºTrimestre/

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        220130.md
        dosfotos/

nothing added to commit but untracked files present (use "git add" to track)

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git add a.
fatal: pathspec 'a.' did not match any files

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git add .

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git commit -m "simulaciones lógicas y flip flops"
[master 04e9dd8] simulaciones lógicas y flip flops
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 "2\302\272Trimestre/220130.md"
 create mode 100644 "2\302\272Trimestre/dosfotos/flipflop.jfif"

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 5.47 KiB | 5.47 MiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:jagb97/Logbook.git
   4b4c1a4..04e9dd8  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git add
220215.md  dosfotos/

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git add .

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   220215.md
        new file:   dosfotos/semaforo.jfif


juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git commit -m "el terror del marcha paro de las vías"
[master 8ef30d7] el terror del marcha paro de las vías
 2 files changed, 5 insertions(+)
 create mode 100644 "2\302\272Trimestre/220215.md"
 create mode 100644 "2\302\272Trimestre/dosfotos/semaforo.jfif"

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 12.24 KiB | 1.36 MiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:jagb97/Logbook.git
   04e9dd8..8ef30d7  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git add .

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git commit -m "cogiendo sabiduría"
[master 7a2ffa8] cogiendo sabiduría
 1 file changed, 5 insertions(+)
 create mode 100644 "2\302\272Trimestre/220224.md"

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ git push
To github.com:jagb97/Logbook.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'github.com:jagb97/Logbook.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

juan@DESKTOP-2N8KECL MINGW64 /logbook/2ºTrimestre (master)
$ cd ..

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git add .
warning: LF will be replaced by CRLF in 3ºTrimestre/tresfotos/homer.htm.
The file will have its original line endings in your working directory

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   "3\302\272Trimestre/tresfotos/homer.htm"
        modified:   README.md


juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git pusch
git: 'pusch' is not a git command. See 'git --help'.

The most similar command is
        push

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
To github.com:jagb97/Logbook.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'github.com:jagb97/Logbook.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   "3\302\272Trimestre/tresfotos/homer.htm"
        modified:   README.md


juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git add .

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   "3\302\272Trimestre/tresfotos/homer.htm"
        modified:   README.md


juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
To github.com:jagb97/Logbook.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'github.com:jagb97/Logbook.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git commit -m "sabiduría"
[master 8342306] sabiduría
 2 files changed, 5 insertions(+)
 create mode 100644 "3\302\272Trimestre/tresfotos/homer.htm"

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
To github.com:jagb97/Logbook.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'github.com:jagb97/Logbook.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   "2\302\272Trimestre/.gitignore"
        modified:   "2\302\272Trimestre/220130.md"

no changes added to commit (use "git add" and/or "git commit -a")

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git add .

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
To github.com:jagb97/Logbook.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'github.com:jagb97/Logbook.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git commit -M "sabiduría"
error: unknown switch `M'
usage: git commit [<options>] [--] <pathspec>...

    -q, --quiet           suppress summary after successful commit
    -v, --verbose         show diff in commit message template

Commit message options
    -F, --file <file>     read message from file
    --author <author>     override author for commit
    --date <date>         override date for commit
    -m, --message <message>
                          commit message
    -c, --reedit-message <commit>
                          reuse and edit message from specified commit
    -C, --reuse-message <commit>
                          reuse message from specified commit
    --fixup [(amend|reword):]commit
                          use autosquash formatted message to fixup or amend/reword specified commit
    --squash <commit>     use autosquash formatted message to squash specified commit
    --reset-author        the commit is authored by me now (used with -C/-c/--amend)
    --trailer <trailer>   add custom trailer(s)
    -s, --signoff         add a Signed-off-by trailer
    -t, --template <file>
                          use specified template file
    -e, --edit            force edit of commit
    --cleanup <mode>      how to strip spaces and #comments from message
    --status              include status in commit message template
    -S, --gpg-sign[=<key-id>]
                          GPG sign commit

Commit contents options
    -a, --all             commit all changed files
    -i, --include         add specified files to index for commit
    --interactive         interactively add files
    -p, --patch           interactively add changes
    -o, --only            commit only specified files
    -n, --no-verify       bypass pre-commit and commit-msg hooks
    --dry-run             show what would be committed
    --short               show status concisely
    --branch              show branch information
    --ahead-behind        compute full ahead/behind values
    --porcelain           machine-readable output
    --long                show status in long format (default)
    -z, --null            terminate entries with NUL
    --amend               amend previous commit
    --no-post-rewrite     bypass post-rewrite hook
    -u, --untracked-files[=<mode>]
                          show untracked files, optional modes: all, normal, no. (Default: all)
    --pathspec-from-file <file>
                          read pathspec from file
    --pathspec-file-nul   with --pathspec-from-file, pathspec elements are separated with NUL character


juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git commit -m "sabiduría"
[master 8313841] sabiduría
 2 files changed, 6 insertions(+)

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
To github.com:jagb97/Logbook.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'github.com:jagb97/Logbook.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
Unpacking objects: 100% (3/3), 696 bytes | 87.00 KiB/s, done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
From github.com:jagb97/Logbook
   8ef30d7..97882f0  master     -> origin/master
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.

juan@DESKTOP-2N8KECL MINGW64 /logbook (master|MERGING)
$ git status
On branch master
Your branch and 'origin/master' have diverged,
and have 3 and 1 different commits each, respectively.
  (use "git pull" to merge the remote branch into yours)

You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

juan@DESKTOP-2N8KECL MINGW64 /logbook (master|MERGING)
$ git add .
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

juan@DESKTOP-2N8KECL MINGW64 /logbook (master|MERGING)
$ git add .

juan@DESKTOP-2N8KECL MINGW64 /logbook (master|MERGING)
$ git status
On branch master
Your branch and 'origin/master' have diverged,
and have 3 and 1 different commits each, respectively.
  (use "git pull" to merge the remote branch into yours)

All conflicts fixed but you are still merging.
  (use "git commit" to conclude merge)

Changes to be committed:
        modified:   README.md


juan@DESKTOP-2N8KECL MINGW64 /logbook (master|MERGING)
$ git commit -m "sabiduria"
[master 8dbf281] sabiduria

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
Enumerating objects: 30, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 16 threads
Compressing objects: 100% (16/16), done.
Writing objects: 100% (18/18), 53.20 KiB | 523.00 KiB/s, done.
Total 18 (delta 5), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (5/5), completed with 2 local objects.
To github.com:jagb97/Logbook.git
   97882f0..8dbf281  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git a
add        am         apply      archive    askpass    askyesno

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git add README.md
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
Everything up-to-date

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git checkout master
Already on 'master'
M       README.md
Your branch is up to date with 'origin/master'.

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git commit -m "sabiduria"
[master 2a5c45f] sabiduria
 1 file changed, 3 insertions(+), 4 deletions(-)

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 344 bytes | 344.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:jagb97/Logbook.git
   8dbf281..2a5c45f  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git add .
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git commit
hint: Waiting for your editor to close the file...
[master 07f754b]  Sabiduría
 1 file changed, 2 deletions(-)

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 347 bytes | 347.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:jagb97/Logbook.git
   2a5c45f..07f754b  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git add .
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git commit -m "sabiduría 2.0"
[master 9a991f5] sabiduría 2.0
 2 files changed, 1 insertion(+), 1 deletion(-)
 create mode 100644 "3\302\272Trimestre/tresfotos/exams-exam-memes.gif"

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 5.18 MiB | 3.66 MiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:jagb97/Logbook.git
   07f754b..9a991f5  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git add .

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git commit -m "examen segunda evaluación"
[master 5257310] examen segunda evaluación
 2 files changed, 2 insertions(+)
 create mode 100644 "3\302\272Trimestre/tresfotos/books-week.gif"

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 16 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 1.15 MiB | 9.17 MiB/s, done.
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:jagb97/Logbook.git
   9a991f5..5257310  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git add .

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git commit -m "comandos del segundo trimestre"
[master a3f04fb] comandos del segundo trimestre
 2 files changed, 641 insertions(+)
 create mode 100644 "2\302\272Trimestre/consola.md"
 create mode 100644 "3\302\272Trimestre/tresfotos/on-fire-flames.gif"

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 16 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 27.56 KiB | 3.44 MiB/s, done.
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:jagb97/Logbook.git
   5257310..a3f04fb  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git add .

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git commit -m "aun más perdidos"
[master 9aa2755] aun más perdidos
 2 files changed, 8 insertions(+)
 create mode 100644 "3\302\272Trimestre/220304.md"
 create mode 100644 "3\302\272Trimestre/tresfotos/funny-celebrate-56.gif"

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 469.89 KiB | 3.76 MiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:jagb97/Logbook.git
   a3f04fb..9aa2755  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git add .

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git commit -m "aún más perdidos 2.0"
[master 0fd62c9] aún más perdidos 2.0
 2 files changed, 4 insertions(+), 1 deletion(-)
 create mode 100644 "3\302\272Trimestre/tresfotos/descarga.jfif"

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 4.20 KiB | 4.20 MiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To github.com:jagb97/Logbook.git
   9aa2755..0fd62c9  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git add .

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git commit -m "Desesperante"
[master 60e2342] Desesperante
 1 file changed, 3 insertions(+)
 create mode 100644 "3\302\272Trimestre/220330.md"

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ gi push
bash: gi: command not found

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 518 bytes | 518.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:jagb97/Logbook.git
   0fd62c9..60e2342  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git add .

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git commit -m "cuestionarios del tercer trimestre"
[master daea475] cuestionarios del tercer trimestre
 1 file changed, 5 insertions(+)
 create mode 100644 "3\302\272Trimestre/220501.md"

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 482 bytes | 482.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:jagb97/Logbook.git
   60e2342..daea475  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git add .

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git commit -m "trabajo final"
[master 75e3240] trabajo final
 2 files changed, 17 insertions(+)
 create mode 100644 "3\302\272Trimestre/220515.md"
 create mode 100644 "3\302\272Trimestre/tresfotos/instalacion-y-venta-placas-solares.gif"

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 18.61 KiB | 6.20 MiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To github.com:jagb97/Logbook.git
   daea475..75e3240  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   "3\302\272Trimestre/.gitignore"

no changes added to commit (use "git add" and/or "git commit -a")

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git add .

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git commit -m "ignorando el .zip del tercer trimestre"
[master 10c1e40] ignorando el .zip del tercer trimestre
 1 file changed, 1 insertion(+)

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 376 bytes | 376.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:jagb97/Logbook.git
   75e3240..10c1e40  master -> master

juan@DESKTOP-2N8KECL MINGW64 /logbook (master)
$
