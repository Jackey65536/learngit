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

add something

