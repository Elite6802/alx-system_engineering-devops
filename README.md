# 0x03. Shell, init files, variables and expansions

## 🚀 Project Overview
This project is part of the **DevOps** stream, focusing on fundamental concepts of the **Bash Shell**, including initialization files, variable management, and various forms of command expansion.

| Element | Detail |
| :--- | :--- |
| **Weight** | 1 |
| **Start Date** | Sep 29, 2025 6:00 AM |
| **End Date** | Oct 6, 2025 6:00 AM |
| **Technologies** | Shell, Bash |

***

## 🧠 Learning Objectives

At the completion of this project, I am expected to explain the following concepts:

### General
* What happens during the shell's processing when you type `$ ls -l *.txt`.

### Shell Initialization Files
* The purpose of the `/etc/profile` file and the files within the `/etc/profile.d` directory.
* The role and execution of the `~/.bashrc` file.

### Variables
* The difference between a local and a global variable.
* The concept of a reserved variable.
* How to create, update, and delete shell variables.
* The roles of reserved variables: `HOME`, `PATH`, and `PS1`.
* What special parameters are, including the purpose of `$?`.

### Expansions
* What expansion is and how to use different types.
* The differences between single (`'`) and double (`"`) quotes.
* How to perform command substitution using `$()` and backticks (\`).

### Shell Arithmetic
* How to perform arithmetic operations within the shell.

### The `alias` Command
* How to create, list, and temporarily disable an alias.

***

## 🛠️ Project Requirements

### General
* Allowed editors: `vi`, `vim`, `emacs`.
* Scripts will be tested on **Ubuntu 20.04 LTS**.
* All scripts must be exactly **two lines long** (`$ wc -l file` should print 2).
* All files must end with a **new line**.
* The first line of all scripts must be `#!/bin/bash`.
* **Restrictions:** You may not use `&&`, `||`, or `;`.
* **Restrictions:** You may not use `bc`, `sed`, or `awk`.
* All files must be **executable**.

***

## 📁 Files and Descriptions

| File Name | Description |
| :--- | :--- |
| **`0-alias`** | A Bash script that creates a temporary shell alias named `ls` with the value `rm *`. This intentionally dangerous alias overwrites the standard file-listing command with a file-deletion command. |
| ... | *(Other files will be added here as tasks are completed)* |
