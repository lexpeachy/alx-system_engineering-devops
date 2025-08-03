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


 # compgen -A variable -A function -A export


 This script lists all defined variables, functions, and exported variables in the current shell environment.
 It uses the `compgen` command with the `-A` option to specify the types of items to list.
 The `-A variable` option lists all shell variables, `-A function` lists


# BEST=School
Creates a local variable named BEST with value "School"


# export BEST=School

Script to Create a New Global (Environment) Variable

# echo $((128 + $TRUEKNOWLEDGE))


 This script calculates the value of TRUEKNOWLEDGE, which is set to 89.
 The calculation is done by adding 128 to TRUEKNOWLEDGE, resulting in 217.
 The output will be 217 when the script is executed.
 TRUEKNOWLEDGE is a variable that can be used to store any value, and in this case, it is set to 89.
 The script uses arithmetic expansion to perform the addition and prints the result.

# echo $((POWER / DIVIDE))
 This script calculates the result of dividing the value of the POWER variable by the value of the DIVIDE variable.
 It uses arithmetic expansion to perform the division.
 Ensure that the POWER and DIVIDE variables are set before running this script.


# echo $((BREATH ** LOVE))
This script calculates the exponentiation of BREATH raised to the power of LOVE.
 It uses the arithmetic expansion $((...)) to perform the calculation.
 Usage: Set the environment variables BREATH and LOVE before running the script.

# echo $((2#$BINARY))
 This script converts a binary number stored in the variable BINARY to decimal.
 It uses the arithmetic expansion $((...)) to perform the conversion.
 Usage: Set the BINARY variable to a binary number (e.g., export BINARY=1010) and run the script.
 Example: If BINARY=1010, the output will be 10.

# printf "%.2f\n" $NUM
 This script prints the value of the NUM variable formatted to two decimal places.
 Usage: Set the NUM variable before running the script, e.g., NUM=3.14159 ./13-print_float