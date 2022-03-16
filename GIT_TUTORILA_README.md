# gitTutDemo
Git tutorial Demo

git init
git status
git add firstfile.txt
or git add .
git commit -m "my first commit"
git restore --staged amit.txt   ---> unstage from staged area
git log
git rm -f file1.txt  --> to delete file
git reset 9066962f11a1c529cb127d6de3de192e65165453    ----> to go previous commit
git stash    ---> to hide or backed stage some currently working file in staged area
git stash pop  ---> to bring back from backstage
git stash clear  ---> to delete from backstage area
===========================================================================================================================
Git HUB: 

git remote add origin url-repo
git remote add origin https://github.com/Amitpatels/GIT-TUTORIAL
git remote -v   --> to check current project attached remote url
===========================================================================================================================
git BRANCH: 

git branch feature
git checkout feature
git merge feature
===========================================================================================================================
git undo commit: 

git reset zsdajdsfskdfiasnfhakfnas  ---> commit hash from commit log
git add .
git stash    ----> to make it background reset commit changes 
git push origin amit -f    ---> -f to force push  
===========================================================================================================================

how to cherry-pick single selected commit:
1. copy your commit hash code by using git log:
2. Then checkout on which branch you want to commit:
cmd:
git cherry-pick a6081e36cdf650e5df94650d11f5d6e0ba41da1e
3. git push origin branchName
4. done 
