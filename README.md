# Skillschule Git_lesson_101  
## Training to introduce the cohort how to push from local environment to Github  
- Download Gitbash (https://git-scm.com/downloads)
## Configure Gitbash  
- Git config --global user.name “username”
- Git config –-global user.name “email addess”
## Prepare the configured environment  
- mkdir directory(website)
- cd into website
- git init (Initialise the git in the directory)
- touch index.html (create a text file)
## Clone a Github repo  
- Create a Github repo
- git remote add origin <url> (this should be the url from your created repo-use https)
## Push from local to remote repo (GitHub)  
- git status (To check Git status as regards staging area)
- git add index.html
- git commit -m "create index.html" (to take a snaoshot of a file)
- git push origin master
