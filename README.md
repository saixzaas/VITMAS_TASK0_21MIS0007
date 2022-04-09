git config <br />
  Helps to set configuration options for your Git installation
  
git init <br />
  To start a new repository

git clone <br />
  To obtain a repository from an existing URL.

git add <br />
  To add a file to staging area

git commit <br />
  To record or snapshot the file permanently in the version history.

git commit --amend <br />
  To amend the most recent commit.
  
git diff   <br />
  Shows the file differences which are not yet staged.

git diff –staged  <br />
 Shows the differences between the files in the staging area and the latest version present.

git diff [first branch] [second branch] <br />  
  Shows the differences between the two branches mentioned.

git reset [file]   <br />
  Unstages the file, but it preserves the file contents.

git reset [commit]   <br />
  Undoes all the commits after the specified commit and preserves the changes locally.

git reset –hard [commit]   <br />
  Discards all history and goes back to the specified commit.
  
git status <br />
  To list all the files that have to be committed.

git rm <br />
  To delete the file from your working directory and stages the deletion.

git log <br />
  To list the version history for the current branch.

git log –follow[file] <br />
  To list the version history for a file, including the renaming of files also.
  
git show <br />
  To show the metadata and content changes of the specified commit.
  
git tag <br />
  To give tags to the specified commit.

git branch <br />
  Lists all the local branches in the current repository.

git branch [branch name] <br />
  Creats a new branch name
  
git branch -d [branch name] <br />
  Delets the branch 

git checkout <br />
  To switch from one branch to another.

git merge <br />
  Merges the specified branch’s history into the current branch.

git remote <br />
  To connect your local repository to the remote server.

git push [variable name] master  <br /> 
  Sends the committed changes of master branch to your remote repository.
  
git push [variable name] [branch] <br />
  Sends the branch commits to your remote repository.
  
git push –all [variable name]   <br />
  Pushes all branches to your remote repository.
 
git push [variable name] :[branch name] <br />
  Deletes a branch on your remote repository.
  
git pull <br />
  Fetches and merges changes on the remote server to your working directory.

git stash save   <br />
  This command temporarily stores all the modified tracked files.

git stash pop   <br />
  This command restores the most recently stashed files.

git stash list   <br />
  This command lists all stashed changesets.

git stash drop   <br />
  This command discards the most recently stashed changeset.
