# minishell
MiniShell is a project that aims to implement a simple bash shell, capable of executing basic commands, handling multiple commands with pipes, and managing file redirections. This project provides a user-friendly interface for interacting with a command-line operating system.

## Introduction
A command-line operating system, also known as a shell, provides users with a text-based interface to interact with the underlying operating system. Instead of using a graphical user interface (GUI), users enter commands directly into a command prompt, which the shell interprets and executes.

The shell acts as an intermediary between the user and the operating system, accepting commands and passing them to the appropriate system programs for execution. It also provides features such as file and process management, input/output redirection, piping, and scripting capabilities.

## Features
MiniShell incorporates the following features:

- **Command Execution:** MiniShell can execute basic commands entered by the user, such as ls, cd, mkdir, rm, etc. It supports both built-in commands and external programs installed on the system.

- **Multiple Commands with Pipes:** MiniShell allows users to chain multiple commands together using pipes (|). This feature enables the output of one command to serve as the input for the next command in the pipeline.

- **Redirections:** MiniShell supports file redirections to manage input and output streams. Users can redirect standard input (<), standard output (>), and standard error (2>).

- **Built-in Commands:** MiniShell provides a set of built-in commands that are executed directly by the shell without invoking external programs. Some common built-in commands include cd, echo, exit, and pwd.

## Usage
To use MiniShell, follow these steps:

Clone the MiniShell repository from GitHub:

```bash
git clone https://github.com/your-username/minishell.git
```
Navigate to the project directory:

```bash
cd minishell
```
Build the MiniShell executable:
```bash
make
```
Run the MiniShell:

```bash
./minishell
```
You can now start entering commands and exploring the features of MiniShell.

## Examples
Here are some examples to showcase the usage of MiniShell:

- Execute a basic command:

```shell
$ ls
file1.txt  file2.txt  directory
```
Chain multiple commands with pipes:

```shell
Copy code
$ ls | grep .txt
file1.txt
file2.txt
```
Redirect input and output:

```shell
$ cat < input.txt > output.txt
```
Use built-in commands:

```shell
$ cd directory
$ pwd
/path/to/directory
```
## Contributing
Contributions to MiniShell are welcome! If you find any issues or have ideas for enhancements, feel free to submit a pull request or open an issue on the GitHub repository.

When contributing, please ensure to follow the project's code style and guidelines.

## License
MiniShell is a program coded by me and [Albertoja]().

## Acknowledgments
MiniShell was inspired by the functionality of the bash shell and aims to provide a simplified version of its features.


Happy coding!
