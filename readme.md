gitbash:

-> mkdir learning-git
-> cd learning-git/
ls
// for brand new project we  use git init. 
// but for exisitng project we dont use git init
-> git init .
-> ls -a

-> touch index.html
-> touch index.js
-> touch main.css
-> ls
-> index.html  index.js  main.css

//  move untracked file to staging
-> git status
-> git add index.html

// remove tracked file from staging to untracked
-> git rm --cached index.html
-> git status

// add all the files from current directory downwards
-> git add .
-> git status

// remove all the files from current directory downwards
-> git rm --cached .
-> git rm -r --cached .

