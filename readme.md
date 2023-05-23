# Git exercise project

this project will be used for a series of git exercises
### bundle1
### exercise 2
...bash
Warning: PowerShell detected that you might be using a screen reader and has disabled PSReadLine for compatibility purposes. If you want to re-enable it, run 'Import-Module PSReadLine'.

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git branch dev
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git checkout
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Your branch is up to date with 'origin/main'.
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)        
        index.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git add index.html
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git branch main
 dev
fatal: a branch named 'main' already exists
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git branch -a
  dev
* main
  remotes/origin/main
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git branch dev
fatal: a branch named 'dev' already exists
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git checkout de
v
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'dev'
A       index.html
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git branch test

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git checkout te
st
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'test'
A       index.html
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git switch dev
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'dev'
A       index.html
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git branch -d <
test>
At line:1 char:15
+ git branch -d <test>
+               ~
The '<' operator is reserved for future use.
    + CategoryInfo          : ParserError: (:) [], ParentContainsError
   RecordException
    + FullyQualifiedErrorId : RedirectionNotSupported

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git branch --delete <test>
At line:1 char:21
+ git branch --delete <test>
+                     ~
The '<' operator is reserved for future use.
    + CategoryInfo          : ParserError: (:) [], ParentContainsError
   RecordException
    + FullyQualifiedErrorId : RedirectionNotSupported

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git add --
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git add .
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git push   
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git push --set-upstream origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: This repository moved. Please use the new location:
remote:   https://github.com/Vinalil/Gym-Git-Exercise-Solutions.git        
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Vinalil/Gym-Git-Exercise-Solutions/pull/new/dev
remote:
To https://github.com/Vinalil/git-exercise.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git remote add origin https://github.com/Vinalil/Gym-Git-Exercise-Solutions.git
error: remote origin already exists.
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git push origin --delete test
error: unable to delete 'test': remote ref does not exist
error: failed to push some refs to 'https://github.com/Vinalil/git-exercise.git'
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash list    
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git add home.html
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   home.html
        new file:   index.html

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Saved working directory and index state WIP on dev: bb265a7  adding home page
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git list
git: 'list' is not a git command. See 'git --help'.

The most similar commands are
        bisect
        rev-list
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash list
stash@{0}: WIP on dev: bb265a7 adding home page
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git add about.html

hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Saved working directory and index state WIP on dev: bb265a7  adding home page
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash list
stash@{0}: WIP on dev: bb265a7 adding home page
stash@{1}: WIP on dev: bb265a7 adding home page
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig fhint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Saved working directory and index state WIP on dev: bb265a7  adding home page
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git list
git: 'list' is not a git command. See 'git --help'.

The most similar commands are
        bisect
        rev-list
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash list    
stash@{0}: WIP on dev: bb265a7 adding home page
stash@{1}: WIP on dev: bb265a7 adding home page
stash@{2}: WIP on dev: bb265a7 adding home page
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash pop stash@{1}
error: unknown switch `e'
usage: git stash pop [--index] [-q | --quiet] [<stash>]

    -q, --quiet           be quiet, only report errors
    --index               attempt to recreate the index

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash list
stash@{0}: WIP on dev: bb265a7 adding home page
stash@{1}: WIP on dev: bb265a7 adding home page
stash@{2}: WIP on dev: bb265a7 adding home page
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash pop [--stash@{1}]
error: unknown switch `e'
usage: git stash pop [--index] [-q | --quiet] [<stash>]

    -q, --quiet           be quiet, only report errors
    --index               attempt to recreate the index

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash pop --stash@{1}
error: unknown option `stash@'
usage: git stash pop [--index] [-q | --quiet] [<stash>]

    -q, --quiet           be quiet, only report errors
    --index               attempt to recreate the index

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash pop --stash@{1}
error: unknown option `stash@'
usage: git stash pop [--index] [-q | --quiet] [<stash>]

    -q, --quiet           be quiet, only report errors
    --index               attempt to recreate the index

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash pop 'sta
sh@{1}'
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (8e2968ee72401830da2f8e9157caf093144b9a63)
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash list
stash@{0}: WIP on dev: bb265a7 adding home page
stash@{1}: WIP on dev: bb265a7 adding home page
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash pop'stas
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash pop stash@{1}
error: unknown switch `e'
usage: git stash pop [--index] [-q | --quiet] [<stash>]

    -q, --quiet           be quiet, only report errors
    --index               attempt to recreate the index

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash pop '--stash@{1}'
error: unknown option `stash@{1}'
usage: git stash pop [--index] [-q | --quiet] [<stash>]

    -q, --quiet           be quiet, only report errors
    --index               attempt to recreate the index

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash pop ' stash@{1}'
error:  stash@{1} is not a valid reference
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash list
stash@{0}: WIP on dev: bb265a7 adding home page
stash@{1}: WIP on dev: bb265a7 adding home page
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash show
 team.html | 12 ++++++++++++
 1 file changed, 12 insertions(+)
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash list
stash@{0}: WIP on dev: bb265a7 adding home page
stash@{1}: WIP on dev: bb265a7 adding home page
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash pop 'stash@{1}'
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

Dropped stash@{1} (10036571f82f24acb28c7b384a128affca589fb8)
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git add --all
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        modified:   home.html
        new file:   index.html

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git commit -m " setup the about.html home.html and index.html"
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[dev 292c6c2]  setup the about.html home.html and index.html
 3 files changed, 26 insertions(+), 1 deletion(-)
 create mode 100644 about.html
 create mode 100644 index.html
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 720 bytes | 720.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote: This repository moved. Please use the new location:
remote:   https://github.com/Vinalil/Gym-Git-Exercise-Solutions.git
To https://github.com/Vinalil/git-exercise.git
   bb265a7..292c6c2  dev -> dev
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git remote add origin https://github.com/Vinalil/git-exercise.git
error: remote origin already exists.
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git remote set -https://github.com/Vinalil/git-exercise.git origin [https://github.com/Vinalil/Gym-Git-Exercise-Solutions.git]
error: unknown subcommand: `set'
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand

PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git remote set-url origin [https://github.com/Vinalil/Gym-Git-Exercise-Solutions.git]
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git push
fatal: protocol '[https' is not supported
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git remote -v
origin  [https://github.com/Vinalil/Gym-Git-Exercise-Solutions.git] (fetch)
origin  [https://github.com/Vinalil/Gym-Git-Exercise-Solutions.git] (push)
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash list
stash@{0}: WIP on dev: bb265a7 adding home page
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git stash pop 'stash@{0}'
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped stash@{0} (16b8ee53250105bd67dedffaed3e4030a278dcea)
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git reset --hard
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
HEAD is now at 292c6c2  setup the about.html home.html and index.html
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
PS C:\Users\Samantha\Dropbox\PC\Desktop\njongi exercise> 
...