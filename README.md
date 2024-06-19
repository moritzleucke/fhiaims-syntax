# FHIaims-syntax highlighting 

FHIaims syntax highlighting for `control.in` and `geometry.in` files in VS Code.

This extension is not officially released by FHIaims. I was just tired uncolored input files.

## Features
Simple syntax highlighting like:

![control.in file](https://github.com/moritzleucke/fhiaims-syntax/blob/main/images/control.png?raw=true)
![geometry.in file](https://github.com/moritzleucke/fhiaims-syntax/blob/main/images/geometry.png?raw=true)


## Known Issues

Spell checking of the keywords is not supported so far (but planned). Up to know the first word in every line is just highlighted independent of the right spelling. 

## Install 
run in root directory of the repository:
```
vsce package 
```
To start using the extension with Visual Studio Code copy `fhiaims-syntax.vsix` into the `<user home>/.vscode/extensions/` folder and restart Code.


