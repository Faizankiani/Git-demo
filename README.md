# Upload Repository to Github from Scratch
## Introduction
Before diving into how to upload repository to github from scatch.

Two things you need to have **git** installed on your system and have a **github** account . If you don't have any of these click below and do these things first

 - [Git](https://git-scm.com/downloads)
 - [Github](https://github.com)

## Initializa Git 
First step isto initialize git to your file by using 

```
git init
```

## Staging our File
Second step to stage our file by following command

```
git add file name
```
or by using . which adds files

```
git add .
```

## Commiting 
Next we need to commit to ir local repository by following command

```
git commit -m "A descriptive message"
```
Till now we have commited our file to local repository but we need to upload it to github remote repository for this

## Create Repository on Github
 - Create a repository on github by clicking on **+ option**. 
 - Click on **create new repository** give it a name and create it.
 - Next copy the http link.
  
## Linking repository
Next we need to link the remote repository we created to git by folloeing command

```
git remote add origin link
```
## Pushing to Github
At last we need to push it github by following command

```
git push -u origin master
or 
git push -u origin main
 ```

