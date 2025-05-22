git --version
git config --global user.name 'name'
git config --global user.email 'email'
git config --global init.defaultBranch main
git status
git add readme.md
git add .
git commit
git checkout [hash]
git branch -M main
git remote add origin https://github.com/rasheedarm/git_project.git
git push -u origin main
git branch branch-name
git checkout -b feature-branch
git branch new-branch-name source-branch
git push -u origin feature-branch
git pull

## workflow:
1- clone the repository
2- create a new branch from the main or another branch
3- make your changes
4- push the branch to the remote repository
5- open a pull request
6- merge the changes
7- pull the merged changes into your local main branch