# bash-utilities

## Collection of bash scripts for simple tasks

These are scripts, or rather tools, I use rather frequently. most are just easier to use interfaces for existing things. I often incorporate these into my other scripts and as such are designed primarily for personal use, but feel free to see if you like any of them.

### image-manipulation

* **deltaaspectratio** : accepts image file [ first argument ] and generates an output file [ second argument ] with a 1:1 aspect ratio. fills in blank spaces with white. 

### string-manipulation

* **del** : fetches input from stdin and deletes all occurence of the first argument

* **fillr** : fetches input from stdin and fills text [ second argument ] into a empty field [ second argument ]. fields and content have to be separated with :

* **readr** : fetches input from stdin and displays the value a particular field [ first argument ] posseses.

* **rep** : fetches input from stdin and replaces all occurences of first arguement with second argument

### math

* **duration** : returns the duration between start time [ first argument ] and end time [ second argument ]

### networking

* **serve** : serves a document [ first arguement ] on a specified port [ second argument ] over http using netcat

* **title** : fetches the title of webpage [ url as first argument ]  

### web

* **form** : generates a form using the format specified in the file


