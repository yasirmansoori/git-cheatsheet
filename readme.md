git init -> to initialize a repo
git status -> to check the status of all files present in repo
git status -s -> to check the summarized status of all files present in repo
ls -lart -> shows all files in the directory with permissions
ls -> shows all files in the directory  
git add <filename.ext> -> stage the changes, not commit
git add -A -> stage the changes to all present files
touch <filename.ext> -> to create an empty file with extension given
git commit -> to commit the changes, but this command will open a vim editor, then first press i to insert the message then when you done adding the message just press the combination (ESC + : + wq)
git commit -m "enter the message" -> To commit all files with single command and single message 
git commit -a -m "message" -> to commit all files skipping staging area
git checkout <filename.ext> -> to revert back the file to last saved commit
git checkout -f -> to revert back all the files to last saved commit
git log -> to show all entries of commits, the press wq to exit
git log -p -5 -> this will show last 5 commits
git diff -> compare working directory to staging area
git diff --staged -> compare staging area to last commit
git rm <filename.ext> -> to remove a file directly from the directory
git rm --cached <filename.ext> -> to remove a file directly from the directory and send it to untrack position  
git rm -f -> to delete forcefully a file from staged area and whatsoever
git branch -> to show all branches
git branch <branch name> -> to create a new branch by given name 
git checkout <branch name> -> to switch to that branch 
git checkout -b <branch name> -> to create and switch to the branch with name given   
git merge <branch name> -> make sure you first have to be onto master branch
git remote add origin <url which you have to copy from repository  on github> -> this is used to add local repository to remote 
git remote -> to check the repository linked to your local named as origin by default 
git remote -v -> to check the url of fetch and push 
git push origin master -> push origin to master branch 
git push -u origin master -> use this command so that after every push you just have to write git push  
git push -> to push files to the remote repository