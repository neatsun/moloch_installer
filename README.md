Moloch install scripts for Ubuntu 14
=================================

These scripts are modifications of the AOL Moloch install scripts http://github.com/aol/moloch

They are a work in progress.  The attempt is to meet as many moloch requirements using standard
ubuntu packages, PPA or debs.  The start up scripts have been replaces with upstart configs.  

It has been tested on Ubuntu LTS 14.04 n aws 

To install everything on a single host, on a fresh install you can just run:

    $ git clone https://github.com/neatsun/moloch_installer.git
    $ cd moloch_installer
    $ ./moloch-install.sh

The script will download everything required to install moloch (no prior checkout of moloch code required).  It will create a directory 'src/' in the home directory of user executing the script.  It will prompt you for sudo password when required.

Warning: the scripts are designed to run on a clean install.  There is minimal checking for previous configuration files or moloch installs

** based on dollarampersand/moloch_installer

