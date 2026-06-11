
# Commands

## add
Add files to git current commit. 
Usually used with `-A` ie, `git add -A`. This option adds all tracked and untracked files to commit.
To add specific files, use a space separated list ie, `git add .\foo.md .\directory\bar.md`.
## commit
Close current commit, start next commit. 
Usually 
## push
## pull
## rebase
## checkout
## switch


# Install `git`
On windows, download git by clicking the "Click here to download" link on [this page](https://git-scm.com/install/windows).
On mac, download git by following the steps on [this page](https://git-scm.com/install/mac).
On linux, download git by running `apt-get install git`.

It is convention to have the main branch have the name main. In the installer, you'll come across a page like the following. Select the override option, and make it main.
![Git Installer|361](https://github.com/nickmedwards/ESOL_wiki/blob/main/images/README/default_branch_name.png?raw=true)

Or if git is already installed, by running `git config --global init.defaultBranch main`.



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