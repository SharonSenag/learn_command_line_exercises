>>Can you reload your terminal?

To reload the terminal type `Control-N (⌘-n)`

>>Can you logout?

To logout of the terminal, 

run `exit`, `quit` or just hit `Control-D (⌘-D)`

>Do more:  Use the help system to look up these commands:  xargs, sudo, chmod, chown

>>xargs:  construct argument list(s) and execute utility

The xargs utility reads space, tab, newline and end-of-file delimited
strings from the standard input and executes utility with the strings as
arguments.

Any arguments specified on the command line are given to utility upon
each invocation, followed by some number of the arguments read from the
standard input of xargs.  The utility is repeatedly executed until standard input is exhausted.

Spaces, tabs and newlines may be embedded in arguments using single
(`` ' '') or double (``"'') quotes or backslashes (``\'').  Single quotes
escape all non-single quote characters, excluding newlines, up to the
matching single quote.  Double quotes escape all non-double quote characters, excluding newlines, up to the matching double quote.
Any single character, including newlines, may be escaped by a backslash.

>>sudo:  execute a command as another user

sudo allows a permitted user to execute a command as the superuser or
       another user, as specified in the sudoers file.  The real and effective
       uid and gid are set to match those of the target user as specified in
       the passwd file and the group vector is initialized based on the group
       file (unless the -P option was specified).  If the invoking user is
       root or if the target user is the same as the invoking user, no
       password is required.  Otherwise, sudo requires that users authenticate
       themselves with a password by default (NOTE: in the default
       configuration this is the user's password, not the root password).
       Once a user has been authenticated, a time stamp is updated and the
       user may then use sudo without a password for a short period of time (5
       minutes unless overridden in sudoers).
       
>>chmod:  change file modes or Access Control Lists

The chmod utility modifies the file mode bits of the listed files as
     specified by the mode operand. It may also be used to modify the Access
     Control Lists (ACLs) associated with the listed files.

>>chown:  change file owner and group

The chown utility changes the user ID and/or the group ID of the specified files.  
Symbolic links named by arguments are silently left unchanged unless -h is used.



