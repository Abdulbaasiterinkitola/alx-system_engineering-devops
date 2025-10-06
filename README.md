# alx-system_engineering-devops
## fifth alx BE prodev project

# 0x03. Shell, init files, variables and expansions

---

## Learning Objectives

To be able to explain (without Google):

- What happens when you type commands like `ls -l *.txt`.
- The purpose of shell initialization files like `/etc/profile`, `/etc/profile.d`, and `~/.bashrc`.
- The difference between local and global variables.
- How to create, update, and delete shell variables.
- What reserved variables (like `HOME`, `PATH`, `PS1`) are used for.
- The meaning of special parameters like `$?`.
- The difference between single and double quotes.
- How command substitution works with `$( )` and backticks.
- How to perform arithmetic in the shell.
- How to create and manage aliases.
- How to execute commands from a file in the current shell.

---

## Scripts

Each script is exactly **two lines long**: the shebang (`#!/bin/bash`) and the required command.

- **0-alias**  
  Creates an alias `ls` that runs `rm *`.

- **1-hello_you**  
  Prints `hello user`, where `user` is the current Linux user.

- **2-path**  
  Adds `/action` to the end of the `PATH`.

- **3-paths**  
  Prints the number of directories in the `PATH`.

- **4-global_variables**  
  Lists all environment variables.

- **5-local_variables**  
  Lists all local variables, environment variables, and shell functions.

- **6-create_local_variable**  
  Creates a local variable `BEST="School"`.

- **7-create_global_variable**  
  Creates a global variable `BEST="School"`.

- **8-true_knowledge**  
  Prints the result of adding `128` to the value stored in `$TRUEKNOWLEDGE`.

- **9-divide_and_rule**  
  Prints the result of `$POWER` divided by `$DIVIDE`.

- **10-love_exponent_breath**  
  Prints the result of `$BREATH` raised to the power of `$LOVE`.

- **11-binary_to_decimal**  
  Converts the binary number stored in `$BINARY` to decimal.

- **12-combinations**  
  Prints all possible two-letter combinations from `aa` to `zz`, excluding `oo`.

- **13-print_float**  
  Prints the number stored in `$NUM` with exactly two decimal places.

---

## Usage

To run a script:
```bash
./script_name
