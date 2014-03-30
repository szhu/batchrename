batchrename
===========

Need to rename a bunch of files and only have a smart text editor? Fear not!

Ever had a bunch of files in a directory that you wanted to rename at once? With **batchrename**, now you can—

+ Change the capitalization of filenames
+ Find-replace strings in filenames
+ Maniupulate file extensions

There are GUI programs that grant some of this functionality, but why use a GUI for text operations you’re already familiar with?

It’s simple:

1. Create the file `_` (single underscore), with the old filenames, one per line.
2. Create the file `__` (two underscores), with the new filenames in the same positions
3. `batchrename`!

**batchrename** is only tested with files in the same directory but will probably work with subdirectoies and parent directories with the use of `/` and `..`.
