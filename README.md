Microsoft Windows [Version 10.0.22631.3235]
(c) Microsoft Corporation. All rights reserved.

C:\Users\HP\Downloads\gits>git init
Initialized empty Git repository in C:/Users/HP/Downloads/gits/.git/

C:\Users\HP\Downloads\gits>git add example.txt

C:\Users\HP\Downloads\gits>git commit -m "first commit"
[master (root-commit) da4e156] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 example.txt

C:\Users\HP\Downloads\gits>git branch -M main

C:\Users\HP\Downloads\gits>git remote add origin https://github.com/GangaSagarReddy/git_tuts.git

C:\Users\HP\Downloads\gits>git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 232 bytes | 77.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/GangaSagarReddy/git_tuts.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

C:\Users\HP\Downloads\gits>git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Users\HP\Downloads\gits>git add example2.txt

C:\Users\HP\Downloads\gits>git commit -m "example2"
[main 83432e8] example2
 1 file changed, 1 insertion(+)
 create mode 100644 example2.txt

C:\Users\HP\Downloads\gits>git branch -M main

C:\Users\HP\Downloads\gits>git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 296 bytes | 296.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/GangaSagarReddy/git_tuts.git
   da4e156..83432e8  main -> main
branch 'main' set up to track 'origin/main'.

C:\Users\HP\Downloads\gits>git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Users\HP\Downloads\gits>git branch
* main

C:\Users\HP\Downloads\gits>git branch -b "Branch1:
error: unknown switch `b'
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --verbose         show hash and subject, give twice for upstream branch
    -q, --quiet           suppress informational messages
    -t, --track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --set-upstream-to <upstream>
                          change the upstream info
    --unset-upstream      unset the upstream info
    --color[=<when>]      use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --abbrev[=<n>]        use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --delete          delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --move            move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    --omit-empty          do not output a newline after empty formatted refs
    -c, --copy            copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --list            list branch names
    --show-current        show current branch name
    --create-reflog       create the branch's reflog
    --edit-description    edit the description for the branch
    -f, --force           force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --column[=<style>]    list branches in columns
    --sort <key>          field name to sort on
    --points-at <object>  print only branches of the object
    -i, --ignore-case     sorting and filtering are case insensitive
    --recurse-submodules  recurse through submodules
    --format <format>     format to use for the output


C:\Users\HP\Downloads\gits>git branch -b "Branch1"
error: unknown switch `b'
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --verbose         show hash and subject, give twice for upstream branch
    -q, --quiet           suppress informational messages
    -t, --track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --set-upstream-to <upstream>
                          change the upstream info
    --unset-upstream      unset the upstream info
    --color[=<when>]      use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --abbrev[=<n>]        use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --delete          delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --move            move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    --omit-empty          do not output a newline after empty formatted refs
    -c, --copy            copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --list            list branch names
    --show-current        show current branch name
    --create-reflog       create the branch's reflog
    --edit-description    edit the description for the branch
    -f, --force           force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --column[=<style>]    list branches in columns
    --sort <key>          field name to sort on
    --points-at <object>  print only branches of the object
    -i, --ignore-case     sorting and filtering are case insensitive
    --recurse-submodules  recurse through submodules
    --format <format>     format to use for the output


C:\Users\HP\Downloads\gits>git checkout
Your branch is up to date with 'origin/main'.

C:\Users\HP\Downloads\gits>git checkout -b "Branch1"
Switched to a new branch 'Branch1'

C:\Users\HP\Downloads\gits>git status
On branch Branch1
nothing to commit, working tree clean

C:\Users\HP\Downloads\gits>git status
On branch Branch1
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        code.py

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\HP\Downloads\gits>git add code.py

C:\Users\HP\Downloads\gits>git commit -m "new branch"
[Branch1 a04ea69] new branch
 1 file changed, 1 insertion(+)
 create mode 100644 code.py

C:\Users\HP\Downloads\gits>git branch -M origin Branch1
fatal: No branch named 'origin'.

C:\Users\HP\Downloads\gits>git branch
* Branch1
  main

C:\Users\HP\Downloads\gits>git push -u origin Branch1
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 321 bytes | 321.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'Branch1' on GitHub by visiting:
remote:      https://github.com/GangaSagarReddy/git_tuts/pull/new/Branch1
remote:
To https://github.com/GangaSagarReddy/git_tuts.git
 * [new branch]      Branch1 -> Branch1
branch 'Branch1' set up to track 'origin/Branch1'.

C:\Users\HP\Downloads\gits>git status
On branch Branch1
Your branch is up to date with 'origin/Branch1'.

nothing to commit, working tree clean

C:\Users\HP\Downloads\gits>git checkout -b "Branch2"
Switched to a new branch 'Branch2'

C:\Users\HP\Downloads\gits>git add .

C:\Users\HP\Downloads\gits>git commit -m "Branch2"
On branch Branch2
nothing to commit, working tree clean

C:\Users\HP\Downloads\gits>git push -u origin Branch2
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'Branch2' on GitHub by visiting:
remote:      https://github.com/GangaSagarReddy/git_tuts/pull/new/Branch2
remote:
To https://github.com/GangaSagarReddy/git_tuts.git
 * [new branch]      Branch2 -> Branch2
branch 'Branch2' set up to track 'origin/Branch2'.

C:\Users\HP\Downloads\gits>git status
On branch Branch2
Your branch is up to date with 'origin/Branch2'.

nothing to commit, working tree clean

C:\Users\HP\Downloads\gits>git branch
  Branch1
* Branch2
  main

C:\Users\HP\Downloads\gits>git checkout Branch1
Switched to branch 'Branch1'
M       example.txt
Your branch is up to date with 'origin/Branch1'.

C:\Users\HP\Downloads\gits>git add .

C:\Users\HP\Downloads\gits>git status
On branch Branch1
Your branch is up to date with 'origin/Branch1'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   example.txt


C:\Users\HP\Downloads\gits>git commit -m "updated example"
[Branch1 def1873] updated example
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\HP\Downloads\gits> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 336 bytes | 336.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/GangaSagarReddy/git_tuts.git
   a04ea69..def1873  Branch1 -> Branch1

C:\Users\HP\Downloads\gits>git status
On branch Branch1
Your branch is up to date with 'origin/Branch1'.

nothing to commit, working tree clean

C:\Users\HP\Downloads\gits>git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 894 bytes | 298.00 KiB/s, done.
From https://github.com/GangaSagarReddy/git_tuts
   83432e8..88243e2  main       -> origin/main
Already up to date.

C:\Users\HP\Downloads\gits>git merge
Already up to date.

C:\Users\HP\Downloads\gits>git merge main
Already up to date.

C:\Users\HP\Downloads\gits>git checkout main
Switched to branch 'main'
Your branch is behind 'origin/main' by 2 commits, and can be fast-forwarded.
  (use "git pull" to update your local branch)

C:\Users\HP\Downloads\gits>git pull
Updating 83432e8..88243e2
Fast-forward
 code.py | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 code.py

C:\Users\HP\Downloads\gits>git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Users\HP\Downloads\gits>git checkout Branch2
Switched to branch 'Branch2'
M       example.txt
Your branch is up to date with 'origin/Branch2'.

C:\Users\HP\Downloads\gits>git status
On branch Branch2
Your branch is up to date with 'origin/Branch2'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   example.txt

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\HP\Downloads\gits>git add example.txt

C:\Users\HP\Downloads\gits>git commit -m "updated"
[Branch2 e16962d] updated
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\HP\Downloads\gits>git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 339 bytes | 339.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/GangaSagarReddy/git_tuts.git
   a04ea69..e16962d  Branch2 -> Branch2

C:\Users\HP\Downloads\gits>git merge
Already up to date.

C:\Users\HP\Downloads\gits>git merge origin/main
Merge made by the 'ort' strategy.

C:\Users\HP\Downloads\gits>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

C:\Users\HP\Downloads\gits>git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 902 bytes | 451.00 KiB/s, done.
From https://github.com/GangaSagarReddy/git_tuts
   88243e2..08e1da6  main       -> origin/main
Updating 88243e2..08e1da6
Fast-forward
 example.txt | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\HP\Downloads\gits>git checkout Branch2
Switched to branch 'Branch2'
Your branch is ahead of 'origin/Branch2' by 2 commits.
  (use "git push" to publish your local commits)

C:\Users\HP\Downloads\gits>git merge origin/main
Auto-merging example.txt
CONFLICT (content): Merge conflict in example.txt
Automatic merge failed; fix conflicts and then commit the result.

C:\Users\HP\Downloads\gits>git status
On branch Branch2
Your branch is ahead of 'origin/Branch2' by 2 commits.
  (use "git push" to publish your local commits)

You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both modified:   example.txt

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\HP\Downloads\gits>git add .

C:\Users\HP\Downloads\gits>git commit -m "updated by Branch2"
[Branch2 253e062] updated by Branch2

C:\Users\HP\Downloads\gits>git push
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 603 bytes | 603.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/GangaSagarReddy/git_tuts.git
   e16962d..253e062  Branch2 -> Branch2
