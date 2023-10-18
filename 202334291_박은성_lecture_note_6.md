# Git config:First time setup  
#### Git configurations are stored in three levels:  
##### System level:--system option.Affects all uses and repositories on the system (administrative)  
file:/etc/gitconfig  
##### Global (user) level:--global option.Affects all repositories of a current user  
file:~/.config/git/config  
##### Local level:--local option.Specific to the current repository  
file: .git/gitconfig  
```
$ git config --global user.name "Name"  
$ git config --global user.email email-address@gachon.ac.kr  
$ git config --global init.defaultBranch main  
```  
---
 ## $git init  
#### Initializing a Repository in an Exsiting Directory  
 ## $git status  
#### Checking Repository Status  
 ## $git add [file_name]  
#### Adding a new file to be staged (tracked)  
 ## $git add.  
 #### Adding all files to be staged (tracked)  
 ## $git rm --cached [file_name]  
 #### Unstaging a file  
 ## $git commit -m "commit message"  
 #### Commit
 
