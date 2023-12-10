## Git Branch Management Commands

### `git branch -m [old_name] [new_name]`

```bash
git branch -m [old_name] [new_name]
```

This command renames a branch.

*Usage:* `[for renaming a branch]`

---

### `git checkout [branch_name]`

```bash
git checkout [branch_name]
```

This command is used to switch to a different branch.

*Usage:* `[for switching to a different branch]`

---

### `git checkout -b [branch_name]`

```bash
git checkout -b [branch_name]
```

This command creates and switchs to a branch simultaneously, you can use a command that combines both actions.

*Usage:* `[for creating and switching to a branch at once]`

---

### `git merge [branch_name]`

This command merges another branch into the current branch.

*Usage:* `[for merging branches]`

---

**Git management commands comparison and their use cases**

| Command                                   | Description                                              | Use Case                                                                   |
| ----------------------------------------- | -------------------------------------------------------- | -------------------------------------------------------------------------- |
| `git branch -m <old_name> <new_name>`    | Renames an existing branch to a new name.               | Useful when you want to change the name of an existing branch.              |
| `git checkout <branch_name>`              | Switches to the specified branch.                       | Commonly used to navigate between different branches in the repository.   |
| `git checkout -b [branch_name]`          | Creates and switches to a new branch in one command.    | Convenient for quickly creating and switching to a new branch.             |
| `git merge <branch_name>`                 | Merges changes from the specified branch into the current branch. | Integrates changes made in one branch into another, often used for feature branches. |

---

**N.B. -** If you find any missing information, inaccuracies, or have suggestions for improvement, please feel free to contribute. Your insights and expertise will help in the continuous development and enhancement of this resource.
