hptool - command line hp microserver remote access card management.
-------------------------------------------------------------------

The script itself is just an example, really it's the 2 rac-* files that matter. I use a script that optionally loops through 4 dracs for management and info, feel free to adapt this one to suit your setup.

The script requires javaws for console/media redirector and ipmitool for power on/off/soft, status/sensor operations etc...

You will need to edit the IPMIUSER/IPMIPASS vars at the top of the script, place the 2 rac-* files somewhere and point the openrac function at them. The provided script assumes they are under ~/.rac/

Works fine under linux/cygwin, osx console works but remote media seems broken, not sure why tbh.
