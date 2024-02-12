# MLOps Class Task 01

This repository is for the MLOps class task.

## Repository Setup

### Creating and Pushing Branches

1. **Initialize the `dev` Branch**

    - Create the `dev` branch and switch to it:

        ```
        git checkout -b dev
        ```

    - Push the `dev` branch to GitHub:

        ```
        git push -u origin dev
        ```
   - The same is done for the test branch, using the main branch as the third branch for this task.

2. **Creating Individual Feature Branch**

    - For the first member (i200556), a new 'feature' branch is created and switched to:

        ```
        git checkout -b i200556
        ```

    - Push the new branch to GitHub:

        ```
        git push -u origin i200556
        ```
    - For the second member (i202308), a new 'feature' branch is created and switched to:

        ```
        git checkout -b i202308
        ```

    - Push the new branch to GitHub:

        ```
        git push -u origin i202308
        ```

### Project Scaffolding

After setting up the individual feature branch (`i200556`), the project scaffolding was initiated. This includes creating the necessary directories and files for a Python project.

- **Create Project Directories and Initialize Python Modules**

    ```
    mkdir src tests
    touch src/__init__.py tests/__init__.py
    ```

- **Stage Changes and Commit**

    ```
    git add .
    git commit -m "Project Scaffolding"
    ```

- **Push the Changes to GitHub**

    ```
    git push origin i200556
    ```

### Merging Feature Branch into Dev

After completing the project scaffolding on the `i200556` branch, the changes were merged back into the `dev` branch to integrate with the main development line.

- **Switch Back to `dev` Branch**

    ```
    git checkout dev
    ```

- **Pull the Latest Changes from `dev`**

    ```
    git pull origin dev
    ```

- **Merge `i200556` into `dev`**

    ```
    git merge i200556
    ```

- **Push Merged Changes to `dev` on GitHub**

    ```
    git push origin dev
    ```
- The same was done by 1202308 for their feature branch. 

### Updating README.md
 - The file now includes this log of commands used for the task

### Additional Git Commands Practiced

#### `git log`

- **Usage:** Displays commit history.
- **Command:**
  ```bash
  git log
  ```
- **Variations:**
  - `git log --oneline`: Condensed commit history.
