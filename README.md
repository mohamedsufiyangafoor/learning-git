# learning-git
# This repo is used to learn git and github

comment - git rm --cached <file name>
meaning - to remove a file from staging

comment - git rm -r --cached .
meaning - to remove all files from staging from current directory	

comment - git add -A
meaning - to ADD all files and folders for staging from current directory (including the folders nested file)	

comment - git log
meaning - shows the commit we have made (returns the commit hashes)


example:
-------
commit 8afaa3db85c34e234f5943a02a70375ddf793089 (HEAD -> master)
Author: Mohamed Sufiyan Gafoor <mohamedsufiyangafoor@gmail.com>
Date:   Wed Jun 8 08:04:37 2022 +0530

    style message

commit d7aa1828e9c15ba8e4044d1cee8af7e277f5780c
Author: Mohamed Sufiyan Gafoor <mohamedsufiyangafoor@gmail.com>
Date:   Tue Jun 7 23:16:14 2022 +0530

    changes20

commit 84d86255afd34a6a4569427574ecacb0f24bab8e
Author: Mohamed Sufiyan Gafoor <mohamedsufiyangafoor@gmail.com>
Date:   Tue Jun 7 22:59:44 2022 +0530

    Initial Commit




comment - git show <Hash of the commit>
meaning - show the changes of the before commit file and current commit file

comment - git diff
meaning - show the exact line changes in the code file

comment - git restore <file name>
meaning - restore the file code with last staged code syntax

comment - git commit --amend -m "message we want to change"
meaning - change the last commit message name as we want

comment - git remote add origin https://github.com/mohamedsufiyangafoor/learning-git.git
meaning - tell your local machine which remote server (git repository) we are goin to add this project

comment - git branch
meaning - to get the branches we have

comment - git branch -M main
meaning - to create a new branch and change the current to that branch


comment - git push -u origin main
meaning - to push the files from  local repository to the remote repository	(only for initial push we need -u origin main) 

comment - git push
meaning - to push the files from  local repository to the remote repository








