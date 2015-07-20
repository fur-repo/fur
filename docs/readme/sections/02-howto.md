Getting started
------

### Requirements

+ [node.js{{pkg.engines.node}}][nodejs_url]

### Installation

{{pkg.name}} is available as an [npm][npm_url] package.

```bash
# Install {{pkg.name}} as a global module.
$ npm install {{pkg.name}} -g
```

Or you can install it without `-g` option and use [Programmatic API](#programmatic-api).
For more details, see tutorial section "[01 - Installing fur][01_installing_fur_url]".


<a name="available commands" />
### Available Commands

```bash
$ fur -h
{{{usages.all}}}
```

<a name="programmatic-api" />
### Programmatic API

{{pkg.name}} provides programmatic API which enables you to execute {{pkg.name}} commands from Node.js program.

```javascript
var fur = require('fur');
fur.banner('my-banner.svg', {
    "text": "coz",
    "color": "o",
    "font": "aa",
    "style": "plain",
    "format": "svg"
}, function (err) {
});
```