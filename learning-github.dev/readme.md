## Things to do using GitHub.Dev & Codespaces

## Cloning 
#### While learning GitHub Codespaces --there are three ways to clone
#### Creating a temp dir in our workspace of codespace instance
```sh
1 mkdir /workspace/test
2 cd /workspace/test
```
#### 1.  HTTPS

 ```sh 
 1 git clone https://github.com/learning-git-organization/github-foundations-prep.git
 2 cd github-foundations-prep
 ```

#### * Hidden Git Folder
There is a hidden `.git` folder which tells this project is a part of repo. To create new project create a new folder and initialize that repo using `git init`

#### * Creating New Project in codespace
```sh
1 mkdir /workspaces/new-project
2 cd new-project
3 git init
4 echo / nano / touch readme.md # add content in the readme file 
6 git add readme.md
5 git commit -a -m "docs: add initial readme file"
```

#### 2.  SSH
#### 3.  GitHub CLI

## Stage Commits

## Commits

## Branches

## Remotes

## Stashing

## Merging