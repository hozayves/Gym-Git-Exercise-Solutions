# Gym Git Solution

A collection of git exercises, which are made to help you get a better understanding of git.

## Bundle- 1
### Exercise-1
```sh
* Initialize git
    
    git init

* Rename your main branch from master to main

    git branch -m master main

* Make changes to the project (add files, rename them, or edit them)

    touch index.html

* Stage your changes and commit them

    git add .
    git commit -m "Initial commit"

* Create a GitHub repo and connect it with your project

    - Create repo in [https://github.com] 
    - git remote add origin https://github.com/hozayves/Gym-Git-Exercise-Solutions.git

* Push your changes to GitHub

    git push -u origin master

* Create a new branch dev

    git chechout -b dev

* From dev create another branch test

    git chechout -b test

* Go back to the dev branch and delete the test branch

    - git branch dev
    - git branch -d test
```
    