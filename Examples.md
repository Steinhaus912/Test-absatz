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