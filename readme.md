first line

mkdir dom2
cd dom2
git init
 

touch readme.md
git add readme.md
git commit -m "first step"
git log --all



5
git brance first_brance
git checkuot first_brance
git add readme.md
git commit -m "step 1 first_brance"

git checkuot master
git add readme.md
git commit -m "step 2 master"

git merge first_brance
git add readme.md
git commit -m "step 3 master"
log --oneline --graph --decorate=short --all

