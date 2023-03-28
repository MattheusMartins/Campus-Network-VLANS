# Campus-Network-VLANS

PARTE 1 - Power on, Hostname Configuration, Port Configuration, Passwords, VTP e VLANS, Acesso Ports e Trunk Ports

Configure a rede da seguinte forma:
1) Configurar nomes de host
2) Desligamento de interfaces não utilizadas
3) Configure a senha de habilitação e as senhas vty do cisco
4) Use o modo VTP transparente e domínio ccna
5) Adicione VLANS 10,20,30,100 ao banco de dados de VLAN
6) Configurar portas entre switches como troncos
7) Configurar portas de acesso em links para PCs
 
PARTE 2 - CDP & LLDP, Spanning Tree, EtherChannel, SVIs, IP Addresses e Routing

Configure a rede da seguinte forma:
1) Use CDP e LLDP para verificar links
2) Verifique quais portas estão encaminhando e bloqueando (spanning tree)
3) Otimize a spanning tree com Core1 sendo raiz para VLANs ímpares e Core2 como raiz para VLANS pares.
4) Configure o Etherchannel nos switches centrais
5) Os switches centrais devem suportar o roteamento interVLAN da camada 3:
VLAN 1 = Núcleo 1 = 10.1.1.251/24, Núcleo 2 = 10.1.1.252/24
VLAN 10 = Núcleo 1 = 10.1.10.251/24, Núcleo 2 = 10.1.10.252/24
VLAN 20 = Núcleo 1 = 10.1.20.251/24, Núcleo 2 = 10.1.20.252/24
VLAN 30 = Núcleo 1 = 10.1.30.251/24, Núcleo 2 = 10.1.30.252/24
VLAN 100 = Núcleo 1 = 10.1.100.251/24, Núcleo 2 = 10.1.100.252/24
6) Os switches da camada de acesso terão apenas endereços IP de gerenciamento na VLAN 1:
Switch 1 = 10.1.1.1/24
Switch 2 = 10.1.1.2/24
Switch 3 = 10.1.1.3/24

PARTE 3 - HSRP e EIGRP

Configure a rede da seguinte forma:
1) Configure e otimize o HSRP
2) Configure o EIGRP nos switches principais e no roteador ISR
3) Configurar PCs e Servidores:
PC1 na VLAN 10, IP = 10.1.10.10/24
PC2 na VLAN 20, IP = 10.1.20.10/24
PC3 na VLAN 30, IP = 10.1.30.10/24
Servidor1 na VLAN 100, IP = 10.1.100.100/24
4) Certifique-se de que os PCs possam executar ping entre si e no servidor
5) Verifique a conectividade entre switches e servidores e PCs
IP do roteador g0/0/0 = 10.1.1.253/24
g0/0/1 = DHCP 

PARTE 4 - NAT

Configure a rede da seguinte forma:
1) Configurar ISR g0/0/1 para DHCP
2) Habilitar NAT para rede interna NAT para interface ISR G0/0/1 (PAT)
3) Verifique se os PCs podem executar ping em cisco.com

<img src="https://raw.githubusercontent.com/MattheusMartins/Campus-Network-VLANS/main/1.PNG">
 
