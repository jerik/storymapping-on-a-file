# Readme

**The aim of this project is to have an easy to use tool to do story mapping on a simple (draft) level.**

## Spark plug for this project
In my case the developer team works often with [jira](https://www.atlassian.com/software/jira) regarding user
stories, bugs, etc. To get an overview I used to do story mapping with post-it notes on a wall. But not always a
wall is available :(. Furthermore, at some point, you have to transfer your real-world post-it notes to jira-tickets. This is in some way bothersome. 

I search for a way to make the story mapping digital plus get rid of the manual typewriting to get jira-tickets. And
  here we are :). Have a look *(with Google Chrome)* at [storymapping-on-a-file.html](https://jerik.github.io/storymapping-on-a-file/storymapping-on-a-file.html)

This project is based on: https://webkit.org/demos/sticky-notes/ and currently **only supports the Google Chrome browser.**

## Convention 
This tool should always be only one single file which must work offline. Javascript libraries should be avoided to keep it small and simple. 
- Just download and start (adding notes or import a [textfile](https://raw.githubusercontent.com/jerik/storymapping-on-a-file/master/example-stories.txt) with stories)
- No worries regarding business compliance
- No worries regarding (technical) dependencies *(if you use Google Chrome)*

## Change log
### 2020-02-28
- Create a new note with hitting 'Numpad add' 

# Todo
1. Additional export to a file that keeps position, zindex, etc. Still in a human readable form
1. Additional import of a file that restores position, zindex, etc
1. Select several notes in a easy way, e.g. drag a rectangle with the mouse over the desired notes. or select with shift + click ...
1. Change colors of notes (shall work on one note or on all selected notes)
1. Extend work sureface on the left und top. At least the space of a note shall be available in all directions
1. Top bar with the buttons (New Note, Clear, ...) shall be available always, independet where I am on the work sureface (e.g. I have scrolled to the left and down)
1. Duplicate/clone a selected note (perhaps with a keyboard shortcut, e.g. Ctrl + d)
1. DB shall be created file-specific. Otherwise does two different html pages query the same databse... 
1. newNote should be created near arround the mouse-pointer
