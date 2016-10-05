FFMEG
=====

Installs ffmpeg

Requirements
------------

No special requirements.

Role Variables
--------------

* `ffmpeg_version`: Version to install
* `ffmpeg_install`: Location to install
* `ffmpeg_webproxy`: _(optional)_ Proxy information

Dependencies
------------

Ansible 1.9+

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ucsdlib.ffmpeg, ffmpeg_version: 3.1.3 }

License
-------

BSD 2 Clause

Author Information
------------------

John H. Robinson, IV  
The Library  
UC San Diego  
