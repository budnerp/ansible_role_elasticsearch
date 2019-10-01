# Ansible role for ElasticSearch 6
Ansible role for ElasticSearch 6 for CentOS 7

## What's inside?
- ElasticSearch 6.x on port `9200`
    ```
    sudo /usr/share/elasticsearch/bin/elasticsearch -V
    ```
- Data stored in the `/var/lib/elasticsearch`
- Configuration files are located in `/etc/elasticsearch`

## Tested on

## Installation
1. Navigate to Ansible's roles folder
2. Add the repo to git modules
    ```
    git submodule add https://github.com/budnerp/ansible_role_elasticsearch.git ansible_role_elasticsearch
    ```
3. Add the role to Ansible's playbook file
    ```    
    roles:
    [...]
        - ansible_role_elasticsearch
    [...]
    ```

## Other links

## TO DO
-[ ] add dependencies 
-[ ] discover: discovery.zen.* settings

## License
Copyright (c) We Are Interactive under the MIT license.