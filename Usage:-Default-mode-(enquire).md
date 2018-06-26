## Options available in init/tutorial mode

**Define the category separator for multi-level menu: (: )**

Change the sequence to break titles into categories (default to ":-"). Users on Windows operating system have to choose a different separator for categories as the colon (:) is not accepted as a file separator.

**Define the format of the page links: (./%s)**

Allows the user to change the links to a different format (default is relative). A full URI could be used for ex:  ```https://github.com/adriantanasa/github-wiki-sidebar/wiki/%s```

**Define the _Sidebar.md content template: (%s)**

You can add markdown content before/after menu content - use this step to add for example a logo. The %s will be replaced with the content of the menu:

```
[![npm module\](https://rawgit.com/wiki/adriantanasa/gi
thub-wiki-sidebar/images/github-wiki-sidebar.svg)](https://www.npmjs.com/package/github-wiki-side
bar)\n\n%s
```

**Select the items to be excluded from menu: (Press \<space\> to select, \<a\> to toggle all, \<i\> to invert selection)**
Provides a checkable list with all the .md files available. Use SPACE to add items to the exlusion list. Checking a top category - ex: ```Categ1.md``` - will exclude all the subpages from the menu - as ```Categ1: Subpage1.md```, ```Categ1: Subpage2: Subsubpage1.md```

**Change the priority/order of the items in menu (ex: 3 4 0): n**

The list of local *.md files are displayed with numeric indexes - here you can specify in a space separated list the priority for them in the menu. By default, the script is looking for the position of Home.md (if any) in your local folder and adding it with the highest priority.
