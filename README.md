# Common Ansible Tasks
This repository contains Ansible task modules performing some common tasks for both Debian and Redhat families.

## Getting Started
1.  Download tasks repo into the folder with playbooks:
```bash
git clone https://github.com/ParanoidRat/ansible-common-tasks.git tasks
```

2.  Reference task modules in a playbook:
```yaml
tasks:
- import_tasks: tasks/task_module.yml
  vars:
    module_var: abc
```
## Requirements
*   Ansible 2.4

## Tested On
*   CentOS 7.3
*   Ubuntu 16.04 LTS

## Authors
*   [ParanoidRat][1]

## License
The work is licensed under the CC-BY-SA 4.0 License. Unless otherwise stated, modifications are also licensed under the CC-BY-SA 4.0 License. See the [LICENSE.md](LICENSE.md) file for details and specific licensing of the modifications.

You should have received a copy of the license along with this work (see the [CC-BY-SA-4.txt](CC-BY-SA-4.txt) file for details). If not, see [here][2].

[1]: https://github.com/ParanoidRat
[2]: https://creativecommons.org/licenses/by-sa/4.0/legalcode
