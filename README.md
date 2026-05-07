Terminal Commands
mkdir
ls
cd



SSH Commands
mkdir -p ~/.ssh 
ssh-keyscan -t rsa github.com >> ~/.ssh/known_hosts

Git Setup Commands
git init
git clone git@github.com:jarbunn/git_training_repo.git
git remote add origin git@github.com:jarbunn/git_training_repo.git
git pull main

Git Branch Commands
git checkout develop
git checkout -b my_branch
git add <file_name>
git add .
git commit -m "Some Message"
git push -u origin my_branch
git push --set-upstream origin my_branch

Git Rebase Commands
git checkout develop
git pull
git checkout my_branch
git pull --rebase origin develop
git rebase --continue
git rebase --abort

Other Commands
git log
git log --oneline


Topics
Basic Terminal Commands
SSH vs HTTPS
Cloning vs Remote add
Understanding Commits
Current vs Incoming
Copy Branch
Squash Commits
VS Code Extensions


