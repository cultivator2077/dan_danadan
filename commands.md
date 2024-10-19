clear
mkdir git_tutorial
cd git_tutorial/
mkdir devops
git init
ls -a
clear
cd devops/
git init
clear
touch laila.txt
touch majnu.txt
ls -l
clear
git add .
clear
git status
git commit -m "feature: nothing"
git status
git log
sudo apt-get update
sudo apt-get install docker.io
clear
git status
cd git_tutorial/
ls
cd devops/
ls
clear
git status
touch file1.txt file2.txt file3.txt
git add .
git commit -m "resign"
git log --oneline
git branch
git checkout -b exp
git log --oneline
git status
vim feature.txt
git add .
git commit -m "added a feature"
git switch dev
git switch exp
git checkout -b staging
git branch
git status
git remote -v
git clone https://github.com/cultivator2077/devops_learning.git
cd devops_learning/
ls
touch solution.txt
git add .
git commit -m "added commands"
git push origin main
git status
vim local.txt
git add .
git commit -m "local"
git push origin main
tree
git checkout -b dev
git push origin dev
vim solution.txt
git add hi.txt
git commit -m "for day 39"
git log --oneline
git checkout master
git branch -a
git log --oneline
touch hello.txt
git add .
git commit -m "hello"
history > commands.txt

