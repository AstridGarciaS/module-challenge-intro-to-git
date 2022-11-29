## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is a tool used for source code management and is used by thousands of developers around the world to actively maintained open-source revision control Systems.

2. What is the difference between Git and GitHub?
Git is a version control system that lets you manage and track your source code history. GitHub is a cloud-based hosting service that allows you to manage Git repositories.

3. Why do we create a branch?
We create a branch to maintain stability so that we can encapsulate changes in case of an error.  

4. What is the purpose of a Pull Request?
The purpose of a pull request is to tell others about changes pushed to a branch in a repository on GitHub. 

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
The command is git checkout -b

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git fetch is used to download contents from a remote repository.
git merge, allows you to integrate independent lines of development created into a single branch.
git pull is used to download content from a remote repository and update the local repository to match that content.

7. What is a merge conflict?
A merge conflict occurs when Git is unable to automatically resolve differences in code between two commits.

8. How do you resolve a merge conflict?
To resolve the merge conflict open it finds the affected files and makes any necessary changes to resolve the conflict. After editing the file, we can use the git add a command to stage the new merged content. Create a new commit with the help of the git commit command and Commit your changes with a comment.
