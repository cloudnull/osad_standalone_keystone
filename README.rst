Standalone Keystone OSAD on public cloud
########################################

deploy keystone standalone using OSAD on RAX Public Cloud

How to use this
---------------

* You will need a Rackspace Public Cloud account.
* Fill in the os-creds.yml file with your Public Cloud Credentials.
* Execute the simple regions playbook.

Example command

.. code-block:: bash

  ansible-playbook -i inventory -e @os-creds.yml osad-standalone-keystone-playbook.yml
