---
layout: post
title: Commonly used Unix commands
date: 07-06-2023 14:35:26 :z
tags: [tools]
description:
summary:
comments: false
author: Yong Huang
mathjax: false
render_with_liquid: true
---

Here are some commanly used commands for unix-based system terminals. 


### Files and directories

1. **cd dirname** --- go to a specific directory.
    1. **.** is current directory
    2. **..** is the parent directory, for example, **cd ..** means go to the parent directory of where I am currently at.

2. **pwd** --- tells you where you currently are, this returns the absolute path.
3. **ls** --- Listing files in current directory
    1. **ls -a** --- listing all files including hidden files, many files are by default hidden such as .gitignore file in a git repo.

4. **mv filename1 filename2 --- moves a file** -- moves a file, rename it or move it to a different directory.
5. **cp filename1 filename2** --- copies a file.

6. **mkdir dirname** --- creates a new directory in current directory

7. **rm filename** --- delete a file.
    1. **rm -r dirname** --- recursively delete everything in a directory


### Connect to remote computer and files uploading
1. **ssh** ---
2. **scp** --- 
3. **rsync** ---


### Other commands

1. **top**
2. **kill**
3. **whoami**
4. **du**
5. **quota**

### Git related

1. **git add** --- stage changes in your code
2. **git commit -m "some commit message"** --- commit changes to your code
3. **git push origin branch-name** --- push changes to remote repo
4. **git clone repo-link** --- clone remote repo to local 
5. **git checkout -b branch-name** --- checkout to a specific branch, if no such branch exists, this will create a new branch.
6. **git fetch** --- fetch updates from remote repo





