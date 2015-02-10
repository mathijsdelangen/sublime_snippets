Save it as ~/Library/Application Support/Sublime Text 2/Packages/User/add_date.py

Then, in Preferences > Key Bindings - User , add:

{"keys": ["ctrl+shift+,"], "command": "add_date" },
{"keys": ["ctrl+shift+."], "command": "add_time" },
You can customize the argument passed to strftime to your liking.

From: http://stackoverflow.com/questions/11879481/can-i-add-date-time-for-sublime-snippet