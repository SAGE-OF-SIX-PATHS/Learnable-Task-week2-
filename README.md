# Learnable-Task-week-2
## A GitHub repo task.

### Explain version control.
Version Control, also known as source control, is the practice of tracking and managing changes to files.

### Explain difference between git and github
Git is a version control system that runs on your computer. It helps track changes in your code and facilitates collaboration by allowing multiple developers to work on the same codebase.
                                        While
GitHub is a cloud-based platform that uses Git to host repositories online. It provides tools for collaboration, such as pull requests, issue tracking, and project management.

### List 3 other github alternatives
a.GitLab: Offers Git repository hosting with CI/CD pipelines and built-in DevOps tools.
b.Bitbucket: Focuses on teams using Git and integrates tightly with Jira and Trello.
c.SourceForge: A platform for hosting open-source projects with Git and SVN support.

### Explain the difference between git fetch and git pull.
Git fetch: Here updates are downloaded from a remote repository but are not merged into your local branch. This command allows you to review changes before integrating them. A good example is: git fetch origin
                                        While
Git pull: This command combines git fetch and git merge into one step. It fetches updates from the remote repository and merges them into your current branch. Example: git pull origin main

### Explain in simple terms git rebase and the command for it
Git rebase is used for rewriting the history of a branch by moving its commits to the end of another branch, creating a cleaner and linear history.
It is used when the developer needs integrate changes from one branch into another without creating a merge commit.

Command: git rebase <branch>
Example: If you're on feature-branch and want to rebase it onto main: 
i.	git checkout feature-branch
ii.	git rebase main

### Explain in simple terms git cherry-pick and the command for it.
Git Cherry-pick is a git command that is used for applying a specific commit from one branch to another. It’s like saying, “I want this exact change, but I don’t need the whole branch.”
It is used when the programmer needs to selectively apply changes without merging an entire branch.

Command: git cherry-pick <commit-hash>
Example: To apply the commit with hash abc123 to your current branch: 
i.	git cherry-pick abc123
