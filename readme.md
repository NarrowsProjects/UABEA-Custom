# UABEA — Personal Modifications
This repository contains personal modifications I made to UABEA for my personal use.

**This is not the official UABEA repository.**

For the original project, including the official source code, documentation, releases, and ongoing development, please visit:

**[nesrak1/UABEA](<https://github.com/nesrak1/UABEA>)**

Please refer to the original repository for the authoritative and current version of UABEA.

## Changes
### Dynamic Plugin Panel
I replaced the existing **Plugins** button with a panel that dynamically displays the plugins available for the currently selected asset type.

When an asset is selected, the panel determines which plugins are applicable to that asset and presents the available options directly in the interface. This removes the need to navigate through a separate plugin menu and makes asset-specific functionality more immediately accessible.

### Saving from the Info Window
I added functionality to allow users to save their changes directly from the **Info** window.

Previously, saving from the Info window required closing the window and then using the save functionality from the main menu. The modification adds a save option directly to the Info window, allowing changes to be saved without leaving the current view.