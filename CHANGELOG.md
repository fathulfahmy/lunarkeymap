# Change Log

## v1.2.4 (07-03-2024)
**Added**
Notes on incompatibility with Neovim

## v1.2.0 (07-03-2024)

**Changed**

- GPL v3.0 to MIT License

**Fixed**

- `tab` cycle next editor
- `shift+tab` cycle previous editor

## v1.1.0 (07-03-2024)

**Changed**

- `ctrl+shift+t` toggle terminal to toggle or focus terminal
- `ctrl+space+t` to terminal menu (new, toggle, focus)
- `ctrl+space+T` to `ctrl+space+u` toggle UI menu
- `ctrl+space+b+Y` to `ctrl+space+y` copy buffer to clipboard
- `ctrl+space+d+d` to `ctrl+space+s` start debug

**Added**

- `d` delete file
- `p` paste file
- `x` cut file
- `y` copy file
- `ctrl+shift+h` increase editor size
- `ctrl+shift+l` decrease editor size
- `ctrl+space+?` view all references
- `ctrl+space+l` LSP menu (refactor, autofix, definition, declaration, format, symbol)
- `ctrl+space+o` open menu (directory, file, recent)
- `ctrl+space+p` peek menu (definition, declaration, implementation, reference)
- `ctrl+space+x` view vscode extension
- `ctrl+space+g+F` git pull from
- `ctrl+space+g+h` git history
- `ctrl+space+g+j` git next change
- `ctrl+space+g+k` git previous change
- `ctrl+space+g+P` git pull
- `ctrl+space+g+t` git create tag
- `ctrl+space+g+T` git delete tag
- `ctrl+space+w+c` to `ctrl+space+w+d` close editor group

**Removed**

- `ctrl+space+c` close current editor
- `ctrl+space+b+P` paste clipboard to buffer

## v1.0.13 (07-01-2024)

**Changed**

`tab` to `enter` to accept suggestion

## v1.0.12 (28-12-2023)

**Changed**

- `enter` to `tab` to accept suggestion

**Removed**

- `tab` to cycle suggestion
- `shift+tab` to cycle suggestion

## v1.0.11 (13-07-2023)

**Fixed**

`ctrl+e` is now handled by vscode and not vim

## v1.0.9 (12-07-2023)

**Added**

- demonsration GIFs
- `ctrl+space+b+P` paste from clipboard shortcut

## v1.0.8 (12-07-2023)

**Fixed**

- `tab` conflicts with terminal completion

**Changed**

- `ctrl+d` is now handled by vim and not vscode

## v1.0.7 (10-07-2023)

**Fixed**

- `ctrl+h` not working
- `ctrl+j` not working
- `ctrl+k` not working
- `ctrl+l` not working

**Changed**

- Dependencies will be installed/uninstalled automatically
- `ctrl+a` is now handled by vim
- `ctrl+f` is now handled by vim
- `ctrl+c` is now handled by vim
- `ctrl+x` is now handled by vim
- `ctrl+z` is now handled by vim
- `ctrl+y` is now handled by vim

**Removed**

- `ctrl+n` to remove search highlight is removed

## v1.0.4 (09-07-2023)

**Changed**

- Changed extension display name from `lunarkeymap` to `LunarKeymap`
- Visual Studio Code >= `1.74.0` is now supported

## v1.0.3 (08-07-2023)

**Fixed**

`ctrl+v` work as expected in vim
