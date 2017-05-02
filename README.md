# qgs.py
"Quick Google Search" from Linux terminal.

A browser automatically opens &amp; key term is entered and submitted. Did this for fun to test out import getopt, urllib, urllib2.

 I used funtion str().replace() for search = argv[2:].<br />
 str() places argv[2] into a string, including whitespaces.<br />
 replace() is used to remove "['','']" characters from string.<br />
 
 Now user can enter strings with whitespaces, symbols, etc. and it will read as only at argv[2].
 Search term will come out clean for a google search because of replace().
 
 ex:
 ./qgs.py -s inurl:londonfog intext:official
 
usage: Usage: g_search.py [(--search, -s) key terms] [-h help menu]

NOTE - Google needs User-Agent filled out, as it does not accept otherwise unfamiliar Agent requests.
