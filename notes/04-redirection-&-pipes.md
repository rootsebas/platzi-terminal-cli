# 🔀 Redirection and Pipes in Linux

## Commands Used

- `>` (redirect output to a file)
- `>>` (append output to a file)
- `|` (pipe output to another command)
- `2>` (redirect errors to a file)
- `2>>` (append errors to a file)
- `&>` (redirect both output and errors)

## Description

- `>` → sends the standard output (stdout) of a command to a file (overwrites content)
- `>>` → appends the output to a file without overwriting existing content
- `|` → takes the output of one command and uses it as input for another command
- `2>` → redirects the standard error (stderr) to a file
- `2>>` → appends errors to a file instead of overwriting
- `&>` → redirects both standard output and standard error to the same file

## Examples

- `echo "hello world" > file.txt` → creates/overwrites a file with content
- `echo "hello again" >> file.txt` → appends content to the file
- `cat file.txt | lolcat` → pipes output to another command
- `ls missing_file 2> error.log` → saves errors into a file
- `ls missing_file 2>> error.log` → appends errors
- `sudo apt install vim &> install.log` → logs both output and errors

## Key Learnings

- Redirection allows you to control where command output goes (files or other commands)
- Pipes (`|`) enable chaining commands to create powerful workflows
- Errors can be handled separately from normal output using `2>`
- Combining outputs (`&>`) is useful for logging execution results
- These tools are essential for automation, debugging, and scripting in Linux