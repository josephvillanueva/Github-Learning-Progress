# Github Learning Progress
Github Tutorial 2020 (https://www.youtube.com/watch?v=iv8rSLsi1xo)
  - Creating Github account and installing Github Desktop

Git & Github Tutorial for Beginners (https://www.youtube.com/watch?v=3RjQznt-8kE&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR)
  - Git is the creating a version that is re-traceable
  - Github is an onlin eservice to host projects
  - Github makes codes shareable and downloadable
  - Installed Atom (atom.io) to continue with the lessons
  - Installed cmder (https://cmder.net/) command line interface for windows (comes with Git)
  - Learned how to make a file and edit using Atom
  - Created and removed directory (folder) files
  - repo = repositories = containers for projects
  - repo > repository project
  - .git only tracks fropm where it is -> inwards
  - Commit - save
  - initialize git (git init)
  - get the status (git status)
  - move files from .git to staging
  - removing files from staging
  - adding all files (git add .)
  - to commit a file to staging (git commit -m "<description>")
  - adding commits must be descriptive in nature to track what you did
  - get complete logs (git log)
  - get shortcut logs (git long --oneline)
  - Three types of undoing (checkout commit, rever commit, and reset commit)
  - Checkout commit - SHOW code at a certain point in time \
  - git checkout <one liner code>
  - detach from the master branch to SHOW a commit
  - git checkout master
  - retach to the master branch
  - Revert commit - undo a recent commit
  - git revert <one liner code>
  - takes you to text editor if you want to add an additional comment (:wq) 
  - shows 'revert' in your git log --oneline
  - Reset commit - take you at a certain commit. Deletes all other commits up to the point
  - git reset <one line code> (has not yet deleted it completely)
  - git reset <one line code> --hard (deleted everythign else compeltely
  - Branches
  - Master Branch - stable
  - Feature Branch - copying stable code to work on it and test things out
  - merge feature branch to the master branch if everything is okay
  - create a new branch (git branch <name of the branch>
  - get list of all branches (git branch -a)
  - to delete a merged branch (git branch -d <branch name>)
  - to delete a non-merged branch (git branch -D <branch name>)
  - making a branch and checking it out (git checkout -b <branch name>)
  - merging branch files to the master branch (git merge <branch name>)
  - fix conflicts
  - Explanation of Github
  - Create a Github first then clone to your computer/local machine
  - created a public repo on my account named (Git & GitHub Tutorial for Beginners)
  - pushing the tutorial repository to the remote repo (git push <URL to push> <what branch to push>)
  - shortening the git repository you are trying to push to (git remote add <alias> <URL to push>)
  - cloning a repository (git clone <url>)
  - getting alias (git remote -v)
  - getting the updated list (git checkout <branch>)
  - pulling the updated list (git pull <alias> <branch>)
  - creating a new branch from the master branch (git checkout -b <branch name>)
