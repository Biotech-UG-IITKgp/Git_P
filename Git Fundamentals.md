# Git Fundamentals

## Basic Commands

### 1. Setup Info

To check the **version** of git installed in the system.

```bash
git --version
```

**Configure git**. To tell username and email. To track who made the changes.

```bash
git configure --global user.name "Your Name"
git configure --global user.email "your@email.com"
```

### 2. Repositories

A git repo is a container for a project that is tracked by Git. Two major types of repos are:

- Local Repository: isolated, stored in your computer.
- Remote Repository: usually stored on remote server.

```bash
git init  #Initialization

# initialization allows git to start tracking, as the container is made into a repository
```

### 3. Staging and Committing

Committing is the act of 'officially' adding to the Git repository. They can be considered as checkpoints, or snapshots from where we can _resume if we want to_.

Commits are added where there is change in logic, or a new feature is added, or something is modified, etc.

**Before we can commit the code, we need to put it in the staging area.**

**Git Status command**. It is used to review all the current information about the git repository.

```bash
git status
```

- Untracked files and staging area.

5. **Git add command** - It is used to add the selected untracked files to the staging area. Since many times we do not wish to commit all the files.

```bash
git add <file1> <file2>
```

Here, both file 1 and 2 will be added to the staging area.
