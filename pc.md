## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? Git is an open source distributed version control system.  It is a software for which the original source code is made freely available and may be redistributed. It also serves as a place that stores content that can be updated, shared and collaborated on in which programmers access a remote version on a central server or locally on their own computers. 
2. What is the difference between Git and GitHub? Git is the open source distributed version control system software while GitHub is a for-profit cloud-based git hosting service that allows for developers to access projects. 
3. Why do we create a branch? We create branches to conduct independent work on a collaborative project, such as working on bug fixes or new features.  The branch can be merged into the main repository later on. 
4. What is the purpose of a Pull Request? Pull requests allow for a developer to announce changes pushed onto a branch.  Once reviewed, it can eventually be determined if the branch can be merged into the base branch. 
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main. The git checkout command is what is used to switch between branches.  After inputing git checkout, input '-b "BRANCH_NAME"' to switch to the desired branch.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
-'git pull' command pulls from a remote branch to update the local branch currenlty being worked on.  
-'git merge' command allows you to merge several independent branches into one branch. 
-'git fetch' command allows you to see if there are any commits/files/changes available to download. Unlike 'git fetch', however, 'git pull' will do this AND copy the changes to the local branch from the remote repository.  
7. What is a merge conflict? A merge conflict occurs when competing changes are made to the same line of a file. 
8. How do you resolve a merge conflict? GitHub has a merge conflict editor tool that handles most conflicts during pull requests.  
