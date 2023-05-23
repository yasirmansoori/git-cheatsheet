git init -> to initialize a repo
git status -> to check the status of all files present in repo
ls -lart -> shows all files in the directory with permissions
ls -> shows all files in the directory  
git add <filename.ext> -> stage the changes, not commit
git add -A -> stage the changes to all present files
touch <filename.ext> -> to create an empty file with extension given
git commit -> to commit the changes, but this command will open a vim editor, then first press i to insert the message then when you done adding the message just press the combination (ESC + : + wq)
git commit -m "enter the message" -> To commit all files with single command and single message use
git checkout <filename.ext> -> to revert back the file to last saved commit
git checkout -f -> to revert back all the files to last saved commit
git log -> to show all entries of commits, the press wq to exit
git log -p -5 -> this will show last 5 commits
git diff -> compare working directory to staging area
git diff --staged -> compare staging area to last commit
