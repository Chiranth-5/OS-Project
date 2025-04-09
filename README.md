# OS-Project

# Simple Shell

This project is a basic Linux shell implemented in C. It supports:

- Executing external commands (e.g., `ls`, `pwd`)
- Custom built-in commands: `cd`, `exit`
- Background execution using `&` (coming soon)
- Input parsing with `fork()`, `execvp()`, and `wait()`

## Build & Run

```bash
make
./myShell
