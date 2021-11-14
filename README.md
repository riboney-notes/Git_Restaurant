# Git Restaurant

## About

- This project is designed to expose its participants to various git workflows and features

## Setup

- Install git: [instructions](https://github.com/git-guides/install-git)
- Customize git & github: [instructions](https://kbroman.org/github_tutorial/pages/first_time.html)
- Clone this repository: [instructions](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)
  - NOTE: Clone into an *empty* directory. And make sure directory does not have a parent repository that is a git repository
  - NOTE: you can see whether a directory is git repository or not by enabling "view hidden files" options in your file manager
- Divide up people to *breakfast, lunch, dinner* groups
- Everyone will work on *serve.md* and *ingredients.md* together

## Centralized/ Main workflow

- This is the most basic workflow where there is only one branch that everyone commits directly into and uses to deploy to the production environment

## Feature Branch Workflow

- *WIP*

## Git workflow

- *WIP*

### Project Overview

- "Prep" all the ingredients required for the meals by pasting it into the `prep/ingredients.md` file
  - Decide as a group who commits what
  - There should be no missing or repeating ingredients
  - Ingredients should be numbered to make counting easier
- Groups will create and push directories named after the group they are assigned to
  - And create their respective meals by copying/pasting from `prep/recipes.md` into `<meal-name>.md` under the appropiate folder
- Once all meals are pushed to the repo, everyone will put their names in `serve.md` under **CHEFS** and also put the names of the meals being served.

### Git exercises

- Screenshot commit history at the end of project
- Re-do the project and use `rebase` this time
  - screenshot commit history and observe the differences
- Fix merge conflicts and explore different tools for resolving conflicts
- Use `git diff` and explore different tools for viewing `git diff`
