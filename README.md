# A CLI Task Tracker in C
> **No AI used for learning reasons.**

A task manager built in C, based on the [roadmap.sh/projects/task-tracker](https://roadmap.sh/projects/task-tracker) requirements.

## Build:
```bash
gcc -o task-cli main.c
```

## Usage:
### add
```bash
./task-cli add "Learn C pointers"
```

### update
```bash
./task-cli update 1 "Learn C pointers and memory allocation"
```

### delete
```bash
./task-cli delete 1
```

### change status
```bash
./task-cli mark-in-progress 1
./task-cli mark-done 1
```

### list
```bash
./task-cli list
./task-cli list done
./task-cli list todo
./task-cli list in-progress
```

This project is licensed under the [MIT License](LICENSE).
