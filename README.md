
just an intro practice for my git colloboration 

``````````````````````````````````````````````````````````````````

sudo apt install git   ======> for installing package 
sudo apt remove git     ======> for removing package



git config --global user.name "<name>"    ======> give username of git for configuration
git config --global user.email "<email>"    ====> give email used for git for configuration 
git config --global color.ui auto   ============> configuration for color format in command line
git config -l    ===============================> to view configurations that you have done till now 



== from git ==> command line ::
``````````````````````````````````
git clone <link of repository from the github>  ===========>  to download repository from github to command line 
git remote -v   ===========================================>  to see the remote repositories downloaded till now 



== from terminal ==> git (3 steps) :: 
````````````````````````````````````````
1) cd <required folder>    ==================================================> folder which has need to connect with git
2) git init   ==============================================================>  to intialise the folder to git
2) git remote add origin <fileNameWithExtension / pathOfTheFile> ===========>  to connect a project from command line to git


cd <git repository folder path>   =============>  for start doing changes in repository 
git add <filepath>    =========================>  for adding the changes of files to staging area
git commit -m "<msg>"   =======================> to commit a file 
git diff    ===================================> viewing the changes made to files ready for commit2, *changes in files before addding staging area
git diff --staged   ===========================> viewing the changes made to files ready for commit2 , *changes in files after addding staging area
git status    =================================> for viewing the status of untracked files, trackedfiles, modified files, commits
git log   =====================================> list all commits

**final step 
```````````````
git push -u origin master   ==================> to publish all the commits to github repository



