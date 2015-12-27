A command that does not match all the lines containing a capital letter in file ``list``.

* ``grep '[A-Z]' list``
* ``grep '.*[A-Z].*' list``
+ ``grep '[A-Z]$' list``
+ ``grep '^[A-Z]' list``
* ``grep '[A-Z]*' list``
* ``egrep '[A-Z]+' list``
