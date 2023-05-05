# Use Past to easily copy files and directories

"Past" is a handy tool designed to select a file or directory from the string content of a target, and then paste it into a new working directory. To make "Past" work, you need a tool called [Mark](https://github.com/ayoubelmhamdi/mark).

## Usage
Here's how to copy a file or directory:

```shell
$ mark file.txt
$ cd /new/dir/path
$ past
```

When you type "past" without any arguments, the content of the file or directory selected will be copied and pasted into the working directory `/tmp/target_content`.

## Contributions

This project requires several "PRs" to address issues related to permission errors, redundancy, and storage limitations. Additionally, we encourage contributors to refactor it in other programming languages like C, Rust, or Go.
