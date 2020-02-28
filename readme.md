# Readme

**The aim of this project is to have an easy to use tool to do story mapping on a simple (draft) level.**

## Spark plug for this project
In my case the developer team works often with [jira](https://www.atlassian.com/software/jira) regarding user
stories, bugs, etc. To get an overview I used to do story mapping with post-it notes on a wall. But not always a
wall is available :(. Furthermore, at some point, you have to transfer your real-world post-it notes to jira-tickets. This is in some way bothersome. 

I search for a way to make the story mapping digital plus get rid of the manual typewriting to get jira-tickets. And
  here we are :) 

This project is based on: https://webkit.org/demos/sticky-notes/ and currently **only supports the Google Chrome browser.**

## Convention 
This tool should always be only one single file which must work offline.  
- Just download and start.
- No worries regarding business compliance
- No worries regarding (technical) dependencies

## Change log
### 2020-02-28
- Added key shortcut 'Numpad add' to create a new note in the current browser view

# Todo
1. Additional export to a file that keeps position, zindex, etc. Still in a human readable form.
1. Additional Import that restores position, zindex, etc.
1. Select several notes in a easy way, e.g. drag a rectangle with the mouse over the desired notes. or select with click + keydown shift?
1. Change colors of notes (shall work on one note or on all selected notes). 
1. Extend work sureface the left und top. At least 2x of a note space shall be available in all directions
1. Top bar with the buttons should be available always, independet where I am on the work sureface
1. Duplicate/clone a selected note (perhaps with a shortcut, e.g. Ctrl + d)
1. DB shall be created file-specific. Otherwise does two different html pages query the same databse... 
1. newNote should be created near arround the mouse-pointer
