## Wildcard matching

> ### How big is foo.txt?

Run `du -h foo.txt`

sample output:

apples-MacBook-Pro:chapter_15 sharonsena$ du -h foo.txt

4.0K	foo.txt

reference url:  http://www.cyberciti.biz/faq/how-to-see-file-size-on-linux-unix/

> ### Can you output all the txt files in this directory?

cd into directory then run `ls *txt`

> ### Show me the content of the text files in slash temp.

cd into ` ~ tmp` directory

Run `cat *.txt`

sample output:

apples-MacBook-Pro:tmp sharonsena$ ls

Readme.md	bar.txt		foo.txt

apples-MacBook-Pro:tmp sharonsena$ cat *.txt

This class is fun

Oh so much fun

> ### Additional questions from Jason

> ### Running ls *.txt would list all files in this directory that end in txt. How would you display the contents? 

Run `ls -R` to list all directories and all their contents

> ### Can you show the content of the text files in slash temp without navigating (cd) there first?

Run `ls chapter_16/tmp`

output: `chapter_16.txt`

> ### The following is a brief list of options commonly used with ls. 

-a (all) — Lists all files in the directory, including hidden files (.filename). The .. and . at the top of your list refer to the parent directory and the current directory, respectively.

-l (long) — Lists details about contents, including permissions (modes), owner, group, size, creation date, whether the file is a link to somewhere else on the system and where its link points.

-F (file type) — Adds a symbol to the end of each listing. These symbols include /, to indicate a directory; @, to indicate a symbolic link to another file; and *, to indicate an executable file.

-r (reverse) — Lists the contents of the directory in reverse sort order.

-R (recursive) — Lists the contents of all directories below the current directory recursively.

-S (size) — Sorts files by their sizes.
