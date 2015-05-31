Copy a file (cp)

>Can you copy the foo.txt file to slash temp? (Create foo.txt first...)

No, permission is denied because it is the master directory

example: 
apples-MacBook-Pro:temp sharonsena$ cd sspractice

apples-MacBook-Pro:sspractice sharonsena$ ls 

  foo.txt

apples-MacBook-Pro:sspractice sharonsena$ cp foo.txt /temp
  
  cp: /temp: Permission denied


>Can you copy .bash_profile in your home directory to the current directory?

Run cp ~/Desktop/.bash_profile ~/Documents

>Explain what Robocopy is

Robocopy or "Robust File Copy" is a command-line directory/file replication command.  

Robocopy allows you to setup simple or advanced backup strategies. 

It provides such features as multi-threaded copying, mirroring or synchronization mode, automatic retry, and the ability to resume the copying process.

>Do more sections:  Use the cp -r command to copy more directories with files in them.

The -r or recursive flag tells the cp command to copy every item in the folder: every sub-folder, every file and folder in every sub-folder, and so one, all the way down, to the new location. 

Copy a directory from your Desktop to your Documents folder like this:

cp -r ~/Desktop/MyFolder /Documents

A / (slash) at the end of a directory? That makes sure the file is really a directory, so if the directory doesn't exist I'll get an error.

