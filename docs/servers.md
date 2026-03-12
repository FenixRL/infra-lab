# Servidores do laboratório

## web-server

Sistema: Ubuntu Server 24.04
IP: 192.168.56.101
RAM: 2GB
CPU: 2

Função na infraestrutura:

- execução de containers
- hospedagem de servidor web
- monitoramento do sistema

Serviços instalados:

- Docker
- Nginx (container)
- Netdata

---

## infra-server

Sistema: Ubuntu Server 24.04
IP: 192.168.56.102
RAM: 2GB
CPU: 2

Função na infraestrutura:

- gerenciamento dos servidores
- execução de automações com Ansible
- acesso remoto via SSH

Ferramentas instaladas:

- Ansible
- SSH


# 

Tive que colocar os códigos:

```
sudo apt update
sudo loadkeys br
```
para teclado funcionar no modelo ABNT
