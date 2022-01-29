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
