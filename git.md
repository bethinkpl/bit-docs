# Git

basic shell (command line) usage

## Intro
Before you jump into Git it's good to first learn what are the version control systems and when it's good to use one.
You can read more about VCS (shortcut from Version Control System) in this article: https://pl.atlassian.com/git/tutorials/what-is-version-control

## Classification / acceptance questions
### Apprentice aka _My First Commit_
* I know what is a version control system and what are the use cases for it
* I know what Git is
* I can initialize empty Git repository on my local machine
* I understand different states of files in Git repository
** untracked
** unstaged
** staged
** commited
* I can list modified fiels on my local file system in version controled directory
* I can reset modified changes in a file
* I can stage changes for commit
* I can unstage changes
* I understand the concept of a commit and I can commit changes
* I can make Git ignore files in the repository

### Intermediate aka _I can branch!_
* I can answer all the questions from level 1 :)
* I can create a branch locally and switch between the branches
* I understand the concept of branching and I know which commits / changes I can expect on different branches
* I know there are remote Git servers and services that offer it like: Github, Bitbucket or Gitlab
* I can stash my changes and move them between branches
* I know how to move commits between branches, `git cherry-pick` command

### Advanced aka _Teamplayer_
* I know I can sync my changes with remote Git server
* I can push my changes to the remote server and pull them from it
* I can create branches locally and push them to the remote server
* I know what the mysterious `origin` means, I know how to add a remote server, change it's URL or remove it from my local git configuration
* I can collaborate with my teamates, share code, merge their changes into my branch and resolve the potential confilcts (in code :D)
* I know different approaches to collaboration in git project. I know what means names like:
** feature branch
** git flow
** pull(merge) request

### Wizard aka _I can fix what I break_
* I understand how Git history works
* I understand the difference between merging and rebasing
* I can revert my changes, both on my local machine and on remote Git server
* I know how to overwrite the Git history and I promise never to use it! :D

## Sources
### Books
- https://git-scm.com/book/en/v2

### Articles
- https://itnext.io/become-a-git-pro-in-just-one-blog-a-thorough-guide-to-git-architecture-and-command-line-interface-93fbe9bdb395
- https://pl.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow
- https://medium.com/@sauvik_dolui/a-few-git-tricks-tips-b680c3968a9b
