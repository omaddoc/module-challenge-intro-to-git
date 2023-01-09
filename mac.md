## Research Questions

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
   Git is a Version Control System used for tracking a users changes.
2. What is the difference between Git and GitHub?
   The difference between Git and Github is that Git is used to track a users changes, Github is a way to store those changes online.
3. Why do we create a branch?
   To write our own version of a feature we are working on so it doesn't mess with the main one.
4. What is the purpose of a Pull Request?
   To compare the changes the user made.
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
   git checkout main
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
   git fetch is a command used to download contents from a remote repository,
   git merge is putting the forked branch with the main branch,
   git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.
7. What is a merge conflict?
   A merge conflict is an event that takes place when Git is unable to automatically resolve differences in code between two commits
8. How do you resolve a merge conflict?

There are a few steps that could reduce the steps needed to resolve merge conflicts in Git.

The easiest way to resolve a conflicted file is to open it and make any necessary changes.
After editing the file, we can use the git add command to stage the new merged content.
The final step is to create a new commit with the help of the git commit command.
Git will create a new merge commit to finalize the merge.

Git Commands to Resolve Conflicts

1. git log --merge
   The git log --merge command helps to produce the list of commits that are causing the conflict

2. git diff
   The git diff command helps to identify the differences between the states repositories or files

3. git checkout
   The git checkout command is used to undo the changes made to the file, or for changing branches

4. git reset --mixed
   The git reset --mixed command is used to undo changes to the working directory and staging area

5. git merge --abort
   The git merge --abort command helps in exiting the merge process and returning back to the state before the merging began

6. git reset
   The git reset command is used at the time of merge conflict to reset the conflicted files to their original state
