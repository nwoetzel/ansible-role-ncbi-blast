ansible-role-ncbi-blast
=======================

[![Build Status](https://travis-ci.org/nwoetzel/ansible-role-ncbi-blast.svg?branch=master)](https://travis-ci.org/nwoetzel/ansible-role-ncbi-blast)
This role installs [ncbi-blast](http://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE_TYPE=BlastDocs)

Requirements
------------

There are no specific requirements.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: nwoetzel.ncbi-blast, ncbi_blast_version: "2.4.0" }

License
-------

[GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

Author Information
------------------

Please see [nwoetzel@github](https://github.com/nwoetzel)
