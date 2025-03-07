# ansible-apps_opensearch

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_opensearch-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_opensearch)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_opensearch.svg)](https://github.com/lotusnoir/ansible-apps_opensearch/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_opensearch?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_opensearch)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_opensearch)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_opensearch)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Description](#description)
- [Requirements](#requirements)
- [Role variables](#role-variables)
- [Examples](#examples)
- [License](#license)
- [Author Information](#author-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Description

Deploy Opensearch using ansible.
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_opensearch
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_opensearch


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
