# First Contribution

This repo aims to create a simple to-do list application suitable for beginners in both programming and open-source contributions. The application will have basic features like adding tasks, marking them as complete, and deleting them.

## Table of contents

- Fork this repository

- Clone the repository

- Create a branch

- Make necessary changes and commit those changes

- Push changes to GitHub

- Submit your changes for review

- Contributors

# just for the instructions!

## Install github

Do you have github desktop in your local machine if not then istall it from here: [install it](https://help.github.com/articles/set-up-git/).

## Fork this repository

when do install github then open this repo and fork this repository by clicking on the fork button on the top of this page.This will create a copy of this repository in your account.

<img align="center" width="300" src="assets/fork.png" alt="fork this repository" />

## Clone the repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the _copy to clipboard_ icon.

<img align="center" width="300" src="assets/clone.png" alt="clone this repository" />

- Open a terminal and run the following git command:

  - git clone "URL you just copied"

    For example:
    git clone https://github.com/this-is-you/first-contributions.git

    - where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository in GitHub to your computer.

    <img align="center" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

## Create a branch

#### Change to the repository directory on your computer (if you are not already there):

cd first-contributions

#### Now create a branch using the `git checkout` command:

```
git checkout -b <add-your-new-branch-name>
```

##### For example:

- git checkout -b add-muhammad

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open `contributions.yml` file from `_data` directory in a text editor, add your name with emoji of your country flag, github_account and profile picture URL (avatar) to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

If you go to the project directory and execute the command `git status`, you'll see there are changes.

- Add those changes to the branch you just created using the `git add` command:

```
git add _data/contributions.yml
```

- Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors list"
```

- replace `<your-name>` with your name.

<img align="center" width="450" src="assets/git-status.png" alt="git status" />
