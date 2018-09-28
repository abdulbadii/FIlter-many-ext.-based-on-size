# FIlter-multi-extension-filename
Filter a file name that has made its folder cluttered with many extension name of it such tmp, bak, old, etc which usually comes out from several update processes.  This utility will tidy up the folder by erasing all except one which is based on the greatest file size, or one newer modification time of two same greatest size if two are found.    
User is opt for having its own extension names specification by putting it in second argument preceded by -xt , if skipping it then tmp, bak and old extension names should default
User is opt for having folder level to search for, next in the 3rd  argument preceded with -d. Put -d3,5 for instance, will searh only 3rd through 5th folder depth level relative to current working folder, ie. the 1st folder.
