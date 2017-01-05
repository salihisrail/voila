

# voila
a setup/build file for a site for managing access to media files

This only works in Unix/Linix

It's simple. 
run "python makeVidServer" in command prompt.
Then follow prompts provided in program. 

the path for the media file you want to add
must be a directory, no quotation marks 
required ex.: C:\User\FolderWithMediaFiles

The program will parse through every folder and
file under that directory.

If there are multiple directories, enter them
as the prompt requests.

Pick a color for your site, don't put the quotation marks.

Give your site a name as prompted.

Then provide the directory where you want the site to be stored.
ex.: C\User\SiteFolder 

The site folder should not exists before hand. The program will
build it.


makepath.py changes or reboots the paths of your media files
whenever you change them or add more. For reasons I care not to 
explain, I had an incomplete version of python2.6, which didn't have the json 
module or the os.walk method. I was still in the learning stages of python,
so working through this code was an adventure.
