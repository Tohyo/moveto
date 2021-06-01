# MOVETO

This is a simple bash script to move between a set of defined directories

## Usage

Move the script to make it availble globaly

`cp moveto /usr/local/bin` 

Move the folders.json file into your home folder and edit it

`mv folders.json.dist /home/$USER/folders.json`

I also recommand adding a alias in your bash_aliases

`alias m=". moveto"`

NB: You need to add the dot before to run the execute the script in the same shell as you run it
