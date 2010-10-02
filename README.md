Description
===========

Series Yonkis is a website where you can find the download url for a lot of chapters of tv shows.
The process to arrive to the final url is a little bit tedious so I made a crawler to fetch it for you.

At the moment the script is made in PHP so you have to be sure that you have it installed

Usage
============

1. Get a copy of the files in your machine
2. Open a command line and navigate to the crawler folder
3. Give execution permissions with
    `chmod 777 crawler`
3. Execute the crawler with the following command, this will give you the title and url of each chapter in the stdout
    `./crawler [URL OF THE CHAPTER LIST IN SERIES YONKIS]`
    
    Example:
    `./crawler http://www.seriesyonkis.com/serie/house/`
4. If you want the urls in a file just redirect the output to a file like this:
    `./crawler [URL OF THE CHAPTER LIST IN SERIES YONKIS] > links.txt`
    
    Example:
    `./crawler http://www.seriesyonkis.com/serie/house/ > house-links.txt`

TODO
============

Migrate the script to a native code for each OS