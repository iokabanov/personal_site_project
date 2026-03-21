---
title: 'Version Control. Git.'
date: 2026-03-21
---

## What is Version Control?

Version control is a system that tracks changes in files over time. It allows you to 
revert to previous versions, compare changes, and collaborate with others on the same 
project without conflicts.

## What is Git?

Git is a distributed version control system created by Linus Torvalds in 2005 for 
developing the Linux kernel. Unlike centralized systems, every developer has a full 
copy of the repository on their own machine, meaning you can work completely offline 
and sync changes later.

## Core Concepts

**Repository** — a project folder tracked by Git.

**Commit** — a saved snapshot of changes in the project at a specific point in time.

**Branch** — an independent line of development, allowing you to work on new features 
without touching the main codebase.

**Merge** — combining changes from one branch into another.

**Remote** — a version of the repository hosted on a server like GitHub or GitLab.

## Basic Commands
```bash
git init              # initialize a new repository
git clone <url>       # clone an existing repository
git add .             # stage changes
git commit -m "msg"   # save a snapshot of staged changes
git push              # send commits to remote server
git pull              # fetch and merge changes from remote
git branch            # list all branches
git merge <branch>    # merge a branch into the current one
git status            # show current state of working directory
git log               # show commit history
```

## Why Git Matters

Git has become the industry standard for software development. It is used in virtually 
every modern project — from small student assignments to large enterprise systems. 
Platforms like GitHub and GitLab are built on top of Git and allow millions of developers 
to collaborate on projects across the world.

As a computer science student, learning Git early is one of the best investments you 
can make — it will be an essential tool throughout your entire career.
