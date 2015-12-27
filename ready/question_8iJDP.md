How do you print the lines between 5 and 10, both inclusive.
+ `cat filename | head | tail -6`
* `cat filename | head | tail -5`
* `cat filename | tail +5 | head`
* `cat filename | tail -5 | head -10`
* `cat filename | tail -n +5 | head -5`
