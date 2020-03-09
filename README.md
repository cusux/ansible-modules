# Ansible modules development sandbox

This project, `ansible-modules`, is my development branch for Ansible modules.  
Each module within this branch is placed according to the Ansible sections for both classic modules as well as placement in Ansible Collections.

Due to the migration of the classic Ansible development life-cycle in regards to plugins and modules to the new Ansible Collections, some namespaces will become part of precompile collections as of march 11th 2020.

For faster development and testing of initial custom modules, with or without their own namespace, this repository is created.

## Repository contents
```
├── community.general
│   └── plugins
│       └── modules
│           └── web_infrastructure
│               └── jenkins_ssh_cli_xml_import.py
├── LICENSE
└── README.md
```
