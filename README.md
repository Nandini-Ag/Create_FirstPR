# Create_First Pull Request

STEP 1
Fork THIS repository by clicking on the fork button on the top of this page. This will create a copy of this repository in your account.

STEP 2
Now clone the forked repo to your machine. Go to your GitHub account, open the forked repo, click on the clone button

STEP 3
Open a terminal/git bash and run the following git command:

git clone "<paste the link here>"
  
  
 STEP 4
Change to the repository directory on your computer (if you are not already there):

cd First-Pull-Request
Now create a branch using the git branch command and change to new branch using git checkout command: (Replace 'branch-name' with any name of your choice)
  git branch <branch-name> 
git checkout <branch-name>
  
 STEP 5
 Add upstream to the repo
  git remote add upstream <original repo link>
  
  STEP 6
  Do the addition or changes you wish to do to the cloned repo and then run
  git add .
  
  STEP 7
Now commit those changes using the git commit command:
git commit -m "give your commit message here"
  
  STEP 8
  git push origin <branch name>
  
  STEP 9
  Create a pull request from your forked repo and wohoo you are done!
