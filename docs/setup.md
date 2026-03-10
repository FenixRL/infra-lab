Foi realizado teste de acesso remoto utilizando SSH.

Comando utilizado:

ssh rafa@192.168.56.101

O acesso ao servidor web-server foi realizado com sucesso.


#


Docker foi instalado no servidor web-server para execução de containers.

Comandos utilizados:

```
sudo apt update
sudo apt install docker.io -y
sudo docker run hello-world
```

#


Ansible foi instalado no servidor infra-server.

Comando: 

```
sudo apt install ansible -y
ansible --version
```

Função: automação de configuração e gerenciamento de servidores.


#


Foi criada chave SSH para permitir autenticação sem senha entre os servidores.

Com os seguintes Codigos:

ssh-keygen --> para gerar a chave
ssh-copy-id rafa@192.168.56.101 --> copiar para o web-server

Isso permite que o Ansible se conecte automaticamente ao web-server.
