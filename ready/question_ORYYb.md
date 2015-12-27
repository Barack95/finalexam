A command that counts the number properly formated questions in the `finalexam` project (if executed from `finalexam` directory).

* `ls * | wc -l`
* `ls * | grep '^question_XXXXX\.md$' | wc -l`
* `ls * | grep '^[a-zA-Z0-9_]*\.md$' | wc -l`
+ `ls * | grep '^question_.....\.md$' | wc -l`
* `ls */* | wc -l`
* `ls * | grep -c '.*\.md$'`
