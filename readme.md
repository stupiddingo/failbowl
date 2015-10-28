Commands Demonstrated
----------
*Adding and Commiting*
- `git status` What is going on?
- `git init` Initialize a new repo
- `git add <filename>` Add changed files to staging
  - `git add .` Add everything new and changed
  - `git add -A .` Add changed and deleted
- `git commit` Commit message  (if editor is vim use <esc> `:wq` to exit)
  - `git commit -m "My commit message."` Add message inline
- `git log`
  - `git log --decorate --graph` Add the lines connecting branches
  - `git log --oneline --graph --all --decorate` This matches the subway lines in GUI
  - `git diff` Show changes to the repo line by line
    - `git diff <folder/path/or/file>` Show only subpath or specific file diff

*Remotes*
- `git remote add <http or ssh address>` Add a remote
  - `git remote -v` Display possible remotes 
- `git push` Push local changes to remote
- `git pull` Pull down remote changes to local
- `git clone <http or ssh address>` Clone down a complete remote repo to local

*Branching*
- `git branch <mybranch>` Create a branch named mybranch
  - `git branch <mybranch> <commit>` Create a new branch from specific commit or tag
- `git checkout <mybranch>` Switch working branch to mybranch
- `git merge <mybranch>` Merge the contents of mybranch into your current branch (master perhaps)

*Management*
- `git tag <tagname>` Lightweight human readable label for a commit
  - `git tag <tagname> <commit>` Add a tag on a specific past commit 

*_Mentioned but not demonstrated_*
- `git checkout -b <mybranch>` Branch and checkout in one go.
- `git cherrypick <commit>` Adds a specific commit from one branch to working branch
- `git revert <commit>` Removes a specific commit
- `git reset` Resets a file to a past state, use with care
  - `git reset --hard <commit>` Reset local to previous commit (accepts commit id, tag or HEAD^^ where each caret is minus one commit.)
- `.gitignore` Not a command but a file in any folder that lists files to ignore from repo.


Resources
--------
Try Git 
(Light red text is not native git, but the tutorial, if you do same changes locally it might make more sense)
https://try.github.io 

Atlassian Tutorial
https://www.atlassian.com/git/tutorials/

Git for Ages 4 and Up
Michael Schwern
Explaining git with tinker toys
https://www.youtube.com/watch?v=1ffBJ4sVUb4

Seven Bridges of Königsberg and Graph Theory
Sam Livingston-Gray
http://think-like-a-git.net/

The Thing about Git
Ryan Tomayko
http://2ndscale.com/rtomayko/2008/the-thing-about-git

How the Internet will (one day) transform government
Clay Shirky
http://www.ted.com/talks/clay_shirky_how_the_internet_will_one_day_transform_government
http://blog.ted.com/further-reading-in-github/

Open Source World
NPR Ted Radio Hour
http://www.npr.org/programs/ted-radio-hour/449179937/open-source-world

Tools
------
Git for Windows (prev. mysysgit)
https://git-for-windows.github.io/  (this is what Brent uses)

GitHub for Desktop
https://desktop.github.com/  (this is what Ben and Pam use)

Git Extensions
https://gitextensions.github.io/

IdahoFishGame Repo
https://github.com/idahofishgame

