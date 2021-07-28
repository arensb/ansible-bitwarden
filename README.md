Bitwarden
=========

Install and update the Bitwarden desktop client.

This role checks github for the latest version of the Bitwarden
desktop client, compares it to what's currently installed, and
installs or upgrades the client to the latest version.

Requirements
------------

An Internet connection.

Role Variables
--------------

None yet.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Keep Bitwarden updated with the latest version.

    - hosts: desktop-hosts
      roles:
	  - bitwarden

License
-------

BSD

Author Information
------------------

[Andrew Arensburger](https://www.ooblick.com/)
