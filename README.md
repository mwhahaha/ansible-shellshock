ansible-shellshock
==========
This is an ansble playbook to address the bash vulnerability in 
CVE-2014-6271 and CVE-2014-7169.  This playbook automates the remediation items
from https://access.redhat.com/articles/1200223.

To be able to run this against a RHEL or CentOS 5/6 box, you will need to
perform the downloading of the bash_ld_preload.c from the above article.
Once you have compiled it, place it in the files/RedHat[5-6]/ folder depending
on your distro version.

HOWTO run
------
```
ansible-playbook -i <hostfile> bash.yml -k -K
```


Author
-----
* Alex Schultz <aschultz@next-development.com>
