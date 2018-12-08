### Learning how to use git

**What is Git?**
- it is a system that records changes to our files over time
- we can recall specific versions of those filesat any given time
- many people can easily collaborate on a project 
- and have their own version of a project file on their computer

**Why use git?**
- store revision in a project history in just one directory
- rewind to any revision in a project you wanted to
- work on new features without messing up the main codebase
- easily collaborate with other programmers

**What is Github?**
- online service the hosts our project
- share our code with other developer
- developer can download the projects and work on them
- they can reload their edits and merge them with the main codebase

**Repositories(Repo)**
- a repo is a container for a project you ant to track with Git (eg. a website project)
- can have many different repos for many different projects on your computer
- like  project folder which Git tracks the contents of for us

**What is commit?**
- they are like a safe point in a video game
- its a safe file that you can return to
- you can have multiple of these safe file

**The 3 stages of progress**
- *Modified*: changed file, not commited
- *Staging*: add any changed file to staging that you want to commit
- *Committed*: any file in the staging area are added to the commit when we make one

**Undoing Thing**
- *checkout commit*: (safe to use)
    - it will not let you edit anything in any way or ruin your commit history
    - this will show you a save point whenyou made a commit
    - any changes don at that save point while in checkout will not be saved
    - its a read-only, unable to destroy the commit history or alter it.
- *revert commit*: (somewhat safe to use)
    - this will undo a particular commit as if it never happened
- *reset commit*: (CAUTION)
    - you want to be sure that you need to use this before you do because potentially it could ruin your repository
    - can permanently delete all commits and your code is going to be back to how it was at certein particular commit

**Branches**
- *master branch*
    - when you create a new repo, you're also creating a master branch
    - can only commit to this master banch
    - master branch represent the stable version of your code 
    - and normally going to be the code which is released or published
- *Branching*
    - if you want to add a new feature to your application is to create another branch to try out the new feature
    - when you create a new branch your kind of copying the stable version of the code
    - you can work in this code in the new branch
    - and make a commit to test it out which is called a merge commit 
    - if you like the new feature and the code is stable then you can merge it to the master branch
    - if everything goes wrong in this new branch you've tested and messes the code up or doesn't work you can delete this branch  
    - the delete branch will not affect the master branch and the stable version of code will not be touched
    
    
    
