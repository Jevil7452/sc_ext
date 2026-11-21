# Steam Client Extensions - TEMPORARY README
A project that restores VGui and brings in the latest APIs for the 2023-07-10 Steam client.

Enable Watch > Custom > Releases to know when a new release comes out.

A proper README will come once the project is finished.

# Installation

1. Install the 2023-07-10 Steam client and prevent it from updating itself.
2. Log in as usual
3. Download the latest sc_ext_package.zip from the Releases and overwrite the files.
4. Additionally, edit package\steam_client_win32.manifest and blank out the version entry.
5. Optionally, extract the contents of CEF 126.7z into bin\cef\cef.win7x64

# Updating 

Download the latest sc_ext_package.zip and replace all of the files.

# Configuration 

Read sc_ext.ini to know what all the settings are and what they do.

Create a new file called sc_ext_override.ini to actually configure them.

Example:
```[sc_ext]
force_args=-vgui -nofriendsui -dev -forcevguimarketing
universe_label=Public
vgui_library_software_art=1
vgui_library_video_art=1
```
This will not be required once developement concludes.

# Bugs 

Report them here in the Issues tab. Send the game if it is relevant, however if it is not a free game you'll most likely want to also upload the log file. Delete the old file and let it create a new one, reproduce the bug and upload it here.

You can also DM me on Discord (`krisskross1225#0`) however this option is NOT recommended.

# Source Code

For the time being, it's within the Tools folder of sc_ext_package.zip.

# Roadmap

Currently, pretty much all of the VGui dialogs, and the Downloads page have been restored. The VGui Game library is in a mostly functional state, however some more things need to be added.

After that, features such as the -no-browser flag will be restored, however most likely as a config flag inside of sc_ext.ini. 

Some other potential changes might be made too.

However, the VGui Login Dialog will NOT be restored.

# AI Disclosure 

Everything you see here in the repo apart from this README has been created with the help of AI. A proper human written README will come once the project is considered mostly finished.
