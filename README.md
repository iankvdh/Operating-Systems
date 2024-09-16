# Operating Systems - Practical Assignments

This repository contains the practical assignments completed for the **Operating Systems** course. The projects are implemented in C and ASM, using standards such as **C11** and **POSIX.1-2008**, covering various fundamental aspects of operating systems development.

## Contents

### TP1: Minimal Shell Interpreter

Development of the minimal functionality of a shell interpreter similar to **bash**, **zsh**, or **fish**. This shell supports basic command execution, with limited features like input/output redirection.

### TP2: Base Scheduler

Implementation of context switching for processes and the task scheduler on an existing operating system. The focus is on efficient process management and CPU time distribution.

- **Objective**: Implement a task scheduler that supports multiple processes
- **Features**: Context switching, process management

### TP3: FUSE-Based Filesystem

Creation of a custom filesystem using **FUSE** (Filesystem in Userspace). This filesystem is designed to be fast, operating entirely in memory, with a single file representing the data on disk.

- **Objective**: Enable the implementation of a user-mode filesystem with access to the VFS interface through standard system calls such as `read`, `open`, `ls`, etc.
- **Features**: In-memory filesystem, access through syscalls, represented as a single file on disk

