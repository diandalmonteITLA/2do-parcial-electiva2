# Laboratorio de Ansible

## Objetivo de la práctica
El objetivo de este laboratorio es configurar un entorno local de automatización utilizando Ansible para gestionar de manera simultánea múltiples servidores simulados a través de contenedores Docker.

## Comandos para iniciar los contenedores
```bash
docker compose up -d
```

## Comando para ejecutar el playbook
```bash
ansible-playbook -i inventory.ini playbook.yml
```

## Capturas de pantalla
<img width="1277" height="445" alt="Screenshot 2026-07-18 233747" src="https://github.com/user-attachments/assets/28132248-92db-44b7-8dca-4b1bbb7e590a" />
<img width="1280" height="533" alt="Screenshot 2026-07-18 233759" src="https://github.com/user-attachments/assets/b4dba0af-3b73-44f6-bc10-27d2e5b72f37" />
<img width="1280" height="434" alt="Screenshot 2026-07-18 233826" src="https://github.com/user-attachments/assets/896953ed-676b-4ca2-b1e7-3c106422fe41" />

