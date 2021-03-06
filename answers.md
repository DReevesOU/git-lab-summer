Answer 1 

git version 2.34.1.windows.1
--------------------------------------------------------------------------------------------------
Answer 2 - git config list shows a all the git config properties. 

diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.email=dr300221@ohio.edu
user.name=Daniel Reeves
--------------------------------------------------------------------------------------------------
Answer 3 - Shows the most commonly used git commands and examples of git usage. 

usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]    
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

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
--------------------------------------------------------------------------------------------------
Answer 4 - The files README.md and answers.md are not yet ready to be committed. 

On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)
--------------------------------------------------------------------------------------------------
Answer 5 - README.md has been staged. 

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md
--------------------------------------------------------------------------------------------------
Answer 6 - README.md and answers.md have been staged.

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md
--------------------------------------------------------------------------------------------------
Answer 7 - changes to answers.md, nothing is staged. 

On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")
--------------------------------------------------------------------------------------------------
Answer 8 - git log

commit 288f29db4d592145014662de085c7cb403de9e96 (HEAD -> master)
Author: Daniel Reeves <dr300221@ohio.edu>
Date:   Fri May 13 15:22:14 2022 -0400

    Initial commit
--------------------------------------------------------------------------------------------------
Answer 9 

The repository has an initial commit with the previous hash with the README.md and answers.md files. 
--------------------------------------------------------------------------------------------------
Answer 10

The changes were not reflected in my local copy. 
--------------------------------------------------------------------------------------------------
Answer 11 - The push was rejected because the remote contains work that is not reflected locally.

! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/DReevesOU/git-lab-summer'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

--------------------------------------------------------------------------------------------------
Answer 12 - The changes I made online are now reflected locally. 

--------------------------------------------------------------------------------------------------
Answer 13 



    Directory: C:\Users\Dan\Desktop\git-lab\git-lab-2-summer


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         5/13/2022   6:37 PM            302 .gitignore
-a----         5/13/2022   6:37 PM             18 README.md

--------------------------------------------------------------------------------------------------







