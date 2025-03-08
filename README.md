# Upload Repository to Github from Scratch
## Introduction
Before diving into how to upload repository to github from scatch.

Two things you need to have **git** installed on your system and have a **github** account . If you don't have any of these click below and do these things first

 - [Download Git](https://git-scm.com/downloads)
 - [Signup on Github](https://github.com)

## Initialize Git 
First step isto initialize git to your file by using 

```
git init
```

## Staging our File
Second step to stage our file by following command

```
git add <file name>
```
If you want to add all file use this :

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
 - Go to [Github](https://github.com)
 - Create a repository on github by clicking on **+ option**. 
 - Click on **create new repository** give it a name and create it.
 - Copy the http link of repository.
  
## Linking repository
Next we need to link the remote repository we created to git by following command

```
git remote add origin <http link>
```
## Pushing to Github
Finally push to github using:

```
git push -u origin master
```
or if your branch is `master` :
```
git push -u origin main
 ```
And that's it! Your repository is now uploaded to GitHub. 🎉

