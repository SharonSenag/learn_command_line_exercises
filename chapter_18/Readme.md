Looking inside files (grep)

>Show me the lines in foo.txt that have "ERROR" in them.

I would run these commands:

`apples-MacBook-Pro:tmp sharonsena$ cat foo.txt`

line of foo txt

line of foo txt

line of foo txt with error

line of foo txt with error

line of foo txt

line of foo txt

`apples-MacBook-Pro:tmp sharonsena$ grep -i error *.txt`

foo.txt:line of foo txt with error

foo.txt:line of foo txt with error

>Show me the lines in bar.txt that have "davinci" in them.

I would run these commands:

`apples-MacBook-Pro:tmp sharonsena$ cat bar.txt`

line of bar txt

line of bar txt

line of bar txt with Davinci

line of bar txt with Davinci

line of bar txt

`apples-MacBook-Pro:tmp sharonsena$ grep -i Davinci *.txt`

bar.txt:line of bar txt with Davinci

bar.txt:line of bar txt with Davinci

>Can you print all the lines in text files that have your first and last name in them?

I would run `grep -1 'Sharon Sena' *.txt`

>Explain what the -i option to grep accomplishes

Use -i to ignore case with grep
