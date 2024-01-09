# ip_link_interface Ansible Role

Renames physical Interfaces on linux according to a map.

## Input
See specific format in `defaults/main.yml`. Essentially takes a mapping of mac addresses to interface names.

## Restrictions
This role has only be tested in Debian 12, but should work in any linux offering `iproute2`. The package installation works only in Debian os family.

## Licensing
This role is licensed in AGPLv3. That explicitly does not force you to make everything open source (or even (A)GPL) when just using this role (we do not consider a playbook as a derived product). However, modified versions of this role have to be licensed in AGPLv3+ according to the terms in `LICENSE`.

# Made by WorNet AG
This role is made by Michael Wodniok, WorNet AG.