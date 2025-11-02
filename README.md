# ALX BE SHELL – Shell Permissions

## 🧠 Description

The **ALX BE SHELL** project focuses on understanding and managing **Linux file permissions** through the command line.  
You will learn how to view, modify, and assign permissions to files and directories using the **`chmod`**, **`chown`**, and **`su`** commands.  

This project is part of the ALX Software Engineering curriculum and builds your foundation in **system administration**, **user management**, and **shell scripting**.

---

## 🎯 Learning Objectives

By the end of this project, you should be able to explain (without Google):

### General
- What the **Linux shell** is  
- What **permissions** are and how they work  
- How to represent permissions in **symbolic** and **octal** notation  
- How to **change file ownership** and **user groups**  
- How to **switch users** in the terminal  
- The difference between **root**, **user**, and **group** permissions  
- How to make files **executable**  
- How to use **`chmod`**, **`chown`**, and **`sudo`**

---

## 🗂️ Project Structure

```bash
alx_be_shell/
├── 0-iam_betty               → Switches the current user to the user betty
├── 1-who_am_i                → Prints the effective username of the current user
├── 2-groups                  → Prints all the groups the current user is part of
├── 3-new_owner               → Changes the owner of a file
├── 4-empty                   → Creates an empty file
├── 5-execute                 → Adds execute permission to the owner of a file
├── 6-multiple_permissions    → Adds execute permission to owner/group and read permission to others
├── 7-everybody               → Adds execution permission to everyone
├── 8-James_Bond              → Sets permissions so only others have all rights
├── 9-John_Doe                → Sets specific permissions to a file using numeric mode
├── 10-mirror_permissions     → Mirrors permissions of another file
└── README.md                 → Project documentation

