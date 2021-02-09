## Basic Terminal Commands

- pwd (path working directory)
- ls (list files in the current directory)
- cd (change-directory)
- . (a reference to the current directory, example `code .`)
- .. (a reference to the parent directory, example `cd ..`)
- mkdir (creates a new directory)
- touch (create files).
- rm (remove files), and if we add the `-rf` **flag** we can use it for directories.
- sudo <command> (gives the next command super user permissions)

## Discuss about Git

- git init
- git status
- git add
- git commit
- git log
- git diff
- git remote add origin (we are telling git where we want to send our commits to).
- git push origin <branch-name>
- git pull origin <branch-name>

.gitignore file:
Ignores files so they are not tracked by Git

### Branches

- git branch (list branches)
- git branch -m "some-name" (create a new branch called "some-name").
- git checkout <branch-name> (move to branch name).