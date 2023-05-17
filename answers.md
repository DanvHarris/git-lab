/////////////Answer 1/////////////

git version 2.40.1.windows.1

/////////////Answer 2/////////////

diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
core.editor="C:\Users\dvhar\AppData\Local\Programs\Microsoft VS Code\bin\code" --wait
user.name=Daniel Harris
user.email=dh783111@ohio.edu

/////////////Answer 3/////////////

usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

/////////////Answer 4/////////////

On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

/////////////Answer 5/////////////

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

/////////////Answer 6/////////////

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

/////////////Answer 7/////////////

On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

/////////////Answer 8/////////////

commit c2f1b7600e88384d0c2c8b1f9f3afae3e11c34a1 (HEAD -> master)
Author: Daniel Harris <dh783111@ohio.edu>
Date:   Wed May 17 10:12:07 2023 -0500

    Initial commit

/////////////Answer 9/////////////

On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

/////////////Answer 10/////////////

commit b6f6cd97a747d47367149e4a24037e38507e7d5a (HEAD -> main, origin/main)
Author: Daniel Harris <dh783111@ohio.edu>
Date:   Wed May 17 10:25:58 2023 -0500

    committing from step 9 answers in answers.md

diff --git a/README.md b/README.md
index 727565f..07cdcd1 100644
--- a/README.md
+++ b/README.md
@@ -1,2 +1,4 @@
-Daniel James Harris
-DanvHarris
\ No newline at end of file
+Full Name: Daniel James Harris
+GitHub User ID: DanvHarris
+Email: dh783111@ohio.edu
+Comments: Answers are recorded in answers.md within the project repository or https://github.com/DanvHarris/git-lab/blob/main/answers.md for direct link.
\ No newline at end of file
//
//This is not how it appears in the online repository due to the prior changes via GitHub(as of step 11)

/////////////Answer 11/////////////

To https://github.com/DanvHarris/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/DanvHarris/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

/////////////Answer 12/////////////

commit f49b58065f8d4ccd713c6ddc7be9d373e6ff5b8d (HEAD -> main, origin/main)
Author: Dan Harris <dvharris93@gmail.com>
Date:   Wed May 17 09:28:45 2023 -0500

    adding class info to readme

diff --git a/README.md b/README.md
index 07cdcd1..096ee25 100644
--- a/README.md
+++ b/README.md
@@ -1,4 +1,5 @@
 Full Name: Daniel James Harris
 GitHub User ID: DanvHarris
 Email: dh783111@ohio.edu
-Comments: Answers are recorded in answers.md within the project repository or https://github.com/DanvHarris/git-lab/blob/main/answers.md for direct link.
\ No newline at end of file
+Comments: Answers are recorded in answers.md within the project repository or https://github.com/DanvHarris/git-lab/blob/main/answers.md for direct link.
+Class Info: CS2400, Summer 2023, Online
//
//This is how it shows in the online repository due to pulling the changes from remote

/////////////Answer 13/////////////

./  ../  .git/  .gitignore  README.md

