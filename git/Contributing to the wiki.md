Before you contribute, please get familiar with [[git/Commands|git commands]].
# Set up `upstream`
In your `ESOL_wiki` directory run, `git remote add upstream https://github.com/nickmedwards/ESOL_wiki.git`.

# Reminder to `pull upstream main`
Before you make any changes to the wiki, pull upstream main. On your main branch run, `git pull upstream main`. This keeps your local wiki up to date. Pull main even when you aren't contributing.

# Contributing branch
Don't make your changes to your local main branch. Use that branch as a place to download the latest version of the wiki without conflicts. Make a branch that's called your name or something descriptive of whatever you are adding. Rebase your contribution branch after pulling.

# `push origin`
Once you've made your changes. Make sure that all new files are tracked and all changes are committed. Then push your contributing branch to origin.

# Pull request
On github, on your fork's contributing branch, click the `Contribute` then the `Open pull request` buttons. Once the pull request is approved, it will be pulled into main.