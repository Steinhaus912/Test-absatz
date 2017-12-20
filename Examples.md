**[AngularJS Wiki](https://github.com/angular/angular.js/wiki)**

Configuration file:

```json
{
  "menu": {
    "item": "{{#levelRepeat}}  {{/levelRepeat}}* [{{{title}}}]({{{link}}})\n",
    "category": "{{#levelRepeat}}  {{/levelRepeat}}* {{#link}}[{{{title}}}]({{{link}}}){{/link}}{{^link}}{{{title}}}{{/link}}\n{{{subitems}}}",
    "category-1": "![AngularJS](https://angularjs.org//img/AngularJS-large.png)\n\n{{{subitems}}}\n"
  },
  "rules": {
    "order": [
      "Home.md",
      "Contribution:-Contribution-Checklist.md",
      "Dev-Guide:-Anti-Patterns.md",
      "Resources:-Training-Courses.md",
      "Design-discussions.md",
      "Projects-using-AngularJS.md",
      "FAQ.md"
    ]
  },
  "separator": ":-",
  "linkTemplate": "https://github.com/angular/angular.js/wiki/%s",
  "menuFile": "_Sidebar.md",
  "multilang": false,
  "menuOnly": true
}

```

**[ng-bootstrap Wiki](https://github.com/ng-bootstrap/ng-bootstrap/wiki)**

Configuration file:

```json
{
  "menu": {
    "item": "{{#levelRepeat}}  {{/levelRepeat}}* [{{{title}}}]({{{link}}})\n",
    "category": "{{#levelRepeat}}  {{/levelRepeat}}* {{#link}}[{{{title}}}]({{{link}}}){{/link}}{{^link}}{{{title}}}{{/link}}\n{{{subitems}}}",
    "category-1": "{{{subitems}}}\n\n![Bootstrap](https://ng-bootstrap.github.io/img/logo.svg)\n"
  },
  "rules": {
    "order": [
      "Home.md",
      "Why-Bootstrap-4-only?.md",
      "Contributions.md",
      "Upstream-issues.md",
      "What-qualifies-as-a-ng-bootstrap-directive-or--component?.md",
      "Roadmap.md"
    ]
  },
  "separator": ":-",
  "linkTemplate": "https://github.com/ng-bootstrap/ng-bootstrap/wiki/%s",
  "menuFile": "_Sidebar.md",
  "multilang": false,
  "menuOnly": true
}
```