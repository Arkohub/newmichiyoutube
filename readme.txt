In order to gather the subtitle files, run this command in terminal.

youtube-dl --all-subs --skip-download 'https://youtube.com what ever, your URL goes here of the playlist'

Then you will have all the .vtt files. 

From there you can run the following in terminal to covert the text files. 

python subs2txt.py *.vtt 

This will run on all files within this directory. 

