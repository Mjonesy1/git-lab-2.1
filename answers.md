* answer 1. git version 2.35.0.windows.1
* answer 2. PS C:\Users\mrj04\git-lab> git config --list
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
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
filter.lfs.clean=git-lfs clean -- %f
user.name=Makenna
user.email=mj584620@ohio.edu
core.editor="C:\Users\mrj04\AppData\Local\Programs\Microsoft VS Code\bin\code" --wait
* answer 3. When I entered git add --help it took me to a manual page for git add and all of the different commands that could be included with it. When I entered git --help on its own my terminal brought up a list of every command you could use for the git --help command and how they all worked.
* answer4. PS C:\Users\mrj04\git-lab> git add README.md
PS C:\Users\mrj04\git-lab> git add answers.md
PS C:\Users\mrj04\git-lab> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md
* answer 5. I already finished this step accidently in step 4. In step 4 before I did the git add README.md command my terminal told me I had untracked files. Once I issued the command my terminal told me that there were changes to be committed. I hope this explanation is enough for the answer.
* answer 6. Once again I completed this step in answer 4. I issued README.md and answers.md at the same time and got the same results.
* answer 7. PS C:\Users\mrj04\git-lab> git commit -m "Initial commit"
[master (root-commit) d6b4b58] Initial commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
 create mode 100644 answers.md
PS C:\Users\mrj04\git-lab> git commit -m "Initial commit"
On branch master
nothing to commit, working tree clean
* answer 7 cont. Once I committed my changed were acknoledged. When I tried to issue the command again my terminal told me that there was nothing new to commit.
* answer 8. PS C:\Users\mrj04\git-lab> git log
commit d6b4b5836fbca9e3d72d744c30ab776824b2e679 (HEAD -> master)
Author: Makenna <mj584620@ohio.edu>
Date:   Fri Jan 26 14:59:23 2024 -0500

    Initial commit
* answer 9. PS C:\Users\mrj04\git-lab> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
* answer 10. My changes didn't look like they were there.
* answer 11. PS C:\Users\mrj04\git-lab> git push
To https://github.com/Mjonesy1/git-lab2.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Mjonesy1/git-lab2.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
* answer 12. PS C:\Users\mrj04\git-lab> git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 952 bytes | 136.00 KiB/s, done.
From https://github.com/Mjonesy1/git-lab2
   d6b4b58..f50ba44  main       -> origin/main
Updating d6b4b58..f50ba44
Fast-forward
 README.md | Bin 6 -> 30 bytes
 1 file changed, 0 insertions(+), 0 deletions(-)
I don't think there were any changes
* answer 13. (Note: I named the repository a little differently because I already had pre-existing repositories from another class)
PS C:\Users\mrj04\2400\git-lab-2.1> ls -a
Get-ChildItem : Parameter cannot be processed because the parameter name 'a' is ambiguous. Possible matches include:
-Attributes -Directory -File -Hidden -ReadOnly -System.
At line:1 char:4
+ ls -a
+    ~~
    + CategoryInfo          : InvalidArgument: (:) [Get-ChildItem], ParameterBindingException
    + FullyQualifiedErrorId : AmbiguousParameter,Microsoft.PowerShell.Commands.GetChildItemCommand
