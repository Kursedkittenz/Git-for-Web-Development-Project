## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 

Git is an Open Source Distributed Version Control System.

2. What is the difference between Git and GitHub? 

Github is a company that provides cloud based hosting services that allows users to manage git repositories, Git is the Open Source Distributed Version Control System.

3. Why do we create a branch? 

Branches allow for isolated work from other team members of the same repository so tasks can be done independently

4. What is the purpose of a Pull Request? 
To update the local version of a repository from a remote one

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main. 

git switch "branch-name" 

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?

git fetch :  downloads objects and refs from another repository
git merge :  joins 2+ development histories together into the current branch
git pull : used to fetch and download content from a remote repository and update the local repository to match

7. What is a merge conflict?

when changes are made to the same file at the same time

8. How do you resolve a merge conflict?

-use git status to identify possible conflicted files and directly access the file in an editor

-git reset to reset to a previous good state

-get merge --abort to exit merge process and return to state before merge