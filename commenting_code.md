# Commenting Code 
If you are writing code in vim, You may find yourself commenting multiple lines of code.
You can go and insert  comment on each line manually but that would be inefficient.

First, visually make a visual selection of the lines you wish to comment using V and j or k  
to move down and up. Then, use the norm command to run a normal mode command across all lines  
in the visual selection. The command will be i to insert at the beginning of the line followed  
by # or whatever your language’s comment character is.
![Commenting Code](/assets/images/comment_code.png)




