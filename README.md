# gmcp
Galaban's GMCP plugin

This plugin pulls in the extra data sent to the clieint and allows you to view it.  It was written for the Aardwolf mud and is a plugin for the MuschClient.


Usage:

    gmcp room:          Show the GMCP room data.
    gmcp exits:         View the standard 'exits' output with room ids

Setup:

    gmcp autoid:        Enable/Disable the room id when viewing the room.
    gmcp color <color>: Change the color of the GMCP output.

##Note

Make sure that this is installed in the Musclient's plugin directory, as it relies on the aardwolf_colors.lua script, which resides in the directory.

## To install
1. Download the raw file from github:
https://raw.github.com/galaban/gmcp/master/Galabans_GMCP_Plugin.xml
2. Place the raw file into your "plugins" directory.  This is fund in your Mushclient folder under /worlds/plugins.
3. Install the plugain in MushClient.  From the "File" menu, choose "plugins", then "Add".  Select the file and choose "OK".
