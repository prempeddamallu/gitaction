# My Exciting Project

Welcome to **My Exciting Project**! This repository is part of a Git assignment to build foundational skills in version control. The project includes a simple Python script and demonstrates various Git concepts.

## Project Overview

This project serves as a sample repository for practicing Git workflows and commands. It includes:

- A Python script that prints different messages.
- Basic Git operations such as branching, merging, conflict resolution, amending commits, dropping commits, and squashing commits.

## Repository Structure

- `README.md`: This file, containing project information and instructions.
- `LICENSE`: A sample license file.
- `my-awesome-script.py`: A Python script with a series of print statements demonstrating different messages.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**

    ```bash
    git clone https://github.com/your-username/my-exciting-project.git
    ```

2. **Navigate to the Project Directory**

    ```bash
    cd my-exciting-project
    ```

3. **Check Out the `develop` Branch**

    ```bash
    git checkout develop
    ```

4. **View the Python Script**

    Open `my-awesome-script.py` to see the content of the script. The script starts with a basic print statement that was modified in different branches.

## Branches and Workflow

This project follows GitFlow, a branching model for Git:

- **`master`**: The main branch containing the production-ready code.
- **`develop`**: The development branch where features are integrated.
- **`feature/*`**: Feature branches for adding new functionality.

### Key Branches:

- **`feature/initial-setup`**: Initial setup with `README`, `LICENSE`, and the basic Python script.
- **`feature/enhancement-1`**: Contains a modified print statement: "Howdy, World!".
- **`feature/enhancement-2`**: Contains another modification to the print statement: "Hajimemashite sekai!".
- **`feature/next-awesome-thing`**: Includes an additional comment in the Python script, with amendments and dropped commits.
- **`feature/part-1-finale`**: Contains squashed commits with final print statement modifications.

## Git Commands Used

Here are some Git commands used in this project:

- **Creating Branches:**

    ```bash
    git checkout -b develop
    git checkout -b feature/initial-setup develop
    ```

- **Merging Branches:**

    ```bash
    git checkout develop
    git merge feature/initial-setup
    git checkout master
    git merge develop
    ```

- **Resolving Merge Conflicts:**

    Conflicts were resolved by editing the affected files and committing the changes.

- **Amending Commits:**

    ```bash
    git commit --amend
    ```

- **Dropping Commits:**

    ```bash
    git reset --hard HEAD~1
    ```

- **Squashing Commits:**

    ```bash
    git rebase -i HEAD~3
    ```


## Contributing

Feel free to fork the repository, make changes, and submit pull requests. For any issues or suggestions, open an issue in this repository.


