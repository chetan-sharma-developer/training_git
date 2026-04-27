- git clone \<git-url\>: cloning the repo from git
- cd \<project-name\>: after cloning git creates a folder with the project name and we would be able to use git commands within the project folder only so requires to get into that project folder from terminal.
- git status: To check/track the changes made
- git add <>
  - git add \<file-name\>
  - git add \<file1\> \<file2\> \<file3\>
  - git add . : It's to add all the files which has changes would automatically added to stage.
- git commit -m "msg"
- git pull: It fetches all the changes available on the repo(recommended to always do this before git push)
- git push: uploads the committed changes to repo


## Session 2
- README.md
- LICENCE
- UI workflow
- reverting the commited
  - git reset --soft HEAD~1
- branches
- stash