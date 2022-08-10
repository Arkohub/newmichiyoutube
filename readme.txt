In order to gather the subtitle files, run this command in terminal.

youtube-dl --all-subs --skip-download 'https://youtube.com what ever, your URL goes here of the playlist'

Then you will have all the .vtt files. 

From there you can run the following in terminal to covert the text files. 

python subs2txt.py *.vtt 

This will run on all files within this directory. 




The 'introductory MIT playlist' folder is from https://www.youtube.com/c/mitocw/playlists?view=50&sort=dd&shelf_id=1

To combine all of the text files into one/others use the following:
Cat file.txt: will print out the contents onto terminal. 
Cat file1.txt file2.txt > newfile.txt: Will concatenate the files into the new file name. 
Cat file1.txt >> file2.txt: will append file2 with file1 (add). 
And to combine all in the current directory, do this:
cat ./* > new_filename.txt


To delete all of a type of file use the following:
find . -name "*vtt" -type f -delete: This will delete everything with that file extension. 

If you aren't sure yet, you can check if it will do the files you want by typing in:
find . -name "*vtt" -type f: By omitting the delete it will just fine them I think. 
