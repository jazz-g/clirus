# Clirus
A tiny CLI RSS/Atom feed reader for the terminal.
clirus simply gets a list of feed urls, and keeps track of a multiple feeds and merges them into one feed.
It does this by keeping track of a queue object of n length and when the clirus script is run, it will output the titles of the articles in the queue.<br/>
Note: For the first time this is run, your feed will only have the first article from each feed, but as it updates, it'll add more articles until the queue becomes full.
Possibly problematic for feeds that update really fast like Reddit
This script is useful for desktop widgets.<br/>

I will be maintaining this script to the bare minimum so that it just works.

## Installing
Just clone the repository, and move the clirus.py script wherever you want. 

