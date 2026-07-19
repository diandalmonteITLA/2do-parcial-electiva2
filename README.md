# Laboratorio de Ansible

## Objetivo de la práctica
El objetivo de este laboratorio es configurar un entorno local de automatización utilizando Ansible para gestionar de manera simultánea múltiples servidores simulados a través de contenedores Docker (Ubuntu 24.04), aplicando conceptos de inventarios, variables del sistema (facts), bucles y ejecución condicional.

## Comandos para iniciar los contenedores
```bash
docker compose up -d
```

## Comando para ejecutar el playbook
```bash
ansible-playbook -i inventory.ini playbook.yml
```

