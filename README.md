# Projeto-Servidor-com-Aplicacoes

PROJETO SERVIDOR DE SITES E OUTROS SERVIÇOS.

Construção do projeto completo, desde a parte de infrestrutura até a virtualização de sistemas para subir sites e aplicações.

A infraestrutura consiste em:

Servidor > Router board PPPOE para gereciar as portas das virtualizações > IP PUBLICO FIXO > DNS GRATIS já configurado SSL em cada server virtual.

SERVIDOR: 2x intel xenom (modelo) (quantidade)GB RAM - 2 HDs 1TB para sistemas em RAID2 - 2 HDs 1TB HAID2 para bakups
SISTEMA: PROXMOX para virtualizar os servidores
SISTEMAS VIRTUALIZADOS: 
    UBUNTU SERVER PARA SITE ARNALDO CARPI (CarpiServer1)
    UBUNTU SERVER PARA SITE GUTEMBERG (GuguServer1)

Esse repositorio esta responsavel pelo CarpiServer1