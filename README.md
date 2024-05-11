# DX9WARE Snippets for Lua

This VSCode extension adds snippets for DX9WARE Lua. Currently has support for all major functions, and some undocumented functions.

Here is a horrible demo as I do not know what to demo! If anyone would like to contribute a good demo please go ahead!

![](/assets/demo.gif)

Created and Maintained by RobloxArchiver. The git is OPEN to contributions! In the event you find a issue or get errors, make a Issue! If you want to add code of course make a pull whenever!

# Installation

There are multiple ways to get `dx9lua`. Pick your own flavor!

## VSCode Marketplace

`dx9lua` is available on the VSCode Marketplace!

![](/assets/vsc_download.png)

## GitHub releases

A prebuild binary can be downloaded from GitHub Releases!

Step 1: Download the latest build from the GitHub repository.

![](/assets/github_release_installation_1.gif)

Step 2: Open VSCode and go to the Extenstions tab. Click the 3 dots and click `install from .vsix`. Go to your downloads folder and double click the binary you just installed.

![](/assets/github_release_installation_2.gif)

## Build

You can also just build it yourself.

Requirements
- [`node.js`](https://nodejs.org/en/)
- [`vsce`](https://github.com/microsoft/vscode-vsce)

Step 1: Go to the GitHub repository, and click on the green `Code` dropdown button and click `Download ZIP`.

![](/assets/build_installation_1.gif)

Step 2: Extract it to Desktop.

![](/assets/build_installation_2.gif)

Step 3: Open the folder, open a command prompt and run the following.

```
vsce package
```

![](/assets/build_installation_3.gif)

Step 4: Copy the path of the folder you made the build in and open VSCode. Go to the Extensions tab and click the 3 dots, then click `install from .vsix`. Paste in the path you copied, and open the build file. Now dx9lua should now be installed and ready for use!

![](/assets/build_installation_4.gif)

# Contributors

- supg (Gave a list of undocumented functions to add)
- 6660/Alleexxi