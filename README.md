# cloneProject

## Synopsis

A script that will clone an xCode project or workspace. (And it REALLY works quite well)

This script will copy an xCode project to a new project directory name
and replace/rename all files within to work as expected under the new name.  I have found this script to work properly on workspaces, pod files, the works.

Project names that contain characters other than alpha-numeric, spaces or
underscores MAY not work properly with this script.  And, naturally you may want to git init the cloned copy.


## Code Example

Copy a project that you want to copy to your desktop. In terminal, navigate to desktop, and run the following in terminal.

    cloneProject sourceProject newProject
    
The only rule is that the sourceProject name connot containthe new project name.  So for instance, renaming "MyStuff" to "MyStuff2" will not work.  
    


## Installation

copy this file to a directory in your path and make it executable with:


    chmod +x cloneProject.sh


## Creators

Morphed from the original renameXcodProject.sh by Monty Ohrt, and modified by Rudi Farkas <rudi.farkas@gmail.com>


