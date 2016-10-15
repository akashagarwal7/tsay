# tsay
Simple speech alert, UI icon bounce alert and displaying completion time when a terminal process gets completed for OS X

You don't have to keep hopping back to terminal to check if a long process like `brew install formula` is completed. 
Installation:  
`brew install akashaggarwal7/tools/tsay`  
Usage example:  
`sleep 5; tsay // Switch active window to see the bounce effect`  
`brew install formula; tsay`  

If you already have the tsay installed and wish to upgrade to the latest version, run:  
`brew upgrade tsay`

And tsay will play a nice speech text, bounce the terminal icon in dock and display the completion time of the command appended in the window.
