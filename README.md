# Blender Involute Gear Extension

This is a simple addon to create geometrically correct (involute) gears in Blender.

Current features:
 - Straight gears.
 - Configurable resolution scale.
 - Full configurable parameters.
 - More to come...


Installing
----------
Simple Method, download the release ZIP.
* Option 1: Blender Edit -> Preferences... Then click the 'Add-ons' tab. In the top right
there is a dropdown arrow choose 'Install from Disk...' select the zip file. Blender will then
create a folder in the user extensions location with the correct name and enable Involute Gear ready for use.
* Option 2: If automatic installation fails, extract the zip to the correct folder depending on your
operating system. See [Blender Extensions Dir](https://docs.blender.org/manual/en/latest/advanced/blender_directory_layout.html)

Advanced technique: 
The super-awesome way is to directly symlink the Involute Gear folder from your git into
the extension folder. The advantage is that each `git pull` 
will download the newest version automatically.

Hit `Ctrl+,` to open up the Edit -> Preferences... Then click the 'Get Extensions'
tab. Involute Gear should show in the installed group if the directory/files have
been found. Then jump to the "Add-ons" tab and tick the square next to Involute Gear


Creating a Gear
---------------
* Before adding a Gear, make sure that large objects are not obstructing world origin and/or
3D cursor.
* From menu select 'Add' -> 'Mesh' -> 'Involute Gear'.
* The Scene Collection will have a new item called "Gear".
* An orange dot is now visible in the middle of the screen.
* Zoom in, use `Numpad .` to centre directly on the new object.


History
-------
A full list of changes can be found on [github](https://github.com/swtya/Blender-v4.2-involute-gear/pulls), and summarised in the
[Change Log](https://github.com/swtya/Blender-v4.2-involute-gear/blob/master/CHANGELOG.md) file.


Support
-------
This Add-on is offered as it is and maintained by the community, no support expected.
However, please raise an issue ticket on [github](https://github.com/swtya/Blender-v4.2-involute-gear/issues).

Enjoy.