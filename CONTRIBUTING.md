Contributing Guide
==================

Thank you for investing you time in contributing to [flow-app-scafold](https://github.com/flyinglimao/flow-app-scaffold)!

Getting Started
---------------

### Adding a new template
Before you add a new template, please open an issue in advance and introduce the template.

To add a new template in a sub-project, fork and clone this repo.
```bash
# after forking the repo
git clone git@github.com:<your-username>/flow-app-scaffold.git
```

Create a new folder under api/cadence/web with your template name.
```bash
cd api # or cadence/web
mkdir <new-template-name>
```

Add some files to the folder and commit them into your repo.
```bash
cd <new-template-name>
cp -r /path/to/template/* .
git add .
git commit
```

Open a pull request on GitHub and link the PR to the issue.

Adding a new example
--------------------
Before you add a new example project, please open an issue in advance and introduce the project.

If your project is a complete app, put whole project in example instead. Your project should follow [the scaffold](https://github.com/onflow/example-projects/tree/master/full-stack-basic).
```
git clone git@github.com:<your-username>/flow-app-scaffold.git
cd example
cp -r /path/to/app .
git add .
git commit
```

Open a pull request on GitHub and link the PR to the issue.

Modifing a existing project
---------------------------
To modify a existing project, fork and clone this project and commit changes. Then, open a pull request on GitHub and describe the changes.