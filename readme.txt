mkdir -p git/learngit
cd git/learngit
git init
vi readme.txt
git add readme.txt
git commit -m "wrote a readme.txt"

git status
git diff
git diff readme.txt

git status
vi readme.txt
git add readme.txt
git commit -m "change again"

git reset --hard HEAD^

git log --pretty=oneline
git reset --hard HEAD^
vi readme.txt 
git log --pretty=oneline
git reset --hard 9de85
cat readme.txt 
git reflog

git diff HEAD -- readme.txt 查看工作区 和版本库里面最新版本的区别

git checkout -- readme.txt 丢掉未add的工作区内容

git reset HEAD readme.txt 删掉未commit的暂存区内容

git push origin master 把本地的最新修改推送至github
