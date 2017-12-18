## End-to-End Scenario

**First time**
* clone your local repository
* execute init job to customise the order of items  and the template of sidebar menu (ex: add a logo)

**Repeat**
* execute the job with default options with automatic promotion to origin repository

![Generate custom GitHub wiki sidebar with order and custom template](https://raw.githubusercontent.com/wiki/adriantanasa/github-wiki-sidebar/images/generating-github-wiki-sidebar-order-and-template.png)

## Actions

If installed globally and the npm bin path is in your $PATH variable just call the github-wiki-sidebar from within your local wiki folder:

```
# this will generate _Sidebar.md with default options
github-wiki-sidebar
```

Executing in tutorial mode (step by step) - allow user to generate sidebar with customized settings:

```
github-wiki-sidebar --action=tutorial
```

Executing in init mode (step by step) - allow user to generate an option.json file with customized settings that will be picked up on next execution.

```
github-wiki-sidebar --action=init
```

The "git-push" mode is also pushing the updated \_Sidebar.md file to your \<project\>.wiki repository given you have access to push.

```shell
github-wiki-sidebar --git-push
```