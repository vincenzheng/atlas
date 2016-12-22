1.add 'altas.py' to ansible server: '/usr/lib/python2.6/site-packages/ansible/module_utils'

2.add a 'atlas' folder in '/usr/lib/python2.6/site-packages/ansible/modules/core/network'

3.add '__init__.py , atlas_command.py, atlas-config.py, atlas-facts.py' to ansible server to '/usr/lib/python2.6/site-packages/ansible/modules/core/network/atlas'

4.configure ansible.cfg, hosts as 'hosts, ansible.cfg' files

5.write a playbook as 'provision.yaml'
