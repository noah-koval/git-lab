1. git version 2.28.0.windows.1
2. diff.astextplain.textconv=astextplain
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
credential.helper=manager
user.name=Noah Koval
user.email=noahkoval.18@gmail.com
3. a list pops up showing common git commands
4.On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)
5. On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md
    
6. On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md
7. On branch master
nothing to commit, working tree clean
8. commit 0e97e1bb775feb9159f07fe8c397d16e546f53c7 (HEAD -> master)
Author: Noah Koval <noahkoval.18@gmail.com>
Date:   Fri Sep 4 14:17:33 2020 -0400

    Initial commit
9. On branch master
Your branch is up to date with 'origin/master'.
10. No
11. ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/noah-koval/git-lab'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
12. Yes
 13. Get-ChildItem : Parameter cannot be processed because the parameter name 'a' is ambiguous. Possible matches include:
-Attributes -Directory -File -Hidden -ReadOnly -System.
At line:1 char:4
+ ls -a
+    ~~
    + CategoryInfo          : InvalidArgument: (:) [Get-ChildItem], ParameterBindingException
    + FullyQualifiedErrorId : AmbiguousParameter,Microsoft.PowerShell.Commands.GetChildItemCommand
14. 