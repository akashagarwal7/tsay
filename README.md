# tsay
Simple speech alert, UI icon bounce alert and displaying completion time when a terminal process gets completed for OS X.

No more hopping back to terminal every now and then to check if a long running process like `brew install <formula>` is completed.

## Installation
`brew install akashagarwal7/tools/tsay`

## Usage examples
`sleep 5; tsay // Switch active window to see the bounce effect`  
`brew install <formula>; tsay`

`tsay` will play a nice speech text, bounce the terminal icon in dock and display the completion time of the command appended in the window.  

## Upgrading
To upgrade `tsay` to the latest version, run:
`brew upgrade tsay`
