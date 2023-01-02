# Python Auto Printf

A Quick Command to generate Python print out log messages utilizing f-string in Visual Studio Code.
A fork from [Python-Quick-Print](https://marketplace.visualstudio.com/items?itemName=AhadCove.python-quick-print)

## Installing

This extension is available for free in the Visual Studio Code Marketplace

## Warning :warning:

This uses Python 3 syntax, If you're using Python 2 print isn't a function.
You can import this behavior from __future__:

`from __future__ import print_function`

## How to use

### ONLY WORKS WITH .py FILES

* Highlight anything in vs code
* For MAC press `⌘+Shift+L`
* For Windows, etc press `Ctrl+Shift+L`
* The output, on a new line, will be: `print(f'variable: {variable}')`

### Editing Keyboard Shortcut

By default the keyboard shortcut is `⌘+Shift+L` or `Ctrl+Shift+L`
If this shortcut interferes with another extension or system wide Shortcut, you may change it in the `Keyboard Shortcuts Setting`.

Press `⌘+P` or `Ctrl+P` and type in `Open Keyboard Shortcuts`.
Search for `Print Python Selection` and click on the `pen icon`.
This is where you can enter any `Shortcut` you choose.

## License

[MIT License](LICENSE)
