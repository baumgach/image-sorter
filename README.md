Small project for sorting images in a folder into a number of label categories which can be specified 
by the user. The system displays a GUI using Tkinter which lets the user cycle rapidly through all the images in the folder, and assign them a label, that is copy it to a subfolder with that label name.  

The only requirement not already packaged with python is the `Pillow` 
library.

Usage:

    python sort_folder.py 
        --folder <INPUT-FOLDER> 
        --labels <INPUT-LABEL1> <INPUT-LABEL2> ...
        
