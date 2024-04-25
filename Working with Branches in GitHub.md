## Introduction
Working with branches in Git and GitHub allows us to collaborate on projects, experiment with new features, and keep our main codebase stable. In this guide, we'll learn how to create branches, make changes, push branches to GitHub, create pull requests, and merge changes.

## Creating a Branch
To start working on a new feature or task, we create a new branch using the following command:

`git checkout -b my-new-feature`

This command creates a new branch named `my-new-feature` and switches us to that branch.

## Making Changes
Now that we're on our new branch, we can make changes to our code as needed. We can add new features, fix bugs, or make any other modifications.

## Committing Changes
Once we've made our changes, we commit them to our branch using the following commands:
`git add .`
`git commit -m "feat: Add new feature"`

Replace `"Add new feature"` with a brief description of the changes we've made.

## Pushing Branches to GitHub
To share our changes with others, we push our branch to GitHub using the following command:

`git push origin my-new-feature`

This command pushes our `my-new-feature` branch to our GitHub repository.

## Creating a Pull Request
Once our branch is pushed to GitHub, we can create a pull request (PR) to merge our changes into the main branch. We go to our repository on GitHub, switch to the `my-new-feature` branch, and click the "New pull request" button. Then, we select the main branch as the base branch and our `my-new-feature` branch as the compare branch. We write a description for our PR, review our changes, and then click "Create pull request".

## Reviewing and Merging
Our friend (or collaborator) can now review our changes in the pull request. They can leave comments, suggest modifications, or approve the changes. Once everything looks good, they can merge the pull request into the main branch.