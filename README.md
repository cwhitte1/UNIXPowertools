# UNIXPowertools
Projects from my UNIX Powertools class taught by Dr. Massingill -- August 2016 through December 2016

For my UNIX Power Tools project, I created a shell script that reorganizes files in a directory, creating subdirectories based on the filename prefix, and organizing subdirectories by file extensions. To accomplish this, the first half of the script loops through each file in the main directory it is working in, and determines the prefix attached to the file. From there, the file is appropriately moved to the subdirectory for its prefix. In the second half of the script, the script moves through each subdirectory, and organizes the files within by their extension. This is done by looking at each filename’s extension, and moving the file into the appropriate subdirectory based on that file’s extension. Once this is executed, the original main directory’s files are organized by prefix and extension! The script also places itself in a directory titled after its prefix (my last name in this case)! If one were to title their files with prefixes, this script could be very effective in helping them keep organized. 

For the UNIXMakeFileProject, when you type make main, creates executable main from the source files, compiling
just the parts of this program that need to be recompiled. Compile using gcc C compiler. 
When you type make clean, deletes all the object files for the program.
When you type make xclean, deletes all the object files for the program and the executable.

