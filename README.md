# vscode-glimmer

VSCode extension for glimmer js components.

## Features

### Syntax Highlighting
This extension adds supports for syntax highlighting inside hbs literal strings. It injects the grammar into the existing typescript and javascript grammars.

![](https://github.com/chiragpat/vscode-glimmer/raw/master/images/syntax-highlighting.png)

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




