#OSX-Workflows#

Automator workflow scripts I'm using daily on my machine.
download each folder, as they are bundels, and move them to your ~/Library/Services folder. Services will then be available from the Finder contextual menu.

###Convertir en ICNS.workflow###

Select pictures and this service will use `sips` to convert them as OSX icons. Use this to creat your own personal OSX icons

###Convertir en JPEG.workflow###

Convert the selected files to JPEG. Uses the `sips`command

###Dater et convertir en JPEG.workflow###

Appends the file creation date and convert the picture to JPEG. Uses the `sips` command. I'm using this for iPhone screenshots I want to save as JPEG.

###Retailler pour Instagram.workflow###

Resizes the selected picture to 600x600 pixels and append the .ig suffix

###Retailler pour Flickr.workflow###

Resize the photos to 1024x1024 and append .f to the filename. I'm using it before uploading to flickr, as I don't want the full resolution available.

###Retailler pour Foodspotting.workflow###

Resizes the selected picture to 600x600 pixels and append the .fs suffix

###Mettre en minucule.workflow###

Lowercase the selected filenames

###Dater et mettre en minuscule.workflow###

Appends the file creation date and lower case the filename. I'm using this to sort photos in my folders

###Create Archive with 7zX.workflow###

Creates a 7zip archive of the selected files. You need to have 7zip installed.

###Dater.workflow###

Appends the date to the selected filename

###Create symbolic link.workflow###

Creates a symlink from the finder as you would do in terminal with ln -s

###Effacer quarantaine.workflow###

Removes the Quarantine bit from newly downloaded app.
