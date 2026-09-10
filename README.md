# Intelligent UNIX Command Shell

## Introduction

Intelligent UNIX Command Shell is a simple command-line shell developed in C.
It allows users to execute UNIX commands and provides some built-in commands for process management, directory navigation, and command history.

## Features

* Execute external UNIX commands
* Command history management
* Support for multiple commands using `;`
* Input and output redirection
* Pipe `|` support
* Built-in commands:

  * `Hist`
  * `curPid`
  * `pPid`
  * `cd`
  * `quit`
* Interactive shell prompt
* Command execution using `fork()` and `execvp()`

## Technologies Used

* C Programming
* Linux / UNIX
* System Calls
* Process Management
* Inter-Process Communication

## System Calls Used

* `fork()`
* `execvp()`
* `wait()`
* `pipe()`
* `dup2()`
* `chdir()'

## Project Objective

The main objective of this project is to understand how a UNIX shell works internally and 
to implement basic shell functionalities using C programming and UNIX system calls.

## Conclusion

This project provides practical knowledge of process creation, command execution,
pipes, redirection, built-in commands, and UNIX system calls.
