## what is Linux ?
Linux is an operating system which is open source which means it provides the source code for the core 
functionality of an operating system,called a kernel and users can modify and expand it.

Linux allow multiple people to use the same computer at the same time and can run multiple applications
simultaneoulsy.It also supports network functionality and provides system tools.


 ### Features of Linux:
* open source
  1. Code is publicly available
  2. Users can modify and expand it
* supports multiple users and multi-tasking
* Is built to handle networking
* Provides system tools and utilities



### Distributions 

A distribution or *distro* is a packaged version of Linux that a group of individuals or an organizations
develops.

A distribution includes core operating system functionality (**kernel**) and additional complementary 
tools and software applications.

Examples of Linux distributions:
* RHEL(Red Hat Enterprice Linux)
* Debian
* Ubuntu

### Components of Linux

A Linux distribution mainly consists of 

* #### Kernel
* #### Daemons
* #### Applications
* #### Data files
* #### Configuration files


---

### Networking commands

* dig @server host
* nslookup host server
* host host server
* ping sitename

### Looking at common network config files

> The following files are associated with the DNS

* /etc/hosts
  * This is where the linux looks up for the dns before checking the network
* /etc/nsswitch.conf
  * This tells where the system looks for the dns first
* /etc/resolv.conf
  * This tell the computer what nameserver to use
  * __Dont't edit this file__


### managing password files

Linux has two different files for managing passwords

1. /etc/passwd
   * This file can be read by anyone.
   * Only the root can write on this file.
   
3. /etc/shadow
   * Contains the actual encrypted passwords for the user
 
** To edit this files use **
` vipw `
` vipw -s `


---

Every user has a profile and profile.d file inside /etc/ folder ,whenever a user logs in this files gets activated and allow users to perform their tasks
```bash

ls -l | grep profile

cd /etc/profile

```
### Text editing

1. sed
  * This allows to edit text on the run which means without entering any editor
  * ` cat file.txt | sed s/"word_to_replace"/"new_word"/g `





 
 
 
 

 





