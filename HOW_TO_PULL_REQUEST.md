# Git and GitHub Workflow Tutorial

## Table of Contents
1. [Cloning the Repository](#cloning-the-repository)
2. [Creating a New Branch](#creating-a-new-branch)
3. [Making Changes](#making-changes)
4. [Committing Changes](#committing-changes)
5. [Pushing Changes](#pushing-changes)
6. [Creating a Pull Request](#creating-a-pull-request)
7. [Naming Files and Components](#naming-files-and-components)

## Cloning the Repository
To get started, you need to clone the repository using SSH.

```bash
git clone git@github.com:HeimdallILVU/system_project_ENSEA.git
cd system_project_ENSEA
```

## Creating a New Branch
Always create a new branch for your work to keep the main branch clean and organized.

```bash
git checkout -b your_branch_name
```

## Making Changes
Make your changes in the newly created branch. Ensure that you follow the project guidelines and naming conventions.

## Committing Changes
Once you have made the necessary changes, commit them to your branch.

1. **Stage your changes:**

   ```bash
   git add .
   ```

2. **Commit your changes with a meaningful message:**

   ```bash
   git commit -m "Description of the changes"
   ```

## Pushing Changes
Push your changes to the remote repository on GitHub.

```bash
git push origin your_branch_name
```

## Creating a Pull Request
1. Go to the repository on GitHub: [GitHub Repository](https://github.com/HeimdallILVU/system_project_ENSEA)
2. Click on the "Compare & pull request" button next to your recently pushed branch.
3. Add a title and a detailed description for your pull request.
4. Assign reviewers if necessary.
5. Click on "Create pull request".

## Naming Files and Components
To avoid conflicts and ensure clarity, adhere to the following naming conventions:
- Use descriptive and unique names for files and components.
- Avoid using special characters and spaces. Instead, use underscores (`_`) or hyphens (`-`).
- Follow a consistent naming pattern (e.g., `feature_component_name`).

### Example:
```plaintext
Correct: frequency_transposer.schematic
Incorrect: Frequency Transposer@.schematic
```

### Summary
1. Clone the repository using SSH.
2. Create a new branch for your changes.
3. Make and commit your changes with clear messages.
4. Push your changes to GitHub.
5. Create a pull request and provide a detailed description.
6. Follow the naming conventions strictly to avoid conflicts.

By following these steps, you'll ensure a smooth workflow and maintain a clean and organized codebase.
```


