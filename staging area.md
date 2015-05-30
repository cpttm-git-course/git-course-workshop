The staging area is a file, generally contained in your Git directory, 
that stores information about what will go into your next commit. 
It’s sometimes referred to as the “index”, but it’s also common to refer to it as the staging area.

The basic Git workflow goes something like this:

1.You modify files in your working directory.


2.You stage the files, adding snapshots of them to your staging area.


3.You do a commit, which takes the files as they are in the staging area and stores that snapshot permanently to your Git directory.


If a particular version of a file is in the Git directory, 
it’s considered committed. If it’s modified but has been added to the staging area, 
it is staged. And if it was changed since it was checked out but has not been staged, it is modified.
 