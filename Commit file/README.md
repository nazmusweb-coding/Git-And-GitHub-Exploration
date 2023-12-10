## Git Commit Commands

### `git commit -m "[comment]"`

```bash
git commit -m "[comment]"
```

This command is used to commit changes with a specified commit meaningful message directly from the command
line.This allows you to include a brief comment about the changes you are committing. it's generally considered
a good practice to include a meaningful commit message for each commit.

*Usage:* `[for committing with message]`

---

### `git commit -a`

```bash
git commit -a
```

This command stages all tracked and modified files, the -a flag tells Git to automatically stage all files that
are currently tracked by the Git repository and have any modifications. This saves you from having to stage each
file individually using the git add command. when you want to commit all tracked and modified files at once.
This is a convenient way to commit changes after making edits to several files. The -a flag will not stage untracked files.

*Usage:* `[for staging all the tracked and modified files without using git add command]`

---

### `git commit --amend`

```bash
git commit --amend
```

This command allows you to modify your most recent commit. To fix a typo or error in your commit message.
This is a quick and easy way to correct a mistake without having to create a new commit.

*Usage:* `[for replacing/modifying your last/previous commit]`

Here are some additional options(flags) you can use with git commit --amend:

1. ### `--no-edit`

    ```bash
    git --amend --no-edit
    ```
    
    This flag prevents the editor from opening, so you can only add staged changes without modifying the commit message. It merges all the addtions and modifications with previous commit without committing new message.

2. ### `--reset-author` 

    ```bash
    git --amend --reset-author
    ```

    This flag allows you to change the author information for the amended commit.

3. ### `--date`

    ```bash
    git --amend --date
    ```

    This flag allows you to change the date of the amended commit.

---

**Differences between git commit -m ["comment"], git commit -a, git commit --amend**

| Command                             | Stages Changes?  | Commits Changes? | Allows Changing Commit Message? |         Purpose                                                                       |
|-------------------------------------|------------------|------------------|---------------------------------| -----------------------------------------------------------------------------------------------------------------------------------------------|
| git commit -m ["comment"]           | Manually         | Yes              | No                              | Quick commits with a specified message.                                                                                                        |
| git commit -a                       | Automatically    | Yes              | No                              | Quick commit of all modifications and deletions to tracked files. Does not include untracked files.                                            |
| git commit --amend                  | Manually         | Yes              | Yes                             | Modifies the last commit, combining staged changes with the previous commit. Allows changing the commit message. Useful for quick adjustments. |

---

**Short summary**

| Command                       |                                                      Description                                                                                                                |
|-------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| git commit -m ["comment"]	|      Commits changes with a specified commit message directly from the command line.                                                                                            |  
| git commit -a	                |      Stages and commits all changes to tracked files (modifications and deletions) in one step. Does not include untracked files.                                               |
| git commit --amend	        |      Modifies the last commit by combining staged changes with the previous commit. Allows changing the commit message. Useful for making quick adjustments to the last commit. |


---

**N.B. -** If you find any missing information, inaccuracies, or have suggestions for improvement, please feel free to contribute. Your insights and expertise will help in the continuous development and enhancement of this resource.
