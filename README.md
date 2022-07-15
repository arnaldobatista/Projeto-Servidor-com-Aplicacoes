# Projeto-Servidor-com-Aplicacoes

PROJETO SERVIDOR DE SITES E OUTROS SERVIÇOS.

Construção do projeto completo, desde a parte de infraestrutura até a virtualização de sistemas para subir sites e aplicações.

A infraestrutura consiste em:

1º - RouterBoard: Acesso a internet via PPPoE + ip publico fixo. (essa RB também gerencia as portas dos servidores e o firewall.)
2ª - SERVIDOR: 1x Intel Celeron (modelo), 4GB RAM - 1 SSD 128GB 


SERVIDOR: 1x Intel Celeron (modelo), 4GB RAM - 1 SSD 128GB
SISTEMA: PROXMOX para virtualizar os servidores
    SISTEMAS VIRTUALIZADOS: 
        UBUNTU SERVER (SITE DE ESTUDO - CLONE MELHORADO ÁREA DO ALUNO UNOPAR)
            APACHE PARA HOSPEDAR SITE
            LINK: https://loginunopar.zapto.org/
            REPOSITORIO: https://github.com/arnaldocarpi/carteirinha-unopar
            MANTENEDORES:
                https://github.com/arnaldocarpi
                https://github.com/OliveiraGutemberg
        FIXTURES: Site atualizado automaticamente via Github Actions quando a branche main for atualizada;
                  SSL habilitado
        TRABALHANDO: IP V6;
                     área de cadastro.
