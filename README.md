# trilium-back-to-history
This script can remember your browsing historical progress so that you can quickly jump to the last browsing position.
Support manual jump and automatic jump.
![](./images/button.png)
## version:0.1.5
## Installation
1. Create a code note of type JS Frontend with the contents of BackToHistory.js and the label #widget
2. Create a note to store the historical progress of browsing 
3. Fill in the notes created in the second step into the position of Window.Backto ["HistoryNoteid"] position in the first step.
   ![](.images/../images/install.png)

## Notice
1. Record the rolling position when each rolling notes
1. Check whether there are historical records when activating the new tab. Display the jump button when there is a historical record
3. Currently, manual jump supports text and code annotations
4. By the way, this plugin fixes a bug in trilium: without installing this plugin, when you open a note with toc and a note without toc, and switch back and forth, the scroll bar of the note will automatically scroll to the wrong position, and this plugin will automatically scroll to the original correct position