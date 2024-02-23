# This is Zero Master GitHub Command
`git status`

`git add README.md`

`git add addfile_and_staging.txt`

`git add read.txt`

`git status`

`git commit -m "The Git Commands"`

`git status`

`git push orgigin master`

`git status`

# What do we have here?
- check the git status
- adding file from untracked -> staging
- `commit` to staged the file whit message
- push the file(s) to repository

# More information at Release Branch
- We have to `push` in order to reveal the new created branch on Repository
- This new branch (Release) is a copy of the main branch last update
- To change branch type command : `git branch <the_branch_name>`
- Create new file(s) and add as usual and type : `git commit -m "message of yours"`
- To push to the Release branch type : `git push origin Release`

# More information at Commits Branch
Command typed: 
- `git branch Commits`
- `git checkout Commits`
- `git push origin Commits`

The result is a new branch `Commits` append to Repository

And this Commits branch have all the components in the Release branch `A copy of Release Branch`

`Cause Commits branch was create while working in the Release branch` so this is the result

- `git tag -a f.10.59 -m "Testing tag one at Commits"`
- `git push --tag`
This two line above is about tag. When push a tag, Git auto create a .zip and .gz file store all the components in the current working branch `Commits`

