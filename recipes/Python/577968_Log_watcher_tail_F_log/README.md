###Log watcher (tail -F *.log)

Originally published: 2011-11-29 18:31:01
Last updated: 2014-04-04 15:54:03
Author: Giampaolo Rodolà

A python class which "watches" a directory and calls a callback(filename, lines) function every time one of the files being watched gets written, in real time.