# sublime-text-3-timestamp

![Settings Window](https://github.com/jovanshernandez/sublime-text-3-timestamp/blob/master/timestamp-screenshot.png)

## Python plugin for Sublime Text 3 for inserting a timestamp

1.From the top Toolbar: Tools > New Plugin

2. Paste in the contents of "timestamp.py"

3. Save as timestamp.py in `~/Library/Application Support/Sublime Text 3/Packages/User/` (should be the default directory that pops up when you save)

4. Choose: Sublime Text 3 > Preferences > Key Bindings - User

5. Add:... 

`{ "keys": ["super+ctrl+t"], "command": "timestamp" }` to make command+ctrl+t perform the insertion.

NOTE: Make sure to add a comma after the previous keymap entry, if present.
