# LINUX-ASSIGNMENT-5
Linux Programming Assignment 5: Comprehensive study of Shell categories (sh, bash, csh, zsh), I/O redirection (stdin, stdout, stderr), command aliases, and advanced manual searching with apropos.

Overview
This repository covers the fundamental concepts of the Linux Shell environment, including shell varieties, input/output redirection techniques, and command-line efficiency tools.

Topics & Commands Covered

1. The Linux Shell

Definition: A command-line interpreter that acts as an interface between the user and the kernel, providing features like I/O redirection, piping, and automation scripts.


Categories:


Bourne Shell family: Includes sh, bash (most popular), dash, ksh, and zsh .


C Shell family: Includes csh and its enhanced version tcsh .


Why Bash?: It is the industry standard due to its backward compatibility with sh, command history, tab completion, and advanced aliasing .

2. Standard Streams & Redirection
Linux manages data through three standard file descriptors :

Standard Input (stdin - 0): Keyboard input.

Standard Output (stdout - 1): Screen output.

Standard Error (stderr - 2): Error messages.

Redirection Techniques:


Error Logging: Redirecting only errors to a file using command 2> error.log .


Appending with tee: Using tee -a to add data to the end of an existing file without overwriting it .

3. Command-Line Efficiency

Aliases: Creating shortcuts for long commands (e.g., alias ll='ls -la') to improve productivity .

Advanced Help:


apropos: Searches manual page names and descriptions for a keyword—essential when you don't know the exact command name .


whatis: Provides a quick, one-line summary of a specific command.
