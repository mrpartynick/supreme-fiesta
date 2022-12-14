# Manual Instruction for main Git commands (lecture 1)

## 1. First opening

After creating folder (repository), Git should be initialised.

Firts command: Git init - commencing Git operations in repository.

Extra commands should be applied in case of first opening of Git
* *User name*: git config --global user.name "your mame"
* *User mail address*: git config --global user.email "<адрес_почты@email.com>"

Another command for checking current status of files numbers and changes in repository:

Repository status: git status

For save all changes on MacOS combination of buttons command+S should be used quite often. 

## 2. Add changes and save versions

Add saved info: git add .

To make comment of new add info after each save, should be used next command: git commit -m "comment"

**Important conclusion** : main using proccess of Git programm consist of 3 command combinations: 
* git status
* git add .
* git commit -m ""

# 3. Commands for version checkout

* To check last version of repository: git checkout master
* To check all verions: git log
* To check difference of master version and chosed version: git diff

# Manual Instruction for main Git commands (lecture 2)

# 4.  Main commands for branches

* git branch - showing current list of all available branches
* git branch *name* - create new branch from current branch line
* clear - will replace all commands on terminal and show clear space

# 5.  Main commands for switching between branches

* git checkout master - will always return to initial master branch (so called "clear version")
* git branch - open adjusted list of branches again
* git checkout name - swith to required branch from list of branches
* git branch -d *name* - delete chosed branch
* git log - show last saved modifications (commits) on branch 

# 6. Merge function, images, structure tree

* git merge - combine last changes on current branch. If used on master branch - it will add all last changes to Master file on these branch
* ! [text for image in case of loading error] (image directory from repository folder)  
* .gitignore - saving file to separate ignore list
* git log --graph - open the structure tree of branches

# 7. Approximate cycle

Use approximate combination for complete cycle:

1. git branch
2. git branch name
3. git log
4. git checkout name
5. git merge
6. git branch -d name

# Manual Instruction for main Git commands (lecture 3)

# 8. Remote repository funcitons

1. git push - command to send local repository to GitHub remote service for user. Repository will be forward from local computer to outdoor cite for futher remote operations (including teamwork possibility).

2. git pull - opposite command, alowing to get required remote repository to your local computer.

# 9. GitHub main integrated functions

1. Fork - separate button on screen to get choosed public reository and save a copy to your local computer. After save, we can adjust these repository by our own needs.

2. In case we'd like to propose our version of adjusted repository to original owner of repo, we can use function pull request.

 -------------------------  Manual End ---------------------