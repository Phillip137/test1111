# test1111

---
- hosts:
all
  connection: local
  gather_facts: no
  
  tasks:
  - name: show version 
    nxos_command:
      host: '{{ inventory_hostname
}}'
      commands:
      - show ip int br


