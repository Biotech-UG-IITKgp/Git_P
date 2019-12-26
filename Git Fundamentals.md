# Git Fundamentals

## Basic Commands

1. To check the **version** of git installed in the system.

```bash
git --version
```

2. **Configure git**. To tell username and email. To track who made the changes.

```bash
git configure --global user.name "Your Name"
git configure --global user.email "your@email.com"
```

3. Repositories and **initialization**.

```bash
git init
```

4. **Git Status command**. It is used to review all the current information about the git repository.

```bash
git status
```

- Untracked files and staging area.

5. **Git add command** - It is used to add the selected untracked files to the staging area. Since many times we do not wish to commit all the files.

```bash
git add <file1> <file2>
```

Here, both file 1 and 2 will be added to the staging area.
