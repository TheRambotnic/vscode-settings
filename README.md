# Visual Studio Code Settings
These are the settings, keybinds, extensions and snippets that I use for Visual Studio Code.

## Extensions (REQUIRED)
Some settings require these extensions to be installed beforehand:
* [Sublime Text Keymap and Settings Importer](https://marketplace.visualstudio.com/items?itemName=ms-vscode.sublime-keybindings)
* [SQL Server (mssql)](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql)
* [open in browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)
* [Selected Lines Count](https://marketplace.visualstudio.com/items?itemName=gurumukhi.selected-lines-count)
* [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
* [Discord Presence](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode)

## For Windows users
After downloading the files, place them in `%appdata%/Code/User/`.

## For Linux users
After downloading the files, place them in `home/YourUserName/.config/Code/User`.

## Keybindings
If you'd like to know the keybinds available, you can open `keybindings.json` which contains comments 
explaining what each keybind do.

## Settings
* **Encoding type**: UTF-8
* **Font family**: Consolas
* **Word wrap**: OFF
* **Multi cursor modifier**: CTRL (Windows and Linux) / COMMAND (Mac)
* **Font size**: 12px
* **Auto indent style**: advanced
* **Startup behavior**: start with blank editor
* **Color scheme**: Monokai (with green-colored comments)
* **Workspace Trust prompt**: OFF

If you're running VS Code on Linux, open `settings.json` and uncomment line 3 and comment line 4. This will 
make the editor use Ubuntu Mono as the default font.

Alternatively, if you don't want to mess with the file, you can download the Consolas font family [here](https://www.fontpalace.com/font-download/consolas/).