jboss_eap_ansible
=======

I did not like the Reference Arch for this so I made an Ansible installer.

Currently this is bad I don't recommend using it. There are some hardcoded values and assumptions made. I hope to make an easier method of installing this than the docs recommend - Which, is individually into each node and doing manual configuration. I hope to create something as dynamic and flexible as the ansible-openshift installer, and in a similar suite.

These playbook assume jboss-eap-7.0.0.zip, jbcs-httpd24-httpd-2.4.6-RHEL7-x86_64.zip, and eap7.tgz are in the directory it is ran out of. Links to these files are available in the reference architecture. 
