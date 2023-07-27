# Learn-Git 2023

## Git commands training - 2023

### git status

- displays the state of the working directory and the staging area.

### git add filename or \* for all files

- adds a change in the working directory to the staging area.

### git reset head filename

- unstage files

### git commit -m "message"

- Commit changes to the local repo

### git branch

- List all branches in the local repo

### git remote -v

- Check if there any connection with online repos and show them if any

### git push remote_repo_name branch_name

- Publish local commits to the remote repo

### git clone repo_url

- Get clone from the remote repo into your local pc

### git pull origin or remote name

- fetch new changes on the remote and merge them with the local repo

### git config --list or git config --l

- list all configuration of git

### git help config

- Manual of all configurations

### git config --global user.name

- Get user name of the global config

### git config --global user.email

- Get user email of the global config

### git config --global user.name "name here"

- set user name of the global config

### git config --global user.email "email here"

- set user email of the global config

### git config -l --show-origin

- Display from where git get configurations

### git config --global --unset user.name

- Remove user name , value = ""

### git config --global --edit

- Edit configurations using editor

### git init

- initialize an empty repo

### git remote add origin url

- make a connection with the remote repo

### git push -u origin main

- pull last changes then push if there is no conflict

### git config --global alias.st status

- Make st alias for status command

### git config --global alias.st 

- to know which command related to this alias

### git config --global alias.cm "commit -m"

- Make cm alias for commit -m command

### git config --global --edit

- will found alias and can edit it through editor

> Some Global Alias

1- git config --global alias.p 'push'

2- git config --global alias.st 'status'

3- git config --global alias.cm 'commit -m'

4- git config --global alias.rv 'remote -v'

### git branch 

- Display all branches 

### git branch new

- create branch called new

### git checkout new

- switch to the new branch

### git branch -d new => Safe delete

- delete the branch after checking if there is edits or not  

### git branch -D new => Force delete

- delete the branch even there is edits

### git checkout -b new_branch

- Create a new branch called new_branch and go to it

### git branch -m newname

- rename the current branch

### git merge branch_name

- merge the branch_name with the master branch (current)


### git stash => every stash have unique id

- save file (hide)

### git stash list

### git stash pop 

- drop saved file (last one) and delete the stash

### git stash save "message"

- save stash with message

### git stash apply

- rop saved file (last one) and doesn't delete the stash

### git pop stash@{1}

- drop a specific stash not the last one

### git stash drop 

- delete the last stash

### git stash show 

- display what is inside a stash (last one)

### git stash clear

- delete all stashes 

### git restore --staged file_name or *

- remove the file from stagging area

### git clean -n 

- display files to be removed 

### git clean -f

- remove files 

### reset 

- remove commits

### head 

- pointer that points to the last commit 

### git reset --hard #hash

- remove all commits after that hash 

### git push origin main --force 

- update the remote repo 

### touch .gitignore
### code .gitignore

- *.log => any file with extension .log ignore it

- !vip.log => except this

- py_packs/ => ignore any folder called py_packs

- text.txt => specific file

- git add text.txt -f => add it by force 

> search about git ignore patterns 

### git tag

- display available tags 

light weight tag => take it's message from commit

### git tag v1.0

- create tag v1.0

### git push origin v1.0

- push the tag to remote 

### git -a tag v2.0 -m "annotated tag"

### git tag -l "v1.*"

- list all tags of v1

### git tag -d v1.0

- delete v1.0 locally 

### git push origin --delete v1.0

- delete v1.0 remote


### References 

- https://git-scm.com/docs/git-add

- https://support.nesi.org.nz/hc/en-gb/articles/360001508515-Git-Reference-Sheet




