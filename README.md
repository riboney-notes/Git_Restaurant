# Git Restaurant

## About

- This project is designed to expose its participants to various git workflows and features

## Prerequisites & Info

- Install git: [instructions](https://github.com/git-guides/install-git)
- Customize git & github: [instructions](https://kbroman.org/github_tutorial/pages/first_time.html)
- Clone git repository: [instructions](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)

### Project Goals

- [ ] Handle merge conflicts
- [ ] Get exposure to feature branching 
- [ ] Use tools such as gitdiff, gitgraph, etc
- [ ] Learning to read and understand git logs
- [ ] Modifying commit history with git rebase and git squash 
- [ ] Being able to revert changes with git

## Project Description

- **Main idea:** work text files to simulate working with code and real-life development scenarios
   - *WHY*: allows anyone to participate regardless of their coding experience
- **What**: Participants will be creating a *Three course meal* or *Breakfast, Lunch, and Dinner* 🍽
   - *How*: pushing commits each meal's folder
      - Commits will contain: ingredients, cooking steps/actions, pictures
- **Potential tasks**: 
   - *Scenario*: A recipe for a meal needs to be changed 
      - *Reason*: Changing app requirements during development
      - *Outcome*: Get exposure to creating git issues and handling it with feature branching workflow
   - *Scenario*: Have two people team up like Remy and Alfredo from Ratatouille on the same meal
      - *Reason*: Have members work on the same file and push commits at the same time to create merge conflicts 
      - *Outcome*: Learning to handle merge conflicts and sync with `main` when merging commits
   - *Scenario*: Investigate the source of a food poisioning 
      - *Reason*: Analyzing commit history to find which commit was responsble for the "poison"
      - *Outcome*: using the `git log` and using `git graph`  
   - *Scenario*: Customer hates the meal and sends it back
      - *Reason*: Remove recent merges into git main 
      - *Outcome*: Learning to revert commits and bring back codebase to an earlier version 
