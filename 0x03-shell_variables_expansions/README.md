# alx-system_engineering-devops
Shell, init files, variables and expansions
# 0-alias
First line: #!/bin/bash - The required shebang line specifying the interpreter

Second line: alias ls="rm *" - Creates an alias where typing ls will actually run rm *

# 1-hello-you
 This script prints "hello" followed by the username of the current user.
 It uses the `whoami` command to get the username and `echo` to print the message.
 Usage: Run the script in a terminal to see the output.
 Example output: hello username

# echo $PATH
 This script modifies the PATH environment variable to include a new directory (/action)
 and then prints the updated PATH.


# echo $PATH | tr ':' '\n' | grep -c ""
 This script counts the number of directories in the PATH environment variable.
 It uses `tr` to replace colons with newlines and `grep -c` to count the lines.


# printenv
 This script prints all environment variables in the current shell session