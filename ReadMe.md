cd # Demo

Creating a Read Me file
Adding a new line!

## Operations/Commands:

git clone path: Clones the existing repo from github
cd folder: Change diretory to folder
ls -la: Shows the hidden files in a drectory
.git Folder: Holds all the files  that save changes recored in the history of that repo(including ones on github.com).[Blue=Folder]

git status: Shows all files updated/created/deleted but haven't been committed. Git first tracks the file and then saves it, so this command gives the status.

git add: Adds to files to git to be traked before saving it to git.
    git add . :Adds all files
    git add filename: Adds specific file

git commit -m "Title Message" -m"Description": Commit Changes

git push: Push it live to a remote repository like Github

git push origin master: Origin= Location of the fit repo, Master= Branch to push

-------------------------------------------------------------------
TO MAKE AN EXISTING PROJECT A GIT REPO

git init: Initialize git for the current project, adds .git folder and other imp stuff

git remote add origin <url>: Adds the new repo created, remote because it isn't present on the local device.

git remote -v: To check if the current repo is connected to the remote repo

Now we can do git push origin master, but as a shortcut, we need to create an upstream that indicated how to push it by default.
Eg: git push -u origin master
Now we can simply use git push