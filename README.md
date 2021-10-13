### bash-updator

A script that compiles the following commands into one : 
- <code>dpkg --configure -a</code>
    - pre-configuring packages
- <code>apt-get install -f</code>
    - fix and attempt to correct a system with broken dependencies
- <code>apt-get update</code>
    - update apt cache
- <code>apt-get upgrade</code>
    - upgrade packages
- <code>apt-get dist-upgrade</code>
    - distribution upgrade
- <code>apt-get --purge autoremove</code>
    - remove unused packages
- <code>apt-get autoclean</code>
    - clean up

Use <code>-r</code> parameter to reboot after successfull update.
