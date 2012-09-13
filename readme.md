ftptail was written by [Will Moffat](http://hamstersoup.wordpress.com/about-will/) 
========

**ftptail** allows you to tail logs via FTP.  Will didn't seem to have a github page so I am putting it up here to get this awesome bit of code out there. 

Example
=======

ftptail -f -p passwd.txt will@hamstersoup.com/access.log
Command Line Options

Usage: ftptail [OPTIONS] user@host/file
Print the last 10 lines of file on an FTP server.

Options:
   -n, --lines=N           Print the last N lines of the file (default:10)
   -f, --follow            Keep FTP connection open and append as file grows
   -s, --sleep-interval=S  Sleep S seconds between updates    (default:200)
   -p, --password-file=P   Use the password stored in P to login
   -v, --verbose           Dump info about FTP connection to STDERR
