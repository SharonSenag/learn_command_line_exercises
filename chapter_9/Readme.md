Making Empty Files (touch)

>Can you touch blah.txt?

Run `mkdir <name>`

CD `<name>` 

Run `touch blah.txt`

>Let's create foo.txt.

Run `mkdir <name>`

CD `<name>` 

Run `touch foo.txt`

>Unix: Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.

Directory's that have files in them cannot be deleted as noted by error message in example below:

apples-MacBook-Pro:temp sharonsena$ mkdir chili

apples-MacBook-Pro:temp sharonsena$ cd chili

apples-MacBook-Pro:chili sharonsena$ touch newmexico.txt

apples-MacBook-Pro:chili sharonsena$ cd ..

apples-MacBook-Pro:temp sharonsena$ rmdir chili

rmdir: chili: Directory not empty


>Do more:  Explain what happens if you touch an existing file

If I `touch` an existing file, it changes the time on the file
