## add
Add files to git current commit. 
Usually used with `-A` ie, `git add -A`. This option adds all tracked and untracked files to commit.
To add specific files, use a space separated list ie, `git add .\foo.md .\directory\bar.md`.
## commit
Close current commit, start next commit. 
Usually run with `-a` and `-m` ie, `git commit -a -m "quick description"`.
`-a` adds all files tracked by git to the commit.
`-m` allows you to write the commit message in the terminal.
## push
Try to apply the commits from the current branch to another.
Usually run with a remote, making this command upload the changes to a remote repo ie, `git push origin contributing`.
## pull
Try to apply the commits from another branch to the current one.
Usually run with a remote, making this command download the changes from a remote repo ie, `git push upstream main`.
## rebase
## checkout
## switch
## remote


PS C:\Users\nmedwards2\ESOL_wiki> git init
Initialized empty Git repository in C:/Users/nmedwards2/ESOL_wiki/.git/
PS C:\Users\nmedwards2\ESOL_wiki> git add -A
warning: in the working copy of '.obsidian/core-plugins.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.obsidian/graph.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.obsidian/workspace.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Visual Studio.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Welcome.md', LF will be replaced by CRLF the next time Git touches it
PS C:\Users\nmedwards2\ESOL_wiki> git commit -a -m "init commit for esol wiki"
[main (root-commit) 26b4a28] init commit for esol wiki
 8 files changed, 300 insertions(+)
 create mode 100644 .obsidian/app.json
 create mode 100644 .obsidian/appearance.json
 create mode 100644 .obsidian/core-plugins.json
 create mode 100644 .obsidian/graph.json
 create mode 100644 .obsidian/workspace.json
 create mode 100644 Visual Studio.md
 create mode 100644 Welcome.md
 create mode 100644 create a link.md
PS C:\Users\nmedwards2\ESOL_wiki> git branch
* main
PS C:\Users\nmedwards2\ESOL_wiki> git remote add origin https://github.com/nickmedwards/ESOL_wiki.git
PS C:\Users\nmedwards2\ESOL_wiki> git push origin main