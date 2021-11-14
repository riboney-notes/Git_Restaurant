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

- "Prep" by pasting the ingredients for meals into the `prep/ingredients.md`
  - **REQUIREMENT**: no missing or repeating ingredients
- Create directory for the mealtypes and create the meals:
  - By copying/pasting from `prep/recipes.md` into `<meal-name>.md` under the appropiate directory
- Put the names of the meals being served
- Put names of all members in `serve.md` under **CHEFS**

### Git "exercises"

- Observe commit history at the end of project
- Use `rebase` and `squash` and view how it changes commit history
- Fix merge conflicts and explore different tools for resolving conflicts
- Use `git diff` and explore different tools for viewing `git diff`
