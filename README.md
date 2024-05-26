# guidefor-git
different command for git github
git clone <link> --- will clone reposetries in local device 
git status  --- will give status of of our git repo is ther any changes or not 

cd-- change directory 
ls-- list file in directory 


to see hideen file 

ls -a

git add <file name> -- will add or modifed the file if git
git add . -- will add all the file 

To commit the changes (legal records)

git commit -m" some message"

To show or upload the changes in git hub:

git push origin main

git init-- will make the the file as git file.
git remote add origin <-link-> -- we want to add new remote repo and name its as origin

git remote -v :-- is used to verify the which remote we are talking about 

git branch 

git branch -M main (to chnage the branch name to name )


Branch command :

git branch (will let you know where you are)
git branch -M main (rename branch)
git checkout <- branch name->  (to navigate from one branch to another branch)

git checkout -b <-new branch name-> (to create new branch)

to delete any branches :
if you are in same branch and try to delte that branch then yoou cannot able to delete it 
git branch -d <name of branch>




now you can push this local repository to main usnig git push origin main


to merge two branches:

way 1
git diff <-branch name-> (to compare commits ,branch files and more)


PULL command:
 used to featch and download contenct from a remote repo and immediatelty update the local repo
 to match the content
< git pull origin main>

to reset your add

git reset 

git reset HEAD~1 

git log( will show show the hash of all previous commit)

to go multiple commit back

git reset <hash of commit>
