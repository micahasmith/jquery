[mQuery](http://jquery.com/) - cause $.noConflict is for suckas
==================================================

The only way to know for certain that your newer jquery won't interfere with your old jquery is to rename the new one to mquery, when you have absolutely no control over being able to $.noConflict.

For external scripts that you want to use with mquery, you should probably module pattern in the name change. (I would guess)