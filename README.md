# obu_automation

*Créer un nouvel host sur Cobbler*:

```bash ansible-playbook ~/obu-automation/playbooks/cobbler_create_host.yml```

*Après le boot du raspberry -->*

*Configurer le raspberry et installer OBU*:

```bash ansible-playbook ~/obu-automation/playbooks/raspberry_config_init.yml```

*Installer OBU (seulement)*:

```bash ansible-playbook ~/obu-automation/playbooks/raspberry_obu_init.yml```
