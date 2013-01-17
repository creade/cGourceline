cGourceline
===========

Live updating [Gource](http://code.google.com/p/gource/) from a git-svn repo

Add cGourceline to your project root then run: 
`sh cGourceline | gource --realtime --log-format custom -`

You can add other arguments to gource but `--log-format custom -` must be present (more details [here](http://code.google.com/p/gource/wiki/CustomLogFormat))

`sh cGourceline | gource --file-idle-time 0 --key --fullscreen --realtime --log-format custom -`'d look real nice on one of them plasma screens.

Caveats
-------

- Only works with git svn repos
- repo must be kept free of other changes
- Displays no commits from before running the script
