# GitGitHub
<br>
Git Configurations
<br>
<br>
1. To Remove the Account from the system
<br>
<br>
         Unset userName
 <br>
   -  git config --global --unset user.name
 <br>
         Unset userEmail
<br>
   -  git config --global --unset user.email
<br>
         Unset Creds
<br>
  -  git config --global --unset credential.helper
<br>
<br>
2. To permanently delete git from system
<br>
<br>
  -  cmdkey /delete:LegacyGeneric:target=git:https://github.com
  <br>
  <br>
3. To add new git account on system 
<br>
<br>
     Set userName
     <br>
  -   git config --global user.name "ByteBusters09"

<br>
Set userEmail
<br>
 -   git config --global user.email "xyz@gmail.com"
<br>
<br>
4. To permanently store password of github on system 
<br>
<br>
-  git config  credential.helper store
<br>
<br>
5 . To check the configurations
<br>
<br>
-  git config --list
<br>
[This will list out all the account with username and user email]
<br>
<br>
6. git config is used for the configuration of the git , and configurations can be done by two methods - 
   <br>
   . --global   [means globally on a system]
   <br>
   . --local    [means for a particular project we are using a diffrent account]
   <br>
<br>
7 . git clone
<br>
   -to copy the git project on local 
<br>
<br>
8 . Two types of locations 
<br>
   . local [laptop or pc]
<br>
   . remote [ github ]
<br>
<br>
9 . git status  - this command is used to display the state of code, whether any file is changed or not
<br>
    Generally, when we are using git status, we can find four types of status
<br>
   . Untracked files - these are the file that are added on local, but not yet tracked by git [ new files]
   <br>
   . Modified - these are the files which are already tracked by git, and its been modified/changed [ added some change in it] now
   <br>
   . Staged - the files that are ready to be commited
   <br>
   . Unmodified  - these are the files that are not modified
   <br>
<br>
10. git add .   -this command is used to add the changes that are done on files [to add all files we use this command]. Adding a file makes it staged.
<br>
<br>
11. git add <fileName> - this command is use to add single file at a time.
<br>
<br>
12 . ls -a  - this command is used to list down all the files including hidden files
<br>
<br>
13 .  git commit -m "message"    - this command is used to save the changes or takes the screenshots preceded by a message, that what actual change was done in the file
<br>
<br>
14. git push   - this command is use to push all the changes to remote, once added and commited. or simply this command is used to upload local repo content to remote repo
<br>
<br>
15.  git push origin main - this command is used when we have only one branch that is main ,here origin is a repository on github which we have cloned and started working.
<br>
<br>


