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


