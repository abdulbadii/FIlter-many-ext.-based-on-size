# FIlter-multi-extension-filename
Filter a file name that has made its folder getting cluttered with many extension name of it such tmp, bak, old, etc which usually comes out from several update processes.  This util will tidy up the folder by erasing all except one which is based on the greatest file size, or one newer modification time of two same greatest size if such are found.    
User is opt for having its own extension name specification by putting it in second argument, if skipping it then tmp, bak and old extension names should default
User is opt for having folder level to search for, next in the 3rd and 4th argument. Put 3 5, for instance will searh only 3rd through 5th folder depth level relative to current working folder, ie. the 1st folder.
