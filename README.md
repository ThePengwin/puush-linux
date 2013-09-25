Puush Linux Script
==================

I was bored, and wanted a puush script that did screenshots automatically like the windows client does, so i made this bash script to do it for me. Use at your own risk!

What does it need?
------------------
You need 3 things to make it work
- scrot - an awesome command line utility to take screenshots
- notify-send - to send messages to your desktop
- xclip - to put your puush url onto your clipboard for you

Setting up
----------
To make it work
- get the puush script
- add it to your path (or anywhere easy to call)
- make it executable
- get your puush API key (find it at http://puush.me/account/settings)
- paste it into a new file called .puushkey in your home directory
- Create a keyboard shortcut in your desktop environment to call it how you want. (See options)

Options!
--------
With no arguments, the script acts like you called it with -fp

### Window modes
- -w - window mode - get the current selected window
- -s - select mode - Select an area by dragging the cursor over it (uses screen's -s switch)
- -d - desktop mode - Get the desktop (used to be f, but eventually f will be for a file upload)

### Image modes
- -p save as PNG
- -j save as jpeg


Some Notes
----------
Im quite new to making anything in bash, and i pieced this together from quite a few google searches.
I dont think adding a .puushkey file is the best way to go, if anyone has a better idea of where/how to store such a thing, let me know.
