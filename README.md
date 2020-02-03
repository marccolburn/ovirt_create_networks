oVirt Create Networks
=========

Create networks in oVirt

Requirements
------------


Role Variables
--------------
vm_networks:
* name: Name of network
* vlan: VLAN ID
* datacenter: oVirt Data Center

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: ovirthost
      roles:
         - { role: ovirt_create_networks }

License
-------

BSD

Author Information
------------------

Marc Colburn Red Hat
