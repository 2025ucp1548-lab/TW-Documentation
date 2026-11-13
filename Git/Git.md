
# Git

## 1. Introduction

Git is a distributed version control system used to track changes in files and manage project development.

It allows developers to maintain different versions of a project and collaborate efficiently.

## 2. Why Do We Need Git?

- Tracks changes in files.
- Maintains project history.
- Helps recover earlier versions.
- Supports teamwork.
- Allows parallel development using branches.
- Prevents accidental loss of previous work.

## 3. Git Architecture

Git mainly works with three areas:

1. Working Directory – Contains the files being edited.
2. Staging Area – Contains changes selected for the next commit.
3. Local Repository – Stores committed versions and project history.

A remote repository, such as GitHub, allows sharing and collaboration.

## 4. Git Installation

For Windows, download Git from:

https://git-scm.com/downloads

For Ubuntu:

```bash
sudo apt update
sudo apt install git
```

Verify installation:

```bash
git --version
```

## 5. Git Configuration

Configure your identity:

```bash
git config --global user.name "Nidhi Panchal"
git config --global user.email "your-email@example.com"
```

View configuration:

```bash
git config --global --list
```

Replace the example email with your GitHub-associated email.

## 6. Basic Git Workflow

```bash
git init
git status
git add .
git commit -m "Initial commit"
```

## 7. Important Git Concepts

- Repository: Stores project history.
- Commit: Records a snapshot of staged changes.
- Branch: Independent line of development.
- Merge: Combines changes from branches.
- Remote: A reference to another repository.
- Clone: Creates a local copy of a repository.

## 8. Advantages of Git

- Distributed version control.
- Fast operations.
- Reliable change tracking.
- Branch-based development.
- Collaboration support.

## 9. Conclusion

Git is an essential tool for managing project versions and maintaining a reliable development history.
