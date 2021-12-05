---
- hosts: localhost
  tasks:
      - name: install apache
        apt: 
           name=apache2
           state=latest
        become: yes
      - name: restart apache2
        service:
            name: apache2
            state: restarted
