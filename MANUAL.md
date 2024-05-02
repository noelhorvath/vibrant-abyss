# Development manual

* [Source](#source)
* [Debug](#debug)
* [Build & Install](#build--install)

## Source

* This folder contains all of the files necessary for `Vibrant Abyss` color theme
  extension.
* `package.json` - this is the manifest file that defines the location of the
  theme file and specifies the base theme of the theme.
* `themes/vibrant-abyss-color-theme.json` - the color theme definition file
  specified
  in `package.json`.
* `assets/icon.img` - the icon of the extension specified in `package.json`.

## Debug

* Press `F5` to open a new window with the extension loaded.
* Open `File > Preferences > Color Themes` and pick the color theme.
* Open a file that has a language associated. The languages' configured grammar
  will tokenize the text and assign 'scopes' to the tokens. To examine these
  scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from
  the `Command Palette` (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).
* Changes to the theme file are automatically applied to the
  `Extension Development Host` window.

## Build & Install

* Run `yarn install` to install the project dependencies.
* Create an extension package with `yarn build`.
* Install the generated `.vsix` file via `code --install-extension vibrant-abyss.vsix`.
