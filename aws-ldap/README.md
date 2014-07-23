Simple playbook to configure ldap for amazon aws instances.  Might need some
tweaking for your specific environment, but works for mine. 


You'll need an ldap.conf file to push, and if you want to add the sudoers part, a sudo file also. 
(The sudoers file will wind up in /etc/sudoers.d, so a partial file is fine)
