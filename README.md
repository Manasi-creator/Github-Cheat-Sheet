Git and GitHub Cheat Sheet
A concise guide to essential Git commands and workflows for version control. 

1. Initial Setup and Configuration
Configure your identity and customize your workflow with aliases.


Initialize Git: git init — Sets up Git in the current folder. 


Set Username: git config --global user.name "Your Name" 


Set Email: git config --global user.email "your@email.com" 


Set Aliases: git config --global alias.<aliasName> "<command>" — Create shortcuts (e.g., git config --global alias.cm "commit -m"). 

2. Staging and Committing
Manage changes and save versions of your progress.


Check Status: git status — View changes made since the last version. 


Stage Specific File: git add <filename> 


Stage Everything: git add . 


Commit with Message: git commit -m "your message" 


Amend Last Commit: git commit --amend -m "new message" — Updates the previous commit instead of creating a new one. 


Ignore Files: Use a .gitignore file to list files or folders Git should ignore. 

3. Viewing History
Navigate through your project's timeline.


Basic Log: git log — Shows version history (excluding unnamed branches). 


Full History: git log --all — Shows every previous version. 


Visual History: git log --all --graph — Displays the branching structure visually. 


Exit Log: Press q to close the log view. 

4. Undoing and Reverting
Correct mistakes by resetting or discarding changes.


Unstage Specific File: git reset <filename> — Reverses git add. 


Unstage All: git reset . 


Discard Changes (File): git checkout -- <filename> — Reverts a file to its last committed state. 


Discard All Changes: git checkout -- . 


Switch to Version: git checkout <commitHash> — Move the HEAD to a specific previous version. 


Switch Branch: git checkout <branchName> 


Remove Git: rm -rf .git — Completely removes Git tracking from the folder. 

5. IDE Integration (VS Code)

Staging Area: Represents git add .; it tracks specific changes rather than just files. 


Changes View: Displays the specific modifications within your files.