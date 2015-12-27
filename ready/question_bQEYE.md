A command that creates file ``new`` as a concatenation of ``file1`` and ``file2``.

* ``cp file1 file2 new``
+ ``cat file[12] > new``
+ ``cat file1 file2 > new``
+ ``cat < file1 > new; cat < file2 >> new``
* ``mv file[12] new``
* ``cat file[12] 2> new``
* ``cat file[12] -> new``
* ``cat file[12] | new``
* ``cat file1 file2 | new``
