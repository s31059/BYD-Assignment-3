# BYD-Assignment-3
This is a repository for the Assignment #3 (BYT, Nov. 2023)

Git 
On the school computers I suggest use of the Cmder console emulator (http://cmder.app/) in full version – it includes, among others, Git. Unzip the archive to chosen folder and run cmder.exe 

Part one – work with local repository 

Create folder 
Inititate it as local repository 
Create a text file in it (it can be a piece of code) 
Add it to traced files 
Commit 
 a. Note – vim or vi will be the default commit message editor. In vim after typing the commit message press escape :wq enter to quit the editor 
 b. Note – you can commit with -m switch instead, put the commit message in quotes after the switch 
Create and add a second file 
Commit 
Create a new branch 
Introduce changes to one of the files, add, commit 
Switch to the new branch 
Introduce different changes to the same file (preferably conflicting ones), add, commit 
Come back to the master branch 
Merge the two branches 
Solve conflicts 
Add file with solved conflicts to the repository 
Commit 
 

Part two – work with remote repository 

Create an account on github.com if you don’t have one 
Ask the tutor for access to repository – provide him with account name 
Clone the following repository:  https://github.com/AbdulM0/BYT4.git
Create a file with the following name: sXXXX.html (put your student id instead of XXXX), add content to it  
Add the new file to tracked files 
Modify the list.html file by adding href element with link to your file, described by your first and last name 
Add the modified file 
Try to submit changes to server 
 a. You may have to run the following command: git config --global push.default matching  
If necessary, fetch the latest updates, merge, submit changes once again (some coordination in your group may be necessary)  
Submitting the first part – send log (git log --stat >> log.txt) 
