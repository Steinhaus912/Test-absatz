[![npm module](https://rawgit.com/wiki/adriantanasa/github-wiki-sidebar/images/github-wiki-sidebar.svg)](https://www.npmjs.com/package/github-wiki-sidebar)

Welcome to the github-wiki-sidebar wiki!

_This wiki is an example of organising your github wiki navigation in order to be used with the npm github-wiki-sidebar module to automatically generate a beautified wiki menu. You can get rid of your huge README.md files by breaking them in a project wiki with multiple pages._

# github-wiki-sidebar

Multi-level github wiki sidebar menu generator (\_Sidebar.md) from the filenames in the wiki repository 

![github wiki sidebar generated by github-wiki-sidebar](https://raw.githubusercontent.com/wiki/adriantanasa/github-wiki-sidebar/images/github-wiki-sidebar-generator.png)

Starting from a github wiki with the following pages:

```
Home
Installation
Roadmap
Usage
Usage: Command line modifiers
Usage: Init Mode
Usage: Tutorial Mode
```

This tool can automatically generate the sidebar file (_Sidebar.md) with the menu as:

  * [Home](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Home)
  * [Installation](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Installation)
  * [Usage](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Usage)
    * [Command line modifiers](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Usage%3A-Command-line-modifiers)
    * [Init mode](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Usage%3A-Init-mode)
    * [Tutorial mode](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Usage%3A-Tutorial-mode)
  * [Roadmap](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Roadmap)

The automatically generated code is:

```mardown
  * [Home](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Home)
  * [Installation](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Installation)
  * [Usage](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Usage)
    * [Tutorial mode](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Usage%3A-Tutorial-mode)
    * [Init mode](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Usage%3A-Init-mode)
    * [Command line modifiers](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Usage%3A-Command-line-modifiers)
  * [Roadmap](https://github.com/adriantanasa/github-wiki-sidebar/wiki/Roadmap)


[//]: # (generated by https://www.npmjs.com/package/github-wiki-sidebar)

```
