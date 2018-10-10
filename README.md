NB: This Vagrant-file implies that your network has an installed and running DHCP-server!

This Vagrant-file prepare a virtual environment on CentOS 7.5 and using provisioner "ansible_local" installs into the prepared environment the following set of software packages: Apache, nginx, php7, MariaDB and Redis and configures them. Further, an archive with cs-cart CMS-system will be downloaded and unarchived. On last task IPs on interfaces will be shown.

Finally, an administrator has an installed and configured environment for further installation of CSCart CMS. To start installation you need to go by link "http://IP", where IP was shown on the last step of playbook.yml execution.