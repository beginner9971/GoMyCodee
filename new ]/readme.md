 ## basic git commands

 ## git init - To initialize a repository or to satert tracking all files in a folder

 ## git status - gives you the status of your repository

 ## git add - will tell git what files to track

 ## git add . - track all files in the repo

 ## git rm  - this will remove a file from being tracked and deledte the file

 ## git rm --cached [file_name] - this will remove a file from being tracked but the file will still be on your system

 ## git commit -m 'first commit' - this creates a commit i.e. a snapshot of a particulaar version of your code
 
 <!-- Once you have staged your files, you can commit them into Git. Imagine a commit command as a snapshot at a certain point and time where you can return back to access your repository at that stage. You assign a commit message to every commit, which you cna pass with the -m prefix. -->

 A - Added/Tracked: A file which has been previously staged or committed.
 U - Untracked: a file which has not beeen staged or committed.
 Ignored - A file which g=Git has been explicitly told to ignore.
 M - Modified.

 <!-- Configure git -->
 git config --global user.name "YOUR NAME"
 git config --global user.email "YOUR EMAIL"