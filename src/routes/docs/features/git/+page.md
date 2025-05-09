---
title: Git integration
---

## Using Git in Files

The Git integration in Files is designed to make it easier to work with your project. The integration displays useful information about the current branch and commit details on the Status Bar, support for creating and switching branches, and Git columns in the Details layout.

### Connecting to Github

Connecting to Github allows you to push and sync changes with remote repositories. Files will prompt and display instructions when authorization is required.

### Creating and switching branches

The current branch name will displayed on the Status Bar. To create a new branch, click the branch name to open the Branches flyout and click the "Create" button. To switch branches, open the "Branches" flyout and select the branch you want to checkout.

### Push, pull, and sync changes from a remote repository

The number of local and remote commits will be displayed on the Status Bar. To push or pull commits from a remote repo, click on the commit count and select the push or pull option. Syncing with the remote repo will update the commit number on the status bar without taking any actions.

### Git columns in the Details layout

The Details layout will display additional columns for Git status, last commit, commit hash, and commit author. These columns can be toggled by right-clicking the column headers.

### Git details in the Details pane

The Details Pane will display the repository name and current checked out branch in the Details Pane.

### Opening a Git repository in VS Code (or your IDE of choice)

When browsing a Git repository, the Status Bar will show an option to open the current folder in your selected IDE. The default IDE can be changed from the dev tools settings page.

### Cloning repositories from GitHub

Repositories can be cloned from GitHub with 'Clone' action. The simplest method is to drag and drop the repository URL from your browser into Files. You can also access this feature through the [Command Palette](/docs/features/command-palette/) or assign it a custom keyboard shortcut via the actions [settings page](/docs/customize-settings/actions/).