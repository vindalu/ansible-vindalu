Role Name
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------
The following variables are available:

    - vd_ess_hos
    - vd_ess_port
    - vd_ess_index

    - vd_api_prefix

    - vd_auth_enabled
    - vd_ldap_url
    - vd_search_base
    - vd_bind_dn
    - vd_bind_password

    - cluster_name
    - cluster_members

Dependencies
------------

- geerlingguy.java
- euforia.elasticsearch

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: euforia.vindaloo }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
