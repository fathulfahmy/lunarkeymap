# Change Log

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

- Set `enter` to accept suggestion by default

## v1.0.12 (28-12-2023)

**Fixed**

- `tab` can now be used to accept suggestion

**Changed**

- Removed `enter` to accept suggestion by default
- Removed `tab` to cycle suggestion
- Removed `shift+tab` to cycle suggestion

## v1.0.11 (13-07-2023)

**Fixed**

- `ctrl+e` is now handled by vscode and not vim

## v1.0.9 (12-07-2023)

**Added**

- demonsration GIFs
- paste from clipboard Which Key shortcut

## v1.0.8 (12-07-2023)

**Fixed**

- `tab` conflicts with terminal completion

**Changed**

- disabled vscode multiline editing via `ctrl+d` by default
- enabled vscodevim move page down via `ctrl+d` by default

## v1.0.7 (10-07-2023)

**Fixed**

- `ctrl+hjkl` not working

**Added**

- Dependencies will be uninstalled automatically upon lunarkeymap uninstallation

**Changed**

- `ctrl+a` is handled by vim
- `ctrl+f` is handled by vim
- `ctrl+c` is handled by vim
- `ctrl+x` is handled by vim
- `ctrl+z` is handled by vim
- `ctrl+y` is handled by vim
- `ctrl+n` to remove search highlight is removed

## v1.0.4 (09-07-2023)

**Changed**

- Changed extension name from `lunarkeymap` to `LunarKeymap`
- Visual Studio Code >= `1.74.0` is now supported

## v1.0.3 (08-07-2023)

**Fixed**

- Enabled `ctrl+v` to work as expected in vim

**Changed**

- Paste via `ctrl+v` is now disabled in normal mode
