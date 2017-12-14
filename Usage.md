* [Tutorial mode](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Usage%3A-Tutorial-mode)
* [Init mode](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Usage%3A-Init-mode)
* [Command line modifiers](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Usage%3A-Command-line-modifiers)

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