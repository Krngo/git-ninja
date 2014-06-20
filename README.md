git-ninja
=========

git / githun practice

Git/GitHub Basics
------------------------------------
######time 2014-06-13 15:00

src: video tutorial https://www.youtube.com/watch?v=U8GBXvdmHT4 [50:00]


##Objectives
- setup git
- use git
- use github


Setup
-------
setup was easy 

    sudo apt-get install git

Basics commands
------
get git version

    git --version

git init <project-name>, this creates a folder with project name and setups a .git folder

    git init

cd into folder

    cd project-name
    
create a file

    touch file.html

to add files to repo 

    git add <file-name>
    
or to add all

    git add .
    
or 

    git add -A

    
to see status

    git status
    
to commit to local repo

    git commit -m "message"
    
to add a remote repo on github
    
    git remote add origin https:github.com/Krngo/git-gitgub-ninja
    
to push up to remote repo

    git push -u origin master
    
to pull down from remote repo

    git pull

:frog:
