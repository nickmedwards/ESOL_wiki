Welcome to the ESOL wiki! This wiki is run using git and Obsidian.md. Please follow the ESOL wiki install steps to use the wiki. 
# ESOL Wiki Install Steps

### 0. Use the terminal
Please follow these steps in your terminal as practice. On windows, use "Windows PowerShell". On mac/linux, use "Terminal".
## git

### 1. Install `git`
On windows, download git by clicking the "Click here to download" link on [this page](https://git-scm.com/install/windows).
On mac, download git by following the steps on [this page](https://git-scm.com/install/mac).
On linux, download git by running `apt-get install git`.

It is convention to have the main branch have the name main. In the installer, you'll come across a page like the following. Select the override option, and make it main.
![Git Installer Branch Name|361](https://github.com/nickmedwards/ESOL_wiki/blob/main/images/README/default_branch_name.png?raw=true)

Or if git is already installed, by running `git config --global init.defaultBranch main`.

Vim is annoying, when installing you'll probably want to change the commit message editor to VSCode. In the installer, you'll come across a page like the following. Use the dropdown to select VSCode.
![Git Installer Editor|361](https://github.com/nickmedwards/ESOL_wiki/blob/main/images/README/default_editor.png?raw=true)

Or if git is already installed, by running `git config --global core.editor "code --wait"`.

Rebasing gives you more control than merging. In the windows installer, make all pull commands default to rebase in the following window by selecting `Rebase`.
![Git Installer Pull Behavior|361](https://github.com/nickmedwards/ESOL_wiki/blob/main/images/README/default_pull.png?raw=true)

Or if git is already installed, by running `git config --global pull.rebase true`.
### 2. Create a fork
This step will make more sense in hindsight. At the top of this page, click `Fork`. On the page, leave everything as default and click `Create fork`.  
### 3. Clone your fork
On windows, create or navigate to your `\source\repos\` directory.
To navigate run, `cd ~\source\repos`.
To create run the following
1. `cd ~`
2. `mkdir source\repos`
3. `cd .\source\repos\`
Once in your `source\repos\` directory run, `git clone https://github.com/your_github_username/ESOL_wiki.git`.

### 4. Create an upstream repo
Again, this will make more sense in hindsight, run, `git remote add upstream https://github.com/nickmedwards/ESOL_wiki.git`.
## Obsidian.md
### 5. Install Obsidian.md
Install Obsidian for your OS by following the link on [this page](https://obsidian.md/download).
### 6. Open the ESOL_wiki directory as a vault
If you have no vaults connected, you'll be presented with the following window:
![Vault Manager|394](https://github.com/nickmedwards/ESOL_wiki/blob/main/images/README/vault_manager.png?raw=true)

Click the `Open` button in the "Open folder as vault" option.

If you already have vaults connected, you can open that window by clicking the vault menu at the bottom left of the Obsidian side bar.

To see the contents of the wiki go to main.base file.