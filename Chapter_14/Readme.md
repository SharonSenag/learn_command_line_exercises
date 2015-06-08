Removing a file (rm)

>Can you remove blah.txt?

Run `rm blah.txt`

>Let's get rid of our development log file.

Run `rm development.log`

>Can you remove everything in the slash temp slash foo directory?

Run `rm -rf /tmp/foo`

>Why is it dangerous to run "rm -rf /" (DO NOT RUN THIS COMMAND)

The rm command is what you use to remove or delete a file or directory. 

By itself, rm will delete a file. 

With the -r or -R option, it will recursively delete a directory. 

The -f option will force the action. 

Typing `rm -rf /` will delete everything that you have permission to delete. 

That means almost everything in your home directory. 

As root, it will continue to chew up any file it encounters until your screen eventually turns completely dark. 

Do not try it, unless you want to have a very, very bad day.
