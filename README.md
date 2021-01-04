# vscode-glimmer

VSCode extension for glimmer js components.

## Features

### Syntax Highlighting

This extension adds syntax highlighting for embedded Glimmer templates in
JavaScript and TypeScript. It supports two types of embedded template syntaxes:

1. Template strings, using `hbs` to denote that they are Handlebars templates:

  ![template strings demo](https://github.com/chiragpat/vscode-glimmer/raw/master/images/template-string.png)

2. Template tags, using a custom `<template>` syntax

  ![template tag demo](https://github.com/chiragpat/vscode-glimmer/raw/master/images/template-tag.png)

It also adds support for the `.gjs` and `.gts` file extensions, which are
aliases to JavaScript and TypeScript respectively.

Note: Syntax highlighting for handlebars requires installing the [Handlebars VSCode extension](https://marketplace.visualstudio.com/items?itemName=andrejunges.Handlebars)

## Developing

### What's in the folder

* `package.json` - this is the manifest file in which you declare your language support and define the location of the grammar file that has been copied into your extension.
* `syntaxes/inline-hbs.json` - this is the Text mate grammar file that is injected into javascript and typescript languages.

### Get up and running straight away

* Press `F5` to open a new window with your extension loaded.
* Create a new file with a file name suffix matching either javascript or typescript.
* Verify that syntax highlighting works and that the language configuration settings are working.

### Make changes

* You can relaunch the extension from the debug toolbar after making changes to the files in the extension.
* You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.




