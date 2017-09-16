# openmosh
## mosh connection handler

openmosh was written by Tiris Eroe tiriseroe@gmail.com GNU GPL v3.0

mosh was written by Keith Winstein mosh-devel@mit.edu. Project home page: https://mosh.org.

Note:
  * the following 2 environment vars may be set (exported) in order to use shortcut options -c, -k, -r
	  * OMDSPORT    default ssh port, exported var
	  * OMDIP       default ip, exported var
  * for example, set up these 2 vars in .bashrc
    
Requires: 
  * mosh installed on "client" and "server" sides.
  
Verified:
  * openmosh v3.1-0 verified:
  * originating: mosh 1.3.2+1279-0ppa~ubuntu17.04.1 on Ubuntu 17.04 zesty.
  * terminating: mosh 1.2.5-2 on Ubuntu 16.04.3 LTS xenial.
  
Fixed in v3.1-0:
  * cleaned up help printout
  * added ability to connect with random mosh port (60000≤P<61000) with command line specified ssh port and target IP

ToDo: 
  - [X] fix wrong password hang (unable to duplicate)
  - [ ] create .deb installation

:koala:
