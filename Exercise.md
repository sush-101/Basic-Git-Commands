Install the git in your computer . Url : git-scm.com

To check whether git is installed or not :
1.Open command prompt / terminal
2. Type git

Working of git:
1.Create a folder named "FirstRepo"(any name) at a location which you would make it as a repository 
2. To make this folder utilise version control mechanism :
   i. Open cmd. Navigate to this folder. Type **git init**.(initialization of this folder as repo)
3. Once made this as a repository (master).. 
4. Add files to this "FirstRepo" and folders with files
5. Type **gti status** 
  you get *On branch master
  Untracked files:
  (use "git add <file>..." to include in what will be committed)
        fourth.html
        second.html
        third.html

   nothing added to commit but untracked files present (use "git add" to track)*
  
6. We need to stage all the files and folders in the "FirstRepo" using command **git add .**
7. To get the status of currect repository we use **git status**
8. When you type **git status** at this point of time after adding all those files and folders you get 
    *On branch master
     Changes to be committed: 
    (use "git restore --staged <file>..." to unstage)
        new file:   second repo/test.html*
9. We need to commit files (here we are commiting all the files at once which creates single log id for this commit. You can add files 
   one by one and then commit which gives then separate log ids)
10. To commit **git commit -m "message"
11. Make changes to a file(or any number of files)
12. Types **git status**
13. You get *On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   file names

no changes added to commit (use "git add" and/or "git commit -a")*
14. Type **git add .** to stage
15. To commit **git commit -m "message" **
16. This creates new log id(or log ids if changes are made at once)
17. To roll back to a particular commit **git checkout <log id> <filename>**
18. This automatically stages and you need to commit once you work with this.
19. Now if you want to reset this (discard this version) and roll back to last version before this you were dealing , you need to first
    unstage this .
20. To do so **git reset HEAD <file name>**
21. As now this is unstaged, you can go to the last commit you have made on this file **git checkout -- <filename>**
Conclusion: 
a. Learnt how to make a repository
b. Commit files
c. Roll back to any point
d. Roll back to the last commit ever made
e. Status of the repository

    
    
