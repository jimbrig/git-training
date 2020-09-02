# Git Training Materials

Various resources and workflows related to teaching others about Git and Version Control

## Notes: 

### Local Workflow:

- git init: put Git in this folder so that it keeps track of changes to files in this folder and subfolders 
- Working Directory: the directory you’re writing code in 
- Staging Area: files are in the staging area if the changes in them will be included in the next save point 
- Repository: everything Git is keeping track of 
- git status: show me which files have been changed and which ones are ready to be committed 
- git add filename.txt: include the changes to this file in the next commit 
- git commit -m “commit message”: wrap up all these changes and save them together with a short description of the changes
- git log: show a history of all commits
- git diff: show what is different from the last commit line by line
- git diff 234nod: show what is different between the commit 234nod and current state, line by line

### Remote Repository

- git remote add origin address-of-remote: make address-of-remote a new place to put my code and call it “origin”
- git push -u origin master: push my code to the location origin points to, on the master branch, and also in the future I will pull code from this same location
- Upstream: where I will pull code from in the future
- Origin: where I put backups or share my code
- git pull: grab code from another repository
- git fetch: grab code from another repository
- git push: save my history and changes in another location
- Fork: I want a GitHub repo that looks like someone else’s repo
- Pull Request: I made some changes that I would like you to include in your repository, please accept them
- git clone: give me the code at this location

### Branching

- git branch: what are all my branches? or what are all the names of the different versions of my code?
- git branch feature: make a new branch/version of my code with the name feature
- git checkout feature: move to that branch/version of my code so I can make changes to that branch/version of my code
- master: the name of the branch which should be the official, working, well documented, version of my code
- git merge: combine the history of two branches so I can have the changes from both in one place
- Merge Conflict: Git does not know how to combine two histories and needs human assistance

### More Advanced Concepts 

> Would not teach these early on in the process.

- HEAD
- git rebase
- git rm filename.txt
- git mv filename.txt otherfile.txt
- git rebase
- git cherry-pick
- git bisect
- git amend
- git reflog
- git blame


## Tips

- Have trainees install Git and make a GitHub/Bitbucket account ahead of time to save time. 
- Anticipate Windows users and be prepared for the strange ways in which Git bash works differently. 
- Partner students up so there are fewer different machines to worry about. Make sure the partners have the same operating system so that they do not learn Git in an environment   they will never use again. 
- If you are teaching an individual, give them a project to work on so they can use Git in context. It is harder to pick a project that would work for a group of people, and it     will be hard to monitor all of them, of course. But if you can use a project, especially for teaching a single person, the process is a lot easier. 

## Don’t forget

- Build a context for your student before teaching commands by explaining the problem Git solves, drawing pictures, and using metaphors. 
- When you teach the commands, try and explain them without using the name of the command in the explanation. 
- Be choosey about what to teach right now and what they can learn later.
