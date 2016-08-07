Role Name
=========

ansible-role-dhcp-server

Requirements
------------

None.

Role Variables
--------------

`dhcp_server_config_file`: Path to a file to use as dnsmasq.conf. Default: `dnsmasq.conf`.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: dhcp-servers
      roles:
         - { role: rfleschenberg.dhcp-server, dhcp_server_config_file: dnsmasq.conf }

License
-------

BSD

Author Information
------------------

René Fleschenberg <rene@fleschenberg.net>
