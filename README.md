# Minishell

A simple Unix shell implementation in C, designed to mimic Bash behavior with essential built-in commands, piping, redirection, environment management, and more. Developed as part of the 42 school curriculum.

## Features

- **Command Parsing & Execution:** Supports single and chained commands.
- **Built-in Commands:**  
  `cd`, `echo`, `pwd`, `export`, `unset`, `env`, `exit`
- **Environment Handling:**  
  `$VAR` variable expansion.
- **Input/Output Redirection:**  
  `>`, `>>`, `<`
- **Pipes:**  
  `|` for command chaining.
- **Quote Handling:**  
  Properly manages `'` and `"` quoting.
- **Signal Handling:**  
  Handles `Ctrl+C`, `Ctrl+D`, `Ctrl+\` and related signals.
- **Exit Status Management**

### Bonus Features

- **Command History:** Use arrow keys to navigate previous commands.
- **Logical Operators:**  
  `&&` and `||`
- **Wildcard Expansion:**  
  Globbing (e.g. `*.c`)
- **Enhanced Signal Handling:**  
  Ignores signals inside heredoc.
- **Improved Error Management:**  
  Handles edge cases, provides clear messages.

## Getting Started

### Prerequisites

- Unix-based operating system (Linux, macOS)
- GCC or Clang C compiler
- GNU Readline library (`libreadline`)

### Installation

Clone the repo:

```bash
git clone https://github.com/Miami05/Minishell.git
```
```bash
cd Minishell
```
Build the project:
```bash
make
```

Run Minishell:

```bash
./minishell
```

## Usage Example

minishell$ echo "Hello World"  
Hello World

minishell$ export NAME=Miami  
minishell$ echo $NAME  
Miami

minishell$ ls -l | grep minishell

## Contributing

Pull requests and issues are welcome for improvements or bug fixes. See the LICENSE for details.

## License

MIT License


Minishell is a great exercise for understanding OS internals, C programming, and shell design!

