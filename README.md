# MaskedCarnivale

**MaskedCarnivale** allows you to record, or stream your game without displaying Dalamud plugins.

The plugin creates a second window in the background which can be recorded using software like OBS.

Optionally you can also have the window display the game without a UI at all, so you can take immersive recordings.

The plugin menu can be displayed by typing /carnivale in chat or by using /carnivale enable or /carnivale disable to start or stop the window.

## Testing exclusive
This plugin is testing exclusive. You must enable plugin testing before you can install it. To do so, follow this set of instructions:

1. Go to `/xlsettings`
2. Go to "Experimental" tab
3. Enable "Get plugins testing builds" checkbox
4. Save settings by pressing a :floppy_disk: button in bottom right corner of the window

Now you can proceed to install the plugin.

## Known issues
Gamma should be set to any value other than 50 for mode with UI to work. 

**Please note**:

This plugin only hides overlay plugins, plugins which actually modify the contents of the game still will be visible.

For example the dalamud menu itself would be hidden but the dalamud button on the escape menu would still show up and thus it is advised to disable it in the dalamud settings.

Plugins such as penumbra, cammy, and the tweaks allowing you to change the layout of the castbar would still be visible.


To display a mouse cursor enable software cursor ingame, though most streamers currently dont show their cursor anyway.

To move the window use the XY offset in the plugin menu.

The UI can be hidden in the plugin menu.

The plugin menu can be displayed by typing /carnivale in chat.

Have fun streaming the game without suffering bad QoL and horrid latency!

4: Click on the Save icon button at the bottom right side of the window.


The plugins should now be available under All Plugins in the Plugins Installer window, accessable via the button/menu or typing /xlplugins.

## This plugin is in development
This means that there are still features that I would like to implement in future or features that I would like to enhance, as well as that I'm accepting suggestions and feature requests.
## Installation
1. Install [FFXIVQuickLauncher](https://github.com/goatcorp/FFXIVQuickLauncher?tab=readme-ov-file#xivlauncher-----) and enable Dalamud in it's settings. You have to run the game through FFXIVQuickLauncher in order for any of these plugins to work.
2. Open Dalamud settings by typing `/xlsettings` in game chat.
3. Go to "Experimental" tab.
4. Find "Custom Plugin Repositories" section, agree with listed terms if needed and paste the following link into text input field: `https://github.com/NightmareXIV/MyDalamudPlugins/raw/main/pluginmaster.json`
5. Click "Save" button.

You should now have NightmareXIV plugins available in your plugin installer. <br>
Open plugin installer by typing `/xlplugins` in game chat, go to "Available plugins" section and search for a plugin you would like to install.

![image](https://github.com/NightmareXIV/MyDalamudPlugins/blob/main/meta/install/installer.png?raw=true)

## Support
Join NightmareXIV Discord server to receive support for this plugin: https://discord.gg/m8NRt4X8Gf
[![](https://dcbadge.vercel.app/api/server/m8NRt4X8Gf)](https://discord.gg/m8NRt4X8Gf)

The server operates on a ticket-based system. Please create a ticket and describe your issue.
Additionally, you may create an issue in the repository. Reply time for tickets may be significantly longer than on Discord, however, the issue does not have any risks to be lost.
(Basically, if you want to report a critical bug or receive help, prefer Discord, if you want to suggest feature or report non-critical bug, prefer Github)
