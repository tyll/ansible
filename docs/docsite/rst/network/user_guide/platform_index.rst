.. _platform_options:

****************
Platform Options
****************

Some Ansible Network platforms support multiple connection types, privilege escalation (``enable`` mode), or other options. The pages in this section offer standardized guides to understanding available options on each network platform. We welcome contributions from community-maintained platforms to this section.

.. toctree::
   :maxdepth: 2
   :caption: Platform Options

   platform_eos
   platform_ios
   platform_junos
   platform_nxos

.. _settings_by_platform:

Settings by Platform
================================

+----------------+-------------------------+----------------------+----------------------+-------------------+-------------------+
|..              |                         | ``ansible_connection:`` settings available                                          |
+----------------+-------------------------+----------------------+----------------------+-------------------+-------------------+
| Network OS     | ``ansible_network_os:`` | network_cli          | netconf              | httpapi           | local             |
+================+=========================+======================+======================+===================+===================+
| Cisco ASA      | ``asa``                 | since version 2.5    | N/A                  | N/A               | since version 2.4 |
+----------------+-------------------------+----------------------+----------------------+-------------------+-------------------+
| Arista EOS*    | ``eos``                 | since version 2.5    | N/A                  | since version 2.6 | since version 2.4 |
+----------------+-------------------------+----------------------+----------------------+-------------------+-------------------+
| Cisco IOS*     | ``ios``                 | since version 2.5    | N/A                  | N/A               | since version 2.4 |
+----------------+-------------------------+----------------------+----------------------+-------------------+-------------------+
| Cisco IOS XR*  | ``iosxr``               | since version 2.5    | N/A                  | N/A               | since version 2.4 |
+----------------+-------------------------+----------------------+----------------------+-------------------+-------------------+
| Junos OS*      | ``junos``               | since version 2.5    | since version 2.5    | N/A               | since version 2.4 |
+----------------+-------------------------+----------------------+----------------------+-------------------+-------------------+
| Cisco NX-OS*   | ``nxos``                | since version 2.5    | N/A                  | since version 2.6 | since version 2.4 |
+----------------+-------------------------+----------------------+----------------------+-------------------+-------------------+
| Nokia SR OS    | ``sros``                | since version 2.5    | N/A                  | N/A               | since version 2.4 |
+----------------+-------------------------+----------------------+----------------------+-------------------+-------------------+
| VyOS*          | ``vyos``                | since version 2.5    | N/A                  | N/A               | since version 2.4 |
+----------------+-------------------------+----------------------+----------------------+-------------------+-------------------+


`*` Maintained by Ansible Network Team
