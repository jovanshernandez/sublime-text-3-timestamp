# sublime-text-3-timestamp

![Settings Window](https://github.com/jovanshernandez/sublime-text-3-timestamp/blob/master/timestamp-screenshot.png)

## Python plugin for Sublime Text 3 for inserting a timestamp

From the top Toolbar: Tools > New Plugin

Paste in the contents of "timestamp.py"

Save as timestamp.py in ~/Library/Application Support/Sublime Text 3/Packages/User/ (should be the default directory that pops up when you save)

Choose: Sublime Text 3 > Preferences > Key Bindings - User

Add:... 

{ "keys": ["super+ctrl+t"], "command": "timestamp" } 

...to make command+ctrl+t perform the insertion.

Make sure to add a comma after the previous keymap entry, if present.
