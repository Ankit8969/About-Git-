# About-Git


## Instead of using VS code terminal you can use ***git bash*** terminal it gives you more feature
  - ***git init*** it is used to initialize the file
  - ***ls -lart*** it show you all the file which present in that file
  - ***git status*** it give you the details about the file which are tracked or untracked

![Screenshot (126)](https://user-images.githubusercontent.com/47697582/151650791-b666269c-ed9e-474f-8dd0-caf4d0ab8fd4.png)

  - ***git add index.html*** it add the index.html file but
  - If I write ***git add .*** it add the all the file
  - If the color of the file is red it means it don't add yet. but if it show greed it means it add 
  - In gitbash ***git commit*** it open a new editor then press ***capital I *** to write something 
  - for exit press ***esc :wq***
  - ***touch ankit.html*** it create a new empty file in your project
  - you can also write like this ***git commit -m "First Commit"*** 

## Very Usefull Command
- ***git checkout index.html***    this command put all the data of you previous commited value in the index.html
- ***git checkout -f***           It match my all the files from the last commited git
- ***git log***                   It gives you all the details about your all the commit you done on your project
- ***git diff***   
```
Suppose you already commit you project and after commiting you make some 
changes and then you want to check the diff b/w the last commit and the last change
in that case you can used git diff command
```
  - ***git diff --staged*** it compare with your last commit

## you can also use all the linux command feature in your windows in bash terminal



## Don't commit you project unnecessay, first confirm it is fine then commmit
- ***git log -p -2***   it gives you the details of your last 2 commit  ***press 'q' for exit***


## Git Remove Command
  - ***git rm --cached waster.html*** it remove the waster.html from the commit
  - ***git rm waster.html*** it delete this file and also remove from the working tree
  - ***git rm -f waster.html*** it delete this file forcely

## .gitignore file
  - create using ***touch .gitignore*** 
  - .gitignore file avoid to push all the files which are written in the .gitignore file
  ```
  node modules
  ```
## for creating new branch you can use the command 
```
git branch feature1
```
## ***git branch*** it gives you the list of all the branch

- generally we are always on master branch
- but IF I want to swith to other branch 
```
git checkout feature1
```
## Git merge Command
  - First of all you remeber our main branch is our master branch
  - Suppose you create a new branch 
  ```
  git branch feature2
  ```
  - If you are working on any project which is very big and very important then try to change on the branch
  - If you have done all the changes in your branch and you want to merge then 
  - first you have to go in the master branch
  ```
  git checkout master
  ```
  - then write
  ```
  git merge feature2
  ```
  
## IF you create any new branch from master 
- in that branch you can do any thing like crating new file , updting something in the existing file 
- but after making all the changes 
- don't forget to commit

### One more interesting command
- this command done It create a new branch and directly move me to in that branch
```
git checkout -b feature5
```

## Few more commands
```
git remote add origin 'https://kjfdkfjdf'
git remote
git remote -v
git push origin master
```







































