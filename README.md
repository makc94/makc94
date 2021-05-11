1. $ git add .
# Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.

2. $ git commit -m "First commit"
# Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.

3. $ git remote add origin  <REMOTE_URL> 
# Sets the new remote.

4. $ git push origin main
# Pushes the changes in your local repository up to the remote repository you specified as the origin.
