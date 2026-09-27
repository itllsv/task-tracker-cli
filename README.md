# A CLI Task Tracker in C
> **No AI used for learning reasons.**

A task manager built in C, based on the [roadmap.sh/projects/task-tracker](https://roadmap.sh/projects/task-tracker) requirements.

## Build:
```bash
gcc -o task-cli main.c
```

## Usage:
```bash
// Add
./task-cli add "Learn C pointers"

// Update with ID
./task-cli update 1 "Learn C pointers and memory allocation"

// Delete
./task-cli delete 1

// Change status
./task-cli mark-in-progress 1
./task-cli mark-done 1

// List
./task-cli list
./task-cli list done
./task-cli list todo
./task-cli list in-progress
```

This project is licensed under the [MIT License](LICENSE).
