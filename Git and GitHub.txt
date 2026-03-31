Git and GitHub 

*git init - setup git in folder

*git status - changes after previous version 

*git add filename.extension / folder - specific file to make changes

*git add . - everything in the folder

*git commit -m  "___" - add msg to the commit

*git config --global user.name "Name" - set name explicitly

*git config --global user.email "Email" - set email explicitly

*git log - shows version history 
(does not show unnamed branches)

*git log --all - shows all previous versions

*git log --all --graph - shows branching effect of git 
(useful when we go to specific version of commit and update it)

*q - closes git log

*git add . 
 git commit -m "___" --amend - amends changes in the previous commit and doesn't make a new commit

*git reset filename.extension / foldername - to undo git add filename.extension / folder

*git reset . - undo git add .

*git checkout -- filename.extension / folder - discard changes in that file / folder

*git checkout -- . - discards changes overall

*git checkout <commitHash> - to go back to previous version of the code 
(commitHash is generated after we create a commit. git log shows versions only uptil previous version where we headed)

*git checkout <branchName> - to go to specific branch 
(used instead of commitHash) 

*git config --global alias.<aliasName> "<aliasStandsFor>" 
(used to set alias / shortcut for any command
eg. git config --global alias.cm "commit -M"
git cm "___" will easily run)

*.gitignore - to ignore files listed in it

*rm -rf .git - removes git from the git initialised folder

VS Code - 

*Staging area - git add . - tracks changes and not files
*Chnages - shows changes in the file