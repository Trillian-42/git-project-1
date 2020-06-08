Overview of the Project:
Following completion of this project, the students will demonstrate the following skills:

Create a new local project that includes Readme and gitignore.

Commit local project to local repo using CLI

Initialize remote Github repo & set upstream & point local project to remote Github repo

Push local project to remote Github repo via CLI

Set user permissions in Github to allow other users to push to Github repo.

Demonstrate how multiple users can work on the same remote Github project via cloning, checkout and creation of new feature branch.

Demonstrate how multiple users can submit their feature branch changes back to the remote Github repo using pull request to merge feature branch to master branch.

Demonstrate how multiple users can merge pull requests and resolve merge conflicts by using the UI-based diff tool to pick changes from conflicting branches and by using the merge strategies:

fast-forward
no fast-forward
Squash

Requirements to run the Project:
Text-editor of your choice w/console access.
git
git-bash
possibly terminal access

How to run the Project:
**Please Note--I have changed the language from Python to vanilla Javascript (ES6)
Project Instructions:

User1 -> Demo Setup of new project (git cli — no ui)

Initialize new project

Add a simple helloworld.py file that prints "Hello World!"  (You can keep the files prepared for the demo to save time)

Add a simple Readme that line overview

Overview of the project

Requirements to run the project

How to run the project ?

Ensure following files are ignored (.gitignore)

*.pyc file

All files in env folder

Commit all files

Create an empty repository in GitHub

Create upstream for your project to point to github

Push changes to github

Add permissions for another user to push to GitHub

User 2> Clone project locally  and submit PR (git cli)

Clone the project created in initial setup

Checkout and create a new branch (feature1)

Change "Hello World!" In helloworld.py to "Hello My World!"

Commit changes.  Submit PR from feature branch to master branch.

User 1> Creates a new branch with changes to same file

Clone the project created in initial setup

Checkout and create a new branch

Change "Hello World!" In helloworld.py to "Hello Big World!"

Commit changes.  Submit PR from feature branch to master branch.

User 1 merges original PR submitted by User 2 using "Merge Commit: —no-ff" Strategy (no fast forward)

User 2>

Show the GitHub with conflicts from master branch

Pull the changes from origin/master and merge it on your feature branch

Configure merge tool to resolve the conflicts by using changes from both the branches. "Hello My Big World!"

Use UI based diff tool to show , how to resolve conflicts and pick changes from both branches.

Push changes to upstream to resolve conflicts

Merges the original PR using "Squash" Strategy.  ( merge it ,  but you squash all commit into single commit)

— Merge Strategies

Squash

Fast forward

No Fast Forward

Setup Demo for new project
Clone project locally and submit PR
Creates a new branch with changes to same file
Demo to handle conflicts , PR, Marge stratagies
