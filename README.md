Contains the ansible playbook to easily configure servers.

# Mailservers

You have to place a file 'dovecot.passwd' into 'secure'.
It contains lines with 'username:{scheme}passwordhash'.

Global vars can be set in 'roles/mailserver/vars/main.yml',
you can also configure variables per host in the directory 'host_vars'.

Thanks for the mailserver part to [Fabien Dupont](http://git.kafe-in.net/ansible-kafein). 

# License
[CC BY-NC-SA 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/)
