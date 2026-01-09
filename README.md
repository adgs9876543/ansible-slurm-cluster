# Ansible Slurm Cluster
Este repositorio contiene roles de Ansible para desplegar y configurar un cluster Slurm con autenticación LDAP y almacenamiento compartido NFS.

## Roles incluidos:
* **common**: Instalación de paquetes base.
* **ldap**: Configuración de usuarios de red.
* **nfs**: Montaje automático de homes.
* **slurm**: Configuración del demonio de cómputo y munge.

## Instalación
```bash
ansible-galaxy install adgs9876543.ansible_slurm_cluster
