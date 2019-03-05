mail4sysdown_n_up
=========

For pushing configuration for mail alert while linux server up and down.

Role Variables
--------------

you can define your customized alert script directory via scripts_dir (default is /opt/scripts), your mail via your_email and your local relay ip or mial server via realy_ip.

Dependencies
------------

need to have mail server or relay server for alert.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    ---
    - hosts: localhost
      sudo: yes
      roles:
        - role: mailme
          scripts_dir: /opt/scripts
          your_email: example@gmail.com
          relay_ip: x.x.x.x
...

Author Information
------------------

https://www.linkedin.com/in/lillian-phyoe-a4485113a/
