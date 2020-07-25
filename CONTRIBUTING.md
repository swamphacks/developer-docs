# Contributing @SwampHacks
Making clear and concise changes to projects is beneficial and helps save time. As a developer, SwampHacks expects you to follow these rules when contributing to any of the repositories under the organization. 

## Git Flow
SwampHacks follows a slightly modified version of Git Flow (no development branch). When making changes, you should follow the task branching strategy outlined below:

> Master is a protected branch – all commits must be made from a non-protected branch and submitted via a pull request

1. Create a new branch based off of master following the specified naming format (see **Branch Name Format** below).
2. Make changes and commits (see **Commit Name Format** below), but keep the changes specific to the feature/issue you are working on.
3. When all of your changes are complete, make a pull request (PR) and wait for review (note: before making a PR, ensure your branch is up-to-date with master).
4. Once your PR has been approved, proceed with merging to the main branch and resolving any merge conflicts.
5. Delete the source branch you created. It is no longer necessary to keep a branch after it has been merged.

For additional information on branching and general workflows, go [here](https://guides.github.com/introduction/flow/).

### Branch Name Format
Branches should all follow a clear and consistent naming scheme, outlined below:

- **feature/<`feature-name`>** => used for developing new features
- **hotfix/<`fix-name`>** => used for fixing bugs

### Commit Format
Commit styles should follow [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/). These styles are generally enforced using git hooks and should be used in every repo.
