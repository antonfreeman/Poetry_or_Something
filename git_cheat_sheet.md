# An Introduction/Quick reference guide for git

# Setup git
Command: | Description
------------ | -------------
git config --global user.name <name> | Sets the name to be associated with your commits
git config --global user.email <email> | Sets the email  to be associated with your commits

# Create a New Repository
Command: | Description
------------ | -------------
git init <DIRECTORY> | Initialize new git repository in DIRECTORY
git clone <REPOSITORY> | Clone an existing repository to the current directory


# Working with a Local Repository
Command: | Description
------------ | -------------
git add <DIRECTORY> | Adds a directory to the staging area
git add <FILE> | Adds a file to the staging area
git commit -m "message" | Adds all files staged to the repository record
git commit <FILE> -m "message" | Adds only FILE to the repository record
git status | Shows all tracked and untracked files


# Working with Branches
Command: | Description
------------ | -------------
git branch | Lists all branches
git branch <NAME> | Creates a new branch called NAME
git checkout <NAME> | Switch head to any branch called NAME
git checkout -b <NAME> | Creates a new branch called NAME and switches head to NAME
git merge <NAME> | Merge NAME with the current branch (Might have conflicts)

# Working with a Remote Repository
Command: | Description
------------ | -------------
git pull <REMOTE> | Get a copy of all changes from remote repository
git pull <REMOTE> <BRANCH> | Get a copy of all changes from a branch in the remote repository
git push <REMOTE> <BRANCH> | Copy all local changes to branch in a remote repository

# Other Useful Commands
Command: | Description
------------ | -------------
git log | Shows all commit history
git diff | Show differences between current files and last commit
git revert <COMMIT> | Makes a new commit reversing changes in COMMIT

