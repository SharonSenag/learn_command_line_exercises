Pipes and redirection

>Can you put "This class is fun" into bar.txt?

cd into chapter_15 Readme

touch `bar.txt`

Run `echo 'This class is fun' > bar.txt`

Run `cat bar.txt` to view words in file

>Can you put "Oh so much fun" into foo.txt?

cd into chapter_15 Readme

touch `foo.txt`

Run `echo 'Oh so much fun' > foo.txt`

Run `cat foo.txt` to view words in file


>Shell output

apples-MacBook-Pro:learn_command_line_exercises sharonsena$ cd chapter_15

apples-MacBook-Pro:chapter_15 sharonsena$ ls

Readme.md

apples-MacBook-Pro:chapter_15 sharonsena$ touch bar.txt

apples-MacBook-Pro:chapter_15 sharonsena$ touch foo.txt

apples-MacBook-Pro:chapter_15 sharonsena$ ls

Readme.md	bar.txt		foo.txt

apples-MacBook-Pro:chapter_15 sharonsena$ echo 'This class is fun' > bar.txt

apples-MacBook-Pro:chapter_15 sharonsena$ cat bar.txt

This class is fun

apples-MacBook-Pro:chapter_15 sharonsena$ echo 'Oh so much fun' > foo.txt

apples-MacBook-Pro:chapter_15 sharonsena$ cat foo.txt

Oh so much fun
