
# add_date.py
With the add_date.py script one can make a shortcut to enter a date or a time. This scripts was found via [stackoverflow](http://stackoverflow.com/questions/11879481/can-i-add-date-time-for-sublime-snippet)

## Usage
Save it as ~/Library/Application Support/Sublime Text 2/Packages/User/add_date.py
(or one could create a symlink)

Then, in Preferences > Key Bindings - User , add:

{"keys": ["ctrl+shift+,"], "command": "add_date" }, {"keys": ["ctrl+shift+."], "command": "add_time" }, 

You can customize the argument passed to strftime to your liking.