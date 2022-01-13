# vscode-icons-js

A forked project from [vscode-icons-js](https://github.com/dderevjanik/vscode-icons-js) by [Daniel Derevjanik
](https://github.com/dderevjanik)

## Changes
  * Removed log4js

## Installation

`npm i @abibv/vscode-icons-js`

## Usage

* To use in your project, download or clone this repo [vscode-icons](https://github.com/vscode-icons/vscode-icons), then copy the `icons/` folder to your project directory.

* Add the path to the `icons/` folder before the filename

```typescript
import { getIconForFile, getIconForFolder, getIconForOpenFolder } from '@abibv/vscode-icons-js';

const file = `/path_to_the_icons_folder/${getIconForFile('main.cpp')}`;
console.log(file);
// /path_to_the_icons_folder/file_type_cpp.svg
```

## Example from source repo

https://dderevjanik.github.io/vscode-icons-js-example/

Source Code:
https://github.com/dderevjanik/vscode-icons-js-example

## Related

- [vscode-icons](https://github.com/vscode-icons/vscode-icons) extension for vscode
- [github-vscode-icons](https://github.com/dderevjanik/github-vscode-icons) extension for chrome, which shows vscode-icons icons in github repository
- [vscode-icons-js-example](https://github.com/dderevjanik/vscode-icons-js-example) example
