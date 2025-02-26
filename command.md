mkdir Git_For_Devops
ls
cd /Git_For_Devops/
ls
pwd

git init
git --v
git --version

sudo yum update -y
sudo yum install git -y

git --version
git init

touch hello.txt
ls
touch suraj.txt
touch xyz.txt
ls

git add suraj.txt
git add xyz.txt
git status

git commite -m "adding both"
git commit -m "adding both"

git config --global user.name "Surajmatere"
git config --global user.email "materesuraj8@gmail.com"

vim suraj.txt
git status
git add suraj.txt
git status
git commit -m "V2"

git restore suraj.txt
vi suraj.txt
git status
git add hello.txt
git status
git commit -m "hello"

git status
git log
git status
git checkout -b dev
git status

ls
touch ganesh.txt
git status
git add .
git commit -m "added new Member"
git status

git checkout master
git status
git log
git checkout dev
git log
git log oneline
git log --oneline

history
