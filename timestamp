###Timestamp Plugin For Sublime Text 3

###Create new file and save as timestamp.py

import sublime, sublime_plugin
from datetime import datetime

class TimestampCommand(sublime_plugin.TextCommand):
  def run(self, edit):
    stamp = datetime.utcnow().strftime("%A %B %d, %Y | %H:%M:%S")
    for r in self.view.sel():
      if r.empty():
        self.view.insert (edit, r.a, stamp)
      else:
        self.view.replace(edit, r,   stamp)


