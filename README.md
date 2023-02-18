# autumnal-theme README

## Building the .vsix extension

$ npm install

This should install all you need to build, including the vsce project.

$ vsce package

When prompted, don't worry about the repository entry in package.json.

## Installing the extension to vscode

$ code--install-extension ./autumnal-theme-0.0.1.vsix
