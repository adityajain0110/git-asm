# git-asm
# Git VCS Assignment: Deleting Files

## Project Information
* **Name:** Pranav Sharma
* **Problem Statement:** GIT-10 - Delete a File Using Git
* **Objective:** Demonstrate the proper workflow for removing an existing, tracked file from a Git repository using the command line interface.

## Overview
Removing a file in Git requires more than just deleting it from the local file explorer. To effectively remove a file from the repository's tracked history, the deletion must be staged and committed. This project demonstrates the exact command line workflow to achieve this safely.

## Git Commands Used
* `git status`: Used to check the state of the working directory and the staging area.
* `git rm <filename>`: Used to remove the file from the working tree and stage the deletion automatically.
* `git rm --cached <filename>`: (Alternative) Used to untrack a file from Git without deleting it from the local hard drive.
* `git commit -m "message"`: Used to finalize the deletion in the branch history.

## Step-by-Step Workflow

**1. Verify Workspace Status**
Checked the current repository status to ensure a clean working tree before making changes.
```bash
killi@PRANAV MINGW64 ~/git-assignment (main)
$ git status
On branch main
nothing to commit, working tree clean
