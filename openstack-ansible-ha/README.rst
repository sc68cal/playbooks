====================
openstack-ansible-ha
====================

Deploy OpenStack Ansible in OpenStack cloud in HA mode.

Steps
=====

#. Source your credentials.

   .. code:: bash

      source path/to/my-openstack-openrc

#. Check out environment setup in ``vars/shared.yml``.

#. Run the playbook.

   .. code:: bash

      ansible-playbook site.yml
