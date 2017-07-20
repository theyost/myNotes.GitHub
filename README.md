git clone <url>
- makes a copy of a repository
- stores it on your computer
- a "fork" creates your own copy of someone else's repository

git add
- adds a file to "staging area"
- tells git to include the file in the next revision to the repository
- get add * adds all changed files
... changes to be committed

git diff
- show all changes changes (shown in green)

git add swap.c
- adds 'swap.c' as a file that git should track

git commit -m "message
- "message" is some message describing why changes
- saves the changes to repository as a new revision (a 'commit')
- records a message
- git commit -am "message" adds and commits in same step

git status
- shows current status of repository

git push
- sends committed changes to remote repository
- more explicitly, could write git push original master (rare)

git pull
- retrieves changes from remote repository

MERGE CONFLICTS
- when two different commits can't be automatically merged
- needs to be resolved (by programmer)

git log
- shows a history of commits and messages

git reset
- git reset --hard <commit hash>
  reverts code back to a prevous commit
- git reset --hard origin/master
  reverts code back to remote repository version
  
BRANCHING
- branch is a version of the repository
- each branch has its own commit history and current version

get branch
- shows all branches of code
- create a branch with git branch <branch_name>
- switch to ("checkout") a new branch with 'git checkout <branch_name>'
- 'git checkout -b <new branch_name>' .. create a new branch & move to

git branch tests
git merge test marges

git merge
- git merge <branch_name> merges the branch_name with current branch

git branch -D <branch_name>
- delete a branch

PULL REQUESTS
- ask repository owner to approve changes

Git
- Keeps track of changes to code
- Synchronizes code between different people
- Test changes to code without losing the original
- Revert back to old versions of code

Git and GitHub
CS50 Seminar
Brian Yu









