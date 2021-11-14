# Contributing Guide

Thank you for investing you time in contributing to [flow-app-scafold](https://github.com/flyinglimao/flow-app-scaffold)!

## Getting Started

## Adding a new example

Before you add a new example project, please open an issue in advance and introduce the project. Your project should follow [the scaffold](https://github.com/onflow/example-projects/tree/master/full-stack-basic).

First fork and clone this repo.

```
git clone git@github.com:<your-username>/flow-app-scaffold.git
cd flow-app-scaffold.git
```

Then, add new git repo into the `examples.json`, the format should be like:

```json
{
    ... // existing projects
    "your-project-name": {
        "repo": "https://github.com/<your-username>/<your-project>.git",
        "branch": "main"
    }
}
```

Commit your change.

```
# edit examples.json
git add examples.json
git commit
```

Open a pull request on GitHub and link the PR to the issue.
