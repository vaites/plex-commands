Plex Commands
=============

Plex channel to provide useful commands 

Features
--------

* Works on Linux and Mac OS X
* Commands can be executed from any client
* Ability to shutdown, restart, hibernate or suspend server
* Shortcut to refresh all libraries

Requirements
------------

* Plex Media Server 0.9 or higher
* Linux or Mac OS X server 

Install
-------

Download and extract the folder *Commands.bundle* to:

* **Linux**: /var/lib/plexmediaserver/Library/Application Support/Plex Media Server/Plug-ins
* **Mac OS X**: /Applications/Plex Media Server.app/Contents/Resources/Plug-ins

The user that runs Plex Media Server need rights to execute this commands. The easiest (but [not the most suitable for 
all users](http://www.techrepublic.com/blog/linux-and-open-source/quick-introduction-to-suid-what-you-need-to-know/)) 
method in Linux and Mac OS X is to *setuid* some executables with the following command:
 
```sudo chmod s+u /sbin/shutdown```

The user and group in Linux are *plex:plex* (daemon) but in Mac OS X the user is the one that is validated.  

TO-DO
-----

* Add support for Windows