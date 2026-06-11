On windows, download git by clicking the "Click here to download" link on [this page](https://git-scm.com/install/windows).
On mac, download git by following the steps on [this page](https://git-scm.com/install/mac).
On linux, download git by running `apt-get install git`.

It is convention to have the main branch have the name main. In the installer, you'll come across a page like the following. Select the override option, and make it main.
![Git Installer|361](https://github.com/nickmedwards/ESOL_wiki/blob/main/images/README/default_branch_name.png?raw=true)

Or if git is already installed, by running `git config --global init.defaultBranch main`.

Vim is annoying, when installing you'll probably want to change the commit message editor to VSCode. In the installer, you'll come across a page like the following. Use the dropdown to select VSCode.
![Git Installer Editor|361](https://github.com/nickmedwards/ESOL_wiki/blob/main/images/README/default_editor.png?raw=true)

Or if git is already installed, by running `git config --global core.editor "code --wait"`.