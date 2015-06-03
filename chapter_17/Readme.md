Finding Files (find, DIR -R)

>Can you show me all the files in slash temp slash foo?

Run `cd tmp`

Run `find . -name 'foo.txt' -print`

Shell output: 

apples-MacBook-Pro:chapter_17 sharonsena$ cd tmp

apples-MacBook-Pro:tmp sharonsena$ ls

foo.txt

apples-MacBook-Pro:tmp sharonsena$ cd ..

apples-MacBook-Pro:chapter_17 sharonsena$ find . -name 'foo.txt' -print

./tmp/foo.txt

>What log files are in your log directory?

Run `cd ./.rvm/log`

Run `ls`

Shell output: 

apples-MacBook-Pro:~ sharonsena$ find . -name 'log' -print

./.rvm/log

./Library/Application Support/BitTorrent Sync/ui/bootstrap-sync/test/dummy_rails/log

./Library/Application Support/TextMate/Managed/Bundles/Git.tmbundle/Support/app/views/log
find: ./Library/Saved Application State/com.adobe.flashplayer.installmanager.savedState: Permission denied

apples-MacBook-Pro:~ sharonsena$ cd ./.rvm/log

apples-MacBook-Pro:log sharonsena$ ls

1431794581_ruby-2.2.1	

1431794765_ruby-2.2.1	

1433208531_ruby-2.2.1

1431794717_ruby-2.2.1	

1431794901_ruby-2.2.1
