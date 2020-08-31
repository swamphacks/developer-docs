# Contributing @SwampHacks
Making clear and concise changes to projects is beneficial and helps save time. As a developer, SwampHacks expects you to follow these rules when contributing to any of the repositories under the organization. 

## Git Flow

> The master branch is protected – all commits must be made from a non-protected branch and submitted via a pull request.

When making changes, you should follow the task branching strategy outlined below:

1. Create a new branch based off of develop/master following the specified strategy (see **Branch Name Format** below).
2. Make changes and commits (see **Commit Name Format** below), but keep the changes specific to the feature/issue you are working on.
3. (see **PR Guidelines** below) When all of your changes are complete, make a pull request (PR) to develop/master and wait for review (note: before making a PR, ensure your branch is up-to-date with master).
4. Once your PR has been approved, proceed with merging to the main branch and resolving any merge conflicts.
5. Delete the source branch you created. It is no longer necessary to keep a branch after it has been merged.

For additional information on branching and general workflows, see [this](https://guides.github.com/introduction/flow/).

### PR Guidelines

1. Before creating a PR, make sure there is an issue on the repository related to the changes you made. If there is not an issue, create one.
2. When creating a PR, be sure to link the related issue to the PR.
3. Provide a brief overall description of the changes that you made in the body of the PR (~1 sentence). 
4. List out individual changes in a bullet-style list to provide a clear view of exactly what was changed.
5. Provide screenshots if relevant to improve the approval speed of the PR (mostly applies to frontend). 

### Branching Strategy
Branches should all follow a clear and consistent naming scheme, outlined below:

- **feat/<`feature-name`>** - used for developing new features, based off of **develop** branch
- **fix/<`fix-name`>** - used for fixing bugs, based off of **master** branch

### Commit Format
Commit styles should follow [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/). These styles are generally enforced using git hooks and should be used in every repo.
