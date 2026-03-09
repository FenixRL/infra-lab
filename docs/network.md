# Configuração de rede

As máquinas virtuais utilizam duas interfaces de rede.

Adapter 1
Tipo: NAT
Função: acesso à internet.

Adapter 2
Tipo: Host-only
Função: comunicação interna entre servidores.

Essa configuração permite simular um ambiente de infraestrutura real com rede privada.


Para gerar o ip tive que fazer manualmente
sudo apt update
sudo apt install isc-dhcp-client

sudo dhclient enp0s8

ip a

Teste de conectividade realizado utilizando ping entre web-server e infra-server.

Na Maquina web-server o comando ping 192.168.56.102

Resultado: comunicação bem sucedida entre as máquinas virtuais.