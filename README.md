# sp3_rotate
_rotate touch, display, and pen surface pro 3_

---

## Usage

I recommend adding sp3_rotate to the path.  
That way you can `rotate.TOUCH`, and `normalize.TOUCH` respectively.  
Otherwise `path/to/sp3_rotate/rotate.TOUCH` and `path/to/sp3_rotate/normalize.TOUCH`.  


### How to "add sp3_rotate to the path"

__bash__ (Linux or MacOS)  

Ensure you're in you home direcory with `cd`  
`nano .bashrc` and `Ctrl + w` to search for `PATH=`  
_removing or altering anything in this line may break some of your programs!_

So make sure you only add this entry, to the paths which are already there.  
Each folder path is separated by colons `:` so add `/home/<username>/git/sp3_rotate:` after the `=`.  
Or you can add `:/home/<username>/git/sp3_rotate` to the end of the `PATH=` line.

Your current terminal session will not yet reflect these changes. You will need to either start a new terminal window or run `. .bashrc` to reload the bash user configuration preferences file.


__zsh__ (Fer yall weirdies who don't want to learn a practical scripting lang)  

`cd ~`  
`vim .zshrc` in vim you can use `/` to search for `PATH=`  
vim uses a navigate mode and an 'insert' mode so you'll need to press `i` in order to make the changes.

_removing or altering anything in this line may break some of your programs!_

So make sure you only add this entry, to the paths which are already there.  
Each folder path is separated by colons `:` so add `/home/<username>/git/sp3_rotate:` after the `=`.  
Or you can add `:/home/<username>/git/sp3_rotate` to the end of the `PATH=` line.

Your current terminal session will not yet reflect these changes. You will need to either start a new terminal window or run `. .zshrc` to reload the bash user configuration preferences file.
