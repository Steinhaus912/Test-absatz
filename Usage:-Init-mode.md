# Options available in init/tutorial mode

**Customise the separator character(s) for multi-level menu:**

Change the sequence to break titles into categories (default to ":-"). Users on Windows operating system have to chose a different separator for categories as colon is not accepted as a file separator.

**Customize the internal links format: ./%s**

You may prefer a full path route ex:  ```https://github.com/adriantanasa/github-wiki-sidebar/wiki/%s```

**Select the _Sidebar.md content template: %s**

You can add markdown content before/after menu content - use this to add for example a logo. The %s will be replaced with the content of the menu:

```
[![npm module\](https://rawgit.com/wiki/adriantanasa/gi
thub-wiki-sidebar/images/github-wiki-sidebar.svg)](https://www.npmjs.com/package/github-wiki-side
bar)\n\n%s
```

**Change the priority/order of the items in menu (ex: 3,4,0): n**

The list of local *.md files is displayed with indexes - here you can specify in a coma separated list the priority for them in the menu. By default the script is looking for the position of Home.md (if any) in your local folder and adding it with highest priority.

