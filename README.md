# Description: Moving Git Branch from "master" to "main"

This code snippet demonstrates how to rename the default branch from "master" to "main" in a Git repository and push the changes to the remote repository. This is a common practice to replace the outdated term "master" with a more inclusive term like "main".

## Steps:

1. **Checkout the "master" branch:**
   The code starts by ensuring that the user is currently on the "master" branch.

2. **Rename the branch to "main":**
   Next, it renames the current branch from "master" to "main" using the `git branch -m` command.

3. **Push the renamed branch to the remote repository:**
   Finally, it pushes the changes to the remote repository using `git push -u origin main`. This creates the "main" branch on the remote repository and sets up tracking.

## Usage:

To use this code:
1. Navigate to your local Git repository in your terminal.
2. Copy and paste each command into your terminal and execute them sequentially.

## Note:
- Before running these commands, ensure that you have the necessary permissions to rename branches and push changes to the remote repository.
- It's always recommended to backup your repository or work on a copy before making significant changes like renaming branches.

