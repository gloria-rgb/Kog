#Frontend learnable assignment.

##What is version control?
- Version control, also known as source control, is the practice of tracking and managing changes to software code.
- Version control enables the current team to analyze the deletion, editing, and creation of datasets made since the original copy. It brings clarity to the development of the software. It ensures that different versions of the document are distinguishable from each other. So, it is easy to identify the latest version.


##Difference betwen Git and Github.
- Git is a version control system that allows developers to track changes in their code while GitHub is a web-based hosting service for git repositories.
- In simple terms, you can use git without Github, but you cannot use GitHub without Git

##3 other github alternatives are:
- Bitbucket
- Sourceforge
- Gitea.

##Difference between gitfetch and gitpull.
- Git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo. 
- The git pull command does both.

##Git rebase
- A Git rebase changes the base of the developer's branch from one commit to another, so it looks like they have created their branch from a different commit. Internally, Git creates a new commit and applies it to the specified base.

 ##Git rebase commands
- git rebase <base>:	Performs the standard rebase
- git rebase -- x:	This executes a command line shell script for each marked commit during playback.
- git status: Checks the rebase status.
git rebase -- continue:	Continue with the changes that you made.
- git rebase --skip	:Skips the changes


##Git cherry-pick
- Git cherry-pick is a Git command that allows you to select and apply individual commits from one branch to another. 
- git cherry-pick --name