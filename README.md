# Custom System Builder Syntax Highlighting for VS Code

## Description

The
[Custom System Builder](https://gitlab.com/custom-system-builder/custom-system-builder)
extension was crafted to offer an enhanced coding experience when working with
the CSB language. It offers custom syntax highlighting, aiding developers in
understanding and writing code more efficiently.

## Features

- Syntax highlighting for tags `${...}$` and `%{...}%`.
- Embedded JavaScript syntax support between `%{...}%`.
- Embedded HTML tags syntax highlighting.

## How to Run in Debug Mode

1. Clone or download the extension repository.
2. Open the extension directory in VS Code.
3. Press `F5` to start the debugging mode. This will launch a new instance of VS
   Code with your extension running.
4. Open or create a `.csb` file to view the syntax highlighting in action.

## How to Compile the Extension

1. Ensure you have `vsce` installed globally: `npm install -g vsce`
2. In the extension directory, run: `vsce package`
3. This will produce a `.vsix` file which can be installed in VS Code.
4. To install the extension from the `.vsix` file, follow the steps mentioned in
   the previous section of this README.
