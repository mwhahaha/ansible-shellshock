ansible-shellshock
==========
This is an ansble playbook to address the bash vulnerability in 
CVE-2014-6271 and CVE-2014-7169.  This playbook automates the remediation items
from https://access.redhat.com/articles/1200223.

HOWTO run
------
```
ansible-playbook -i <hostfile> bash.yml -k -K
```


Author
-----
* Alex Schultz <aschultz@next-development.com>
