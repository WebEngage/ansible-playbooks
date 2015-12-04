Ansible Datadog Role
========

Install and configure datadog agent. Currently only handles base agent.

May extend to handle some service monitoring in the future.

Requirements
------------

Amazon Linux ami/Ubuntu/Redhat

Role Variables
--------------

- `datadog_api_key` - your datadog API key

Dependencies
------------
None

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: datadog-agent, datadog_api_key: "mykey" }

