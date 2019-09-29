# Sublime GotoLastEditEnhanced plugin

Replacement for default sublime goto last edit (or not default but I've used
some goto last edit before I did this plugin).


### Demo

![Demo](https://github.com/shagabutdinov/sublime-enhanced-demos/raw/master/goto_last_edit_enhanced.gif "Demo")


## Installation

### By Package Control

1. Download & Install **`Sublime Text 3`** (https://www.sublimetext.com/3)
1. Go to the menu **`Tools -> Install Package Control`**, then,
   wait few seconds until the installation finishes up
1. Go to the menu **`Tools -> Command Palette...
   (Ctrl+Shift+P)`**
1. Type **`Preferences:
   Package Control Settings – User`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
   add the following setting to your **`Package Control.sublime-settings`** file, if it is not already there
   ```js
   [
       ...
       "channels":
       [
           "https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json",
           "https://packagecontrol.io/channel_v3.json",
       ],
       ...
   ]
   ```
   * Note,
     the **`https://raw...`** line must to be added before the **`https://packagecontrol...`**,
     otherwise you will not install this forked version of the package,
     but the original available on the Package Control default channel **`https://packagecontrol...`**
1. Now,
   go to the menu **`Preferences -> Package Control`**
1. Type **`Install Package`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
search for **`GotoLastEditEnhanced`** and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


### Features

Goto last edit in view. Keeps history of edits and allows to navigate through it.


### Usage

Hit keyboard shortcut to go to last edit. Hit keyboard shortcut several times to
go to last edit before last edit and etc.


### Commands

| Description    | Keyboard shortcuts | Command palette                      |
|----------------|--------------------|--------------------------------------|
| Goto last edit | alt+z              | GotoLastEditEnhanced: Goto last edit |
| Goto next edit | alt+shift+z        | GotoLastEditEnhanced: Goto next edit |


### Dependencies

None


## License

See the `LICENSE` file under this repository.

