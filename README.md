systemd-boot
============

Automate the process to switch from legacy GRUB2 boot to systemd-boot

Requirements
------------

System requires to have UEFI enabled, ESP mounted in /boot/efi or /efi. This initial release requires secure boot to be disabled.

Role Variables
--------------

None at the moment.

Dependencies
------------

None at the moment.

Example Playbook
----------------

Just import the role

    ---
    - hosts: servers
      roles:
         - mikelolasagasti.systemd-boot

License
-------

GPL-3.0-or-later

Author Information
------------------

Mikel Olasagasti Uranga <mikel@olasagasti.info>
