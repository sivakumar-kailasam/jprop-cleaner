jprop-cleaner
=============

Sublime text 2 plugin to remove multiple occurrences of a key in java property files.

Sometimes we end up having duplicate entries of the same key due to merge issues in source control (I'm looking at you svn!) or other reasons. This is something I whipped up to remove such duplicate entries and preserve the last key value pair because that's the one resource bundle class ends up selecting from the file. 


If you want to know the duplicate entries in the file open up the SublimeText2 console using ctrl+` to see the list of keys.


Definitely open to suggestions and ideas to improve this :)