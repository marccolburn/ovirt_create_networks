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


ovirt_hosts:
* name: Name of host
* interface: Name of interface to attach network to
* networks: List of networks
  * name: Name of network to be attached

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
