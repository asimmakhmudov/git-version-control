

|**#**|**Document name / number / date:**|Workshop|||
| :-: | :-: | :-: | :- | :- |



|**DOCUMENT RULES:**|
| :-: |
|**Task Number / Name:**|`     `**Task /**|
|**Task name & column name should be written:**|**Bold (CTRL+B)**|
|**Commands should be written in the after # sign:**|*Italic (CTRL+I) #hostname*|
|<p>**Output photo should be cropped or compressed:**</p><p>**Photo could be more than one:**</p><p>**If you need extra lines, add the line next after it:**</p>|<p>***Description photo should be with title bar (CTRL + I + B)***</p><p>![](Aspose.Words.1331dde0-3e22-46eb-be43-1720989b8cce.001.png)</p>|
|**All other text should be written:**|Standard|
|**Font name and text size:**|Calibri and 9|
|**Group name:**|Dev\_ops|
|**Student name and surname:** |Asim Mahmudov|
|**E-mail:**|asimmahmudov18@gmail.com|
|**WhatsApp number:**|+994 50 996 2442|


|**#**|**Task names**|**Command steps and outputs**|
| :-: | :-: | :-: |
||<p></p><p>**Firstly, get all updates on your OS**</p><p></p>|*#sudo apt-get update*|
||<p></p><p>**Install git to your system**</p><p></p>|*#sudo apt-get install git-all*|
||<p></p><p>**Check the version of git. To make sure that git is successfully installed on the system**</p><p></p>|*#git --version*|
||<p></p><p>**Set you github account username**</p><p></p>|*#git config --global user.name “your account username”*|
||<p></p><p>**Set you github account email address**</p><p></p>|*#git config --global user.email “your account email”*|
||<p></p><p>**Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.** </p><p></p><p>**Because of this if you don’t want every time you clone, or push git don’t ask for username and password. We create this file. If you didn’t do this every time you push or clone you must write your github access-token when git ask for password.**  </p><p></p>|*#sudo touch ~/.netrc*|
||<p></p><p>**Enter created file**</p><p></p>|*#sudo* *nano ~/.netrc*|
||<p></p><p>**Write this information inside the file**</p><p>**In addition press for save [ctrl+o], for exit [ctrl+x]**</p><p></p>|<p>*#machine github.com*</p><p>*#login username*</p><p>*#password access-token*</p>|
||<p></p><p>**Enter etc directory**</p><p></p>|*#cd etc/*|
||<p></p><p>**Create local repo folder**</p><p></p>|*#sudo mkdir firstrepo*|
||<p></p><p>**Enter firstrepo directory**</p><p></p>|*#cd firstrepo/*|
||<p></p><p>**INFO – according to ChatGPT**</p><p>**“git init” is a command that initializes a new Git repository. It is used when you want to start tracking changes in a new directory or when you want to convert an existing project into a Git repository.**</p><p></p>|*#sudo git init*|
||<p></p><p>**Create file any file what you want it may be index.html or txt file**</p><p></p>|*#sudo touch mynotebook.txt*|
||<p></p><p>**Check status of repo. As a result, we can see file is created but changes didn't add. Its color is red.**</p><p></p>|*#git status*|
||<p></p><p>**Add changes for specific file use** </p><p>**[git add name of file], for add all changes we use [git add .]**</p><p></p>|*#sudo git add mynotebook.txt*|
||<p></p><p>**Check status of repo. As a result, we can see all changes added. Its color is green.**</p><p></p>|*#git status*|
||<p></p><p>**This command to create a new commit. -m is for specific message for your commit.**</p><p></p>|*#sudo git commit -m “first file uploaded”*|
||<p></p><p>**Check status of repo. As a result, we can see**</p><p>**[nothing to commit, working tree clean]**</p><p></p>|*#git status*|
||<p></p><p></p><p>**Get your created repo link and run with this command**</p><p></p><p></p><p></p>|*#sudo git remote add origin your-github-repo-link*|
||<p></p><p>**INFO – according to ChatGPT**</p><p>**git branch -M master is a command used in Git to rename the current branch to "master". This command is typically used when you are working with an existing Git repository and want to rename the default branch from its previous name (e.g. "main", "develop", etc.) to "master".**</p><p></p><p>**The -M option is used to force Git to rename the branch, even if the new name already exists as a branch in the repository. This can be useful if you want to rename the branch and override any existing branches with the same name.**</p><p></p><p>**In addition, there is no functional difference between master and main branch**</p><p></p>|*#sudo git branch -M master*|
||<p></p><p>**INFO – according to ChatGPT**</p><p>**The -u flag is used to set the upstream branch for the current branch. This means that Git will remember which branch on the remote repository corresponds to the local branch that you are currently working on and will use this information for future push and pull operations.**</p><p></p><p>**The origin argument specifies the name of the remote repository that you want to push your changes to. "Origin" is a common name for the remote repository that you cloned the local repository from, but you can use any name you want for the remote repository.**</p><p></p><p>**The master argument specifies the name of the branch that you want to push your changes to. In this case, you are pushing changes to the "master" branch of the remote repository.**</p><p></p>|*#sudo git push -u origin master*|


1

