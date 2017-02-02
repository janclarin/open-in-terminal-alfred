# Open in Terminal Workflow for [Alfred 3](https://www.alfredapp.com/)

Allows you to search for a folder in Alfred, open a terminal instance, and `cd`
into the selected folder in one step.

**[DOWNLOAD](https://github.com/janclarin/open-in-terminal/releases/download/1.0/open-in-terminal.alfredworkflow)**

<img src="https://raw.githubusercontent.com/janclarin/open-in-terminal/master/screenshots/screencast.gif" width="480">

Note: Terminal/iTerm does *not* have to be open before running this command.

## Usage
Type `cd` into Alfred followed by the folder that you want to open in Terminal.

## iTerm2 support
By default, Alfred will use Terminal.app when running terminal commands via
workflows. This must be changed within Alfred's preferences to open iTerm2.  
To do so, follow these instructions copied from
[iTerm2's support page](https://www.iterm2.com/version3.html):
> Go to Alfred Preferences and choose Features.
> Pick *Terminal / Shell* and for *Application* choose *Custom*.
> Then paste the [iTerm2 3.0 Alfred Script](https://gist.githubusercontent.com/gnachman/4cbe6743baa7fe07536b/raw/61fceba4a0b2624850ac1b4a20ac8ca48e07f7d2/gistfile1.txt)
> into the text field.
> [Perhaps a crude illustration will help.](https://www.iterm2.com/images/AlfredForiTerm2Version3.png)
