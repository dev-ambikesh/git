
# Git Tutorial By Ambikesh

In this section we're going to learn about every commnad of git and it's working flows.
I'm going to describe every command and how it works in simple language.

## Installation

Install git on your local machine

```bash
  cd my-project-name
  git init
```
    
## Git commnads

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install on linux

```bash
  sudo apt-get install git-all
```
check git version

```bash
  $ git --version
```
Add file to the staging area
```bash
  $ git add .
  $ git add -A
```
Lists all the files that have to be committed.
 ```bash
    git status
```
Git commit the changes.
```bash
    git commit -m “[ Type in the commit message]”
```
Add git remote url
```bash
    git remote add < remotename : origin > https://your-repo-link.
```
Configure url email and name.
```bash
    git config --global user.name <ambikesh>
    git config --global user.email <dev.ambikesh@gmail.com>
```
Check git current branch or all branches.
```bash
    git branch
```
Swtich to an other branch
```bash
    git checkout [branch name] 
```
Create a new branch
```bash
    git branch <new-branch-name>
```
List the version history for the current branch
```bash
    git log
    git log –follow[file]
```
Shows the file differences which are not yet staged
```bash
    git diff
```
Shows the differences between the files in the staging area and the latest version present
```bash
    git diff –staged
```
Unstages the file, but it preserves the file contents
```bash
    git reset [file] 
```
Undoes all the commits after the specified commit and preserves the changes locally
```bash
    git reset [commit]
```
Discards all history and goes back to the specified commit.
```bash
    git reset –hard [commit]
```
Deletes the file from your working directory and stages the deletion
```bash
    git rm [file]
```
Shows the metadata and content changes of the specified commit.
```bash
    git show [commit]
```
Give tags to the specified commit.
```bash
    git tag [commitID]
```
Deletes the feature branch.
```bash
    git branch -d [branch name]
```
Merges the specified branch’s history into the current branch
```bash
    git merge [branch name]
```
Connect your local repository to the remote server
```bash
    git remote add [variable name] [Remote Server Link]
```
Sends the committed changes of master branch to your remote repository
```bash
    git push [variable name] master
```
Pushes all branches to your remote repository
```bash
    git push –all [variable name]
```
Deletes a branch on your remote repository.
```bash
    git push [variable name] :[branch name]
```
Fetches and merges changes on the remote server to your working directory
```bash
    git pull [Repository Link]
```
Temporarily stores all the modified tracked files
```bash
    git stash save
```
Restores the most recently stashed files
```bash
    git stash pop
```
Lists all stashed changesets
```bash
    git stash list
```
Discards the most recently stashed changeset
```bash
    git stash drop
```
## Git Documentation

[GitHub Docs](https://docs.github.com/en)


## Authors

- [@ambikesh](https://www.github.com/dev-ambikesh)

