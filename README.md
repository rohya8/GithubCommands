### Introduction
Useful Github Commands for development.

- Git is a distributed version-control system for tracking changes in source code during software development.
- It is designed for coordinating work among programmers, but it can be used to track changes in any set of files.

#### Commands

+ git config => sets the author name and email address respectively to be used with your commits
    ```sh
    $ git config –global user.name “<name>”
    $ git config –global user.email “<email-address>”
    ```
    
+ git init  =>  turns a directory into an empty Git repository
    ```sh
    $ git init
    ```    
    
+ git add  => Adds files in the to the staging area for git
  There are different ways to use git add 
    - To add a single file
     ```sh
     $ git add <file>
     ```   
     - To add everything at once
     ```sh
     $ git add -A / git add .
     ``` 
     
+ git commit => is like setting a checkpoint in the development process with a short message to explain what you have developed or changed in the source code
    ```sh
    $ git commit -m "message"
    ```
     ` [` git commit saves your changes only locally `] `    
     
+ git remote add => connects your local repository to the remote server
    ```sh
    $ git remote add <variable name> <remote server link>
    ```
    
+ git push => sends the committed changes to your remote repository
    ```sh
    $ git push <remote> <branch-name>
    ```
    ` [` git push only uploads changes that are committed `] `  
    
+ git pull => fetches and merges changes on the remote server to your working directory
    ```sh
    $ git pull <repository-link>
    ```    
    
+ git status => lists all the files that have to be committed
    ```sh
    $ git status
    ```  
    
+ git diff => shows the file differences which are not yet staged
    ```sh
    $ git diff
    ```  
    
+ git checkout => mostly used for switching from one branch to another. We can also use it for checking out files and commits
    ```sh
    $ git checkout <name-of-your-branch>
    ```
    - To create and switch to a branch at the same time
    ```sh
    $ git checkout -b <name-of-your-branch>
    ```
    ` [` -b stands for branch `] `    

+ git log => lists the version history for the current branch
    ```sh
    $ git log
    ```
    - for detailed changes 
    ```sh
    $ git log --summary
    ```    
    
#### Reference Links

* [Git Handbook]
* [DZone]


[Git Handbook]: https://guides.github.com/introduction/git-handbook/
[DZone]: https://dzone.com/articles/top-20-git-commands-with-examples

**if you want to contribute to the project,create a pull request**
