# Bash Scripting Exercises

This repository contains a collection of Bash scripting exercises organized into different directories. Each directory focuses on a specific topic related to Bash scripting, such as file operations, variable handling, and permissions.

## Directory Structure

- `init_files_variables_and_expansions/`: Scripts related to initialization files, variables, and expansions.
- `io_redirections_and_filters/`: Scripts demonstrating input/output redirections and filters.
- `permissions/`: Scripts related to file and directory permissions.

## init_files_variables_and_expansions

This directory contains scripts that demonstrate the use of initialization files, variables, and expansions in Bash.

### Scripts

- `0-alias`: Creates an alias for the `ls` command to remove all files.
- `1-hello_you`: Prints a greeting message with the current user's name.
- `2-path`: Adds `/action` to the `PATH` environment variable.
- `3-paths`: Counts the number of directories in the `PATH`.
- `4-global_variables`: Prints all global environment variables.
- `5-local_variables`: Placeholder script for local variables.
- `6-create_local_variable`: Creates a local variable `BEST` with the value "School".
- `7-create_global_variable`: Creates a global variable `BEST` with the value "School".
- `8-true_knowledge`: Adds 128 to the value of the `TRUEKNOWLEDGE` variable and prints the result.
- `9-divide_and_rule`: Divides the value of `POWER` by `DIVIDE` and prints the result.
- `10-love_exponent_breath`: Raises `BREATH` to the power of `LOVE` and prints the result.
- `11-binary_to_decimal`: Converts a binary number stored in `BINARY` to decimal and prints the result.
- `12-combinations`: Generates all two-letter combinations from `a` to `z` excluding "oo".
- `13-print_float`: Prints the value of `NUM` as a floating-point number with two decimal places.
- `14-decimal_to_hexadecimal`: Converts a decimal number stored in `DECIMAL` to hexadecimal and prints the result.
- `15-rot13`: Encodes input using the ROT13 cipher.
- `16-odd`: Placeholder script for odd operations.
- `17-water_and_stir`: Performs a custom transformation on the `WATER` and `STIR` variables and prints the result.

## io_redirections_and_filters

This directory contains scripts that demonstrate input/output redirections and filters in Bash.

### Scripts

- `0-hello_world`: Prints "Hello, World".
- `1-confused_smiley`: Prints a confused smiley face.
- `2-hellofile`: Prints the contents of `/etc/passwd`.
- `3-twofiles`: Prints the contents of `/etc/passwd` and `/etc/hosts`.
- `4-lastlines`: Prints the last 10 lines of `/etc/passwd`.
- `5-firstlines`: Prints the first 10 lines of `/etc/passwd`.
- `6-third_line`: Prints the third line of the file `iacta`.
- `7-file`: Creates a file with a specific name and writes "Best School" to it.
- `8-cwd_state`: Saves the output of `ls -la` to a file named `ls_cwd_content`.
- `9-duplicate_last_line`: Appends the last line of the file `iacta` to itself.
- `10-no_more_js`: Deletes all `.js` files in the current directory.
- `11-directories`: Counts the number of directories in the current directory.
- `12-newest_files`: Lists the 10 newest files in the current directory.
- `13-unique`: Filters out repeated lines from the input.
- `14-findthatword`: Searches for the word "root" in `/etc/passwd`.
- `15-countthatword`: Counts the occurrences of the word "bin" in `/etc/passwd`.
- `16-whatsnext`: Prints the lines following the word "root" in `/etc/passwd`.
- `17-hidethisword`: Prints all lines in `/etc/passwd` that do not contain the word "bin".
- `18-letteronly`: Prints lines from `/etc/ssh/sshd_config` that start with a letter.
- `19-AZ`: Translates characters 'A', 'c', and 'e' to 'Z', 'e', and 'e' respectively.
- `20-hiago`: Deletes characters 'c' and 'C' from the input.
- `21-reverse`: Reverses the input.
- `22-users_and_homes`: Prints the usernames and home directories from `/etc/passwd`, sorted alphabetically.
- `23-empty_casks`: Finds and prints the names of empty files and directories.
- `24-gifs`: Finds all `.gif` files, removes the extension, and sorts the results.
- `25-acrostic`: Prints the names of empty files and directories.
- `26-the_biggest_fan`: Prints the names of empty files and directories.

## permissions

This directory contains scripts that demonstrate file and directory permission operations in Bash.

### Scripts

- `5-execute`: Adds execute permission for the user on the file `hello`.
- `6-multiple_permissions`: Adds execute permission for the user and group, and read permission for others on the file `hello`.
- `7-everybody`: Adds execute permission for all users on the file `hello`.
- `8-James_Bond`: Sets the permissions of the file `hello` to `007`.
- `9-John_Doe`: Sets the permissions of the file `hello` to `753`.
- `10-mirror_permissions`: Sets the permissions of the file `hello` to match those of the file `olleh`.
- `11-directories_permissions`: Adds execute permission for all users on all directories.
- `12-directory_permissions`: Creates a directory `my_dir` with permissions `751`.
- `13-change_group`: Changes the group of the file `hello` to `school`.
- `14-change_owner_and_group`: Recursively changes the owner and group of all files and directories to `vincent:staff`.
- `15-symbolic_link_permissions`: Changes the owner and group of the symbolic link `_hello` to `vincent:staff`.
- `16-if_only`: Changes the owner of the file `hello` to `vincent` if the current owner is `guillaume`.

## Usage

To run any of the scripts, navigate to the appropriate directory and execute the script using Bash. For example:

```sh
cd io_redirections_and_filters
./0-hello_world