Wildcard matching

>How big is foo.txt?

Run `du -h foo.txt`

sample output:

apples-MacBook-Pro:chapter_15 sharonsena$ du -h foo.txt

4.0K	foo.txt

reference url:  http://www.cyberciti.biz/faq/how-to-see-file-size-on-linux-unix/

>Can you output all the txt files in this directory?

cd into directory then run `ls *txt`

>Show me the content of the text files in slash temp.

cd into ` ~ tmp` directory

Run `cat *.txt`

sample output:

apples-MacBook-Pro:tmp sharonsena$ ls

Readme.md	bar.txt		foo.txt

apples-MacBook-Pro:tmp sharonsena$ cat *.txt

This class is fun

Oh so much fun
