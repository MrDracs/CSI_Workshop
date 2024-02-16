# Workshop for CSI Members
In this workshop you will learn:

## 1. Basics
- What is Git, Github and version control
- Why is it used/needed
- How to install git  
  - Remember to use `git config --global user.name “[firstname lastname]”` & `git config --global user.email “[email]”`
- Some basic cmd commands  
   - ls (list), cls (clear screen), mkdir (make directory), dir (show directories), cd (change directory), d (delete), rm (remove)
- GitHub Accounts and Repositories
- How to make a repository (3 Ways)  
   1. using github on site
   2. using github desktop
   3. using cmd

## 2. Working with Git (Locally on Terminal)
- Initializing a Git Repo (2 Ways)
    1. Navigating to your project folder in the terminal & entering `git init`
    2. Cloning a pre-made Repo using `git clone`
- Making the first change
- checking the status of project
    - `git status`
- What is staging and how to?  
    - `git add`
- Committing changes  
    - `git commit -m [message]`
- Understanding commit history (logs)
    - `git log`
- removing a commit from history (stashing)
    - `git reset [commit hash]`
    - `git stash` & `git stash pop`

## 3. Remote Repos
- Remote repository connecting (2 ways)
    1. Using Github (Cloning)
    2. Using Git locally (cmd)
- What are Branches
- creating new branch
    - `git branch [branch name]`
- switching between branches
    - `git checkout [branch name]`
- merging to main
    - `git merge [branch name]` while checkout on main branch
- push to master
    - `git push origin main`
- pull from main (Fetch)
    1. Using GitHub site to update repo
    2. Using Github Desktop to update local
    3. Using `git pull origin main` command
 
## 4. Working on Projects
- working with existing project
- how to fork and why
- making fork branch and pull requests
- what is pull request
- not making pull request directly on main
- merging PRs
- merge conflicts

