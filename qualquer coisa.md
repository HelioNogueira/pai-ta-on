qualquer coisa


309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~
$ ssh-keygen
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/309 - SUPER09/.ssh/id_ed25519):
Created directory '/c/Users/309 - SUPER09/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/309 - SUPER09/.ssh/id_ed25519
Your public key has been saved in /c/Users/309 - SUPER09/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:QWiOrEnn2L2oTiL09eULEz1kf1c74SDQSt6tf9jiWNo 309 - SUPER09@DESKTOP-M5OMQSP
The key's randomart image is:
+--[ED25519 256]--+
|       ....      |
|      o. ...     |
|   . +  +oo... ..|
|  . + . ++....o +|
| o B o .S+ ... = |
|. = + o + ... . .|
|o .. . = .  ..o  |
|.o  . . o . =+ o |
| .o.     . o.Eo  |
+----[SHA256]-----+

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~
$ git clone git@github.com:HelioNogueira/pai-ta-on.git
Cloning into 'pai-ta-on'...
ssh: connect to host github.com port 22: Connection timed out
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~
$ git clone git@github.com:HelioNogueira/pai-ta-on.git
Cloning into 'pai-ta-on'...
he authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Please type 'yes', 'no' or the fingerprint: yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~
$ cd pai-ta-on/

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ code .

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git add .

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git commit -m "isso ae mn"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git push
Everything up-to-date

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        qualquer coisa.md

nothing added to commit but untracked files present (use "git add" to track)

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git add .

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   qualquer coisa.md


309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git commit -m " bom dia "
[main 96f77a8]  bom dia
 1 file changed, 1 insertion(+)
 create mode 100644 qualquer coisa.md

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 299 bytes | 299.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:HelioNogueira/pai-ta-on.git
   e1f3aa3..96f77a8  main -> main

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git branch
* main

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git checkout -b font_end
Switched to a new branch 'font_end'

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (font_end)
$ git branch
* font_end
  main

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (font_end)
$ git status
On branch font_end
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   qualquer coisa.md

no changes added to commit (use "git add" and/or "git commit -a")

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (font_end)
$ git add .

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (font_end)
$ git commit -m " teste de envio "
[font_end d725bfb]  teste de envio
 1 file changed, 2 insertions(+), 1 deletion(-)

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (font_end)
$ git push
fatal: The current branch font_end has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin font_end

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (font_end)
$ ^C

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (font_end)
$   git push --set-upstream origin font_end
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 314 bytes | 314.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'font_end' on GitHub by visiting:
remote:      https://github.com/HelioNogueira/pai-ta-on/pull/new/font_end
remote:
To github.com:HelioNogueira/pai-ta-on.git
 * [new branch]      font_end -> font_end
branch 'font_end' set up to track 'origin/font_end'.

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (font_end)
$  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git branch -b back_end
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
    -v, --[no-]verbose    show hash and subject, give twice for upstream branch
    -q, --[no-]quiet      suppress informational messages
    -t, --[no-]track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --[no-]set-upstream-to <upstream>
                          change the upstream info
    --[no-]unset-upstream unset the upstream info
    --[no-]color[=<when>] use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --[no-]abbrev[=<n>]   use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --[no-]delete     delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --[no-]move       move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    --[no-]omit-empty     do not output a newline after empty formatted refs
    -c, --[no-]copy       copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --[no-]list       list branch names
    --[no-]show-current   show current branch name
    --[no-]create-reflog  create the branch's reflog
    --[no-]edit-description
                          edit the description for the branch
    -f, --[no-]force      force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --[no-]column[=<style>]
                          list branches in columns
    --[no-]sort <key>     field name to sort on
    --[no-]points-at <object>
                          print only branches of the object
    -i, --[no-]ignore-case
                          sorting and filtering are case insensitive
    --[no-]recurse-submodules
                          recurse through submodules
    --[no-]format <format>
                          format to use for the output


309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git checkout -b back_end
Switched to a new branch 'back_end'

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (back_end)
$ git branch
* back_end
  font_end
  main

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (back_end)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git checkout back_end
Switched to branch 'back_end'
M       qualquer coisa.md

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (back_end)
$ git status
On branch back_end
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   qualquer coisa.md

no changes added to commit (use "git add" and/or "git commit -a")

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (back_end)
$ git add .

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (back_end)
$ git commit -m "teste"
[back_end 78ac09a] teste
 1 file changed, 2 insertions(+), 1 deletion(-)

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (back_end)
$ git push
fatal: The current branch back_end has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin back_end

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (back_end)
$ git push --set-upstream origin back_end
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 309 bytes | 309.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'back_end' on GitHub by visiting:
remote:      https://github.com/HelioNogueira/pai-ta-on/pull/new/back_end
remote:
To github.com:HelioNogueira/pai-ta-on.git
 * [new branch]      back_end -> back_end
branch 'back_end' set up to track 'origin/back_end'.

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (back_end)
$ git branch
* back_end
  font_end
  main

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (back_end)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git merge back_end
Updating 96f77a8..78ac09a
Fast-forward
 qualquer coisa.md | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git merge font_end
Auto-merging qualquer coisa.md
CONFLICT (content): Merge conflict in qualquer coisa.md
Automatic merge failed; fix conflicts and then commit the result.

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main|MERGING)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both modified:   qualquer coisa.md

no changes added to commit (use "git add" and/or "git commit -a")

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main|MERGING)
$ git add .

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main|MERGING)
$ git commit -m "resolvendo conflito"
[main d971dca] resolvendo conflito

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 347 bytes | 347.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:HelioNogueira/pai-ta-on.git
   96f77a8..d971dca  main -> main

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (main)
$  branch 'back_end'
  git push
   branch 'back_end'

309 - SUPER09@DESKTOP-M5OMQSP MINGW64 ~/pai-ta-on (back_end)
$ git branch
* back_end
  font_end
  main


