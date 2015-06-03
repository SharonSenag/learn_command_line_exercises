>Can you cd into the temp directory?
 
From home directory (~), run cd temp
 
>Why don't we go into the temp directory?
 
From home directory (~), run cd temp
 
>Can you go to the slash temp directory?
 
Run cd /temp 

>Can you go to the slash temp slash log directory?

Run cd /temp/log

>What does the .. argument to cd do?  Explain.

Use the .. to move "up" in the tree and path

>Do More bullet points

>>cd to the joe directory with one command

From temp run `cd stuff/things/frank/joe`

apples-MacBook-Pro:temp sharonsena$ cd stuff/things/frank/joe

apples-MacBook-Pro:joe sharonsena$ ls

alex

>>cd back to temp with one command, but not further above that.

cd ../../../../

>>Find out how to cd to your "home directory" with one command.

cd ~

>>cd to your Documents directory, then find it with your GUI file browser (Finder, Windows Explorer, etc.).

Run `cd ~/documents`

Shell output:

apples-MacBook-Pro:~ sharonsena$ cd ~/documents

apples-MacBook-Pro:documents sharonsena$ pwd

/Users/sharonsena/documents

>>cd to your Downloads directory, then find it with your file browser.

Run `cd ~/downloads`

apples-MacBook-Pro:~ sharonsena$ cd ~/downloads

apples-MacBook-Pro:downloads sharonsena$ pwd

/Users/sharonsena/downloads

>>Find another directory with your file browser, then cd to it.

Run `cd ~/workspace`

Shell output: 

apples-MacBook-Pro:~ sharonsena$ cd ~/workspace

apples-MacBook-Pro:workspace sharonsena$ pwd

/Users/sharonsena/workspace
