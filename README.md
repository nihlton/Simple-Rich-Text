# Simple-Rich-Text

Simple rich text editing functionality in less than 100 lines.  

(Mac users, try [command] instead of [ctrl])

[CTRL] + 
* [ I ] for italic
* [ B ] for bold
* [ Y ] for strike
* [ U ] for underline
* [ up arrow ] for big
* [ down arrow ] for small
* [ Q ] to clear styles.
* [ Z ] to undo.


This is just the POC.  

Demo here:  http://gregtaff.com/misc/rich.html

Later, I'll extract and package this as a library you can import.

Caveats: 

* doesn't do any clean up. would benefit from a little {/<[^\/>][^>]*><\/[^>]+>/} after editing  
* styling is one way.  ctrl + b wont remove bold styling from bold text.  text can be unstyled with ctrl + q.  
