# data210_git_basics
## Git

### What is Git?
Git is a popular version control system. It was created by Linus Torvalds in 2005, and has been maintained by Junio Hamano since then.

### Git is used for:

- Tracking code changes
- Tracking who made changes
- Coding collaboration

### What does Git do?
- Manage projects with Repositories
- Clone a project to work on a local copy
- Control and track changes with Staging and Committing
- Branch and Merge to allow for work on different parts and versions of a project
- Pull the latest version of the project to a local copy
- Push local updates to the main project

### Working with Git
- Initialize Git on a folder, making it a Repository
-Git now creates a hidden folder to keep track of changes in that folder
- When a file is changed, added or deleted, it is considered modified
- You select the modified files you want to Stage
- The Staged files are Committed, which prompts Git to store a permanent snapshot of the files
- Git allows you to see the full history of every commit.
- You can revert back to any previous commit.
- Git does not store a separate copy of every file in every commit, but keeps track of changes made in each commit!

### Why Git?
  - Over 70% of developers use Git!
  - Developers can work together from anywhere in the world.
  - Developers can see the full history of the project.
  - Developers can revert to earlier versions of a project.

### What is GitHub?
  - Git is not the same as GitHub.
  - GitHub makes tools that use Git.
  - GitHub is the largest host of source code in the world, and has been owned by Microsoft since 2018.
  
### Git Install
- You can download Git for free from the following website: https://www.git-scm.com/

#### Using Git with Command Line
- To start using Git, we are first going to open up our Command shell.
- For Windows, you can use Git bash, which comes included in Git for Windows. For Mac and Linux you can use the built-in terminal.
- The first thing we need to do, is to check if Git is properly installed:
- Example
```
git --version
git version 2.30.2.windows.1
```
- If Git is installed, it should show something like git version X.Y

## Other version control providers
### Bitbucket
- Bitbucket is a Git hosting solution from Atlassian. 
- Bitbucket Server is the self-hosted version of Bitbucket. 
- Stackery supports both versions of the service, and can be set up with the following CLI commands:
```
stackery bitbucket setup [flags]
stackery gitproviders setup -p myBitbucketServerName
```
### GitLab
- GitLab is another Git provider that offers a variety of DevOps tools. Stackery supports both public and private repositories as well as GitLab groups. 
- GitLab can be set up with the following CLI command:
```
stackery gitlab setup [flags]
```



