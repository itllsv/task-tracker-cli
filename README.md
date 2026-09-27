# A CLI Task Tracker in C
> **No AI used for learning reasons.**

A task manager built in C, based on the [roadmap.sh/projects/task-tracker](https://roadmap.sh/projects/task-tracker) requirements.

## Build:
```bash
gcc -o task main.c
```

## Usage:
### add
```bash
./task add "Learn C pointers"
```

### update
```bash
./task update 1 "Learn C pointers and memory allocation"
```

### delete
```bash
./task delete 1
```

### change status
```bash
./task mark-in-progress 1
./task mark-done 1
```

### list
```bash
./task list
./task list done
./task list todo
./task list in-progress
```

This project is licensed under the [MIT License](LICENSE).
