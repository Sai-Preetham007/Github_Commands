$ Git Bash Download :
---------------------
Website Link : https://git-scm.com/install/



$ Configure Git :
-----------------
git config --global user.name "Sai Preetham"
git config --global user.email "saipreethamudumula@gmail.com"
<!-- git config --global core.editor "notepad" -->
git config --list



$ Git Initialization & Tracking :
---------------------------------
git init
git add read.txt
git commit -m "Welcome Message"



$ Git Branch:
-------------
git branch feature-branch main              ---> Creates a new branch from the main/master branch.
git checkout feature-branch                 ---> Switches to new branch i.e feature-branch.
git checkout -b feauture-branch-copy        ---> Create and Switch to that new branch.



$ Merge the changes to Main/Master branch :
--------------------------------------------
git checkout main
git merge feature-branch



$ Github Connection & Upload:
-----------------------------
git remote add origin "https://github.com/....."
git push -u origin main



$ Git Restore:
--------------
git restore example.txt                     ---> Undo the changes from the local/Working, If you haven't used git add command.
git restore --staged example.txt            ---> Undo the changes from the staging area, If you have done git add command.



$ Git Reset:
------------
git reset --soft HEAD~1                     ---> Undo the commit, keep changes staged
git reset --mixed HEAD~1                    ---> Undo the commit, keep changes but unstaged
git reset --hard HEAD~1                     ---> Discard changes, revert fully



$ Other Features :
------------------
git                  ---> Show all the git commands.
git log              ---> Show the info related to changes, who has done and when it is done.
git branch           ---> Show all the available branches.
git remote -v        ---> Show the details of remote location.
git fetch            ---> Shows weather Git & Github are in sync.
git pull             ---> Github -> Local
git push             ---> Local -> Github