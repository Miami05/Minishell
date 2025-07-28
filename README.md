# Minishell
A simple Unix shell implementation in C, designed to mimic the behavior of Bash with basic built-in commands, piping, redirection, and environment management. Developed as part of the 42 school curriculum.

## Features

- Command parsing and execution (supports single and multiple commands)
- Built-in commands: `cd`, `echo`, `pwd`, `export`, `unset`, `env`, `exit`
- Environment variable handling (`$VAR` expansion)
- Input/output redirection (`>`, `>>`, `<`)
- Pipes (`|`) for command chaining
- Quote handling (single `'` and double `"` quotes)
- Proper signal handling (`Ctrl+C`, `Ctrl+D`, `Ctrl+\`)
- Exit status management

## Bonus Features

- Support for command history (using arrow keys for navigation)
- Logical operators: `&&` and `||`
- Wildcard expansion (globbing, e.g. `*.c`)
- Enhanced signal handling (e.g., ignoring signals inside heredoc)
- Improved error messages and edge-case handling

## Getting Started

### Prerequisites

- Unix-based OS (Linux, macOS)
- GCC or Clang compiler
- GNU Readline library (`libreadline`)

### Installation

Clone the repository:

```bash
git clone https://github.com/your-username/minishell.git
cd minishell


Build the project:

make

Run the shell:

./minishell
```
```
```
```

Let me know if you want to add usage examples, contributor guidelines, or anything more specific!

