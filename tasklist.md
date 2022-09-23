# Git setup and configurations
## First time setups
- Initialize git repository (git init)
- Setup git with git config
    - git config --global user.name ""
    - git config --global user.email ""

## Starting with git
- Create a folder
- create a file
- `git init`
- add a file in tracking `git add <file>`
- commit file changes `git commit -m "commit message"`
- add remote with `git remote add <alias; e.g. origin> <remote address; e.g. git@github.com:razainaequo/git-workshop.git>`
- remove remote with `git remote <alias; e.g. origin>` 


## Contribute to other's repo

- create a branch with your name `git branch <branch-name>`
- checkout that branch `git checkout <branch-name>`
- add a folder with your name `mkdir folder`
- add a file inside that folder with your name `touch file.txt (Linux) | type nul > file.txt (Windows)`
- add your name inside that file
- commit that change `git commit -m "feat: add name"`
- push that change `git push <remote-name; e.g. origin> <branch-name; e.g. feature-name>`
- create a PR **(Pull request)**