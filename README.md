## PROJETO SERVIDOR DE SITES E OUTROS SERVIÇOS.

Esse projeto consiste na construção de forma completa de um servidor web, desde a parte de infraestrutura até a virtualização de sistemas, configuração de ambientes,
instalação e configuração de aplicações para hospedar sites e caso necessário, outros serviços.

### A infraestrutura consiste em:

1. - `RouterBoard:` Acesso a internet via PPPoE + ip publico fixo. (Essa RB também gerencia as portas dos servidores e o firewall.)
2. - `SERVIDOR:` 1x Intel Celeron (modelo), 4GB RAM - 1 SSD 128GB, (Será necessário fazer um upgrade futuramente para rodar serviços mais pesados) 

### Sistemas virtualizados via PROXMOX:

1. `Ubuntu Server:` (SITE DE ESTUDO - PROJETO CARPI SERVER (SITE PARA TUTORIAIS ESCRITOS E CURSOS))
    - `Repositório:` [Repositório PROJETO CARPI SERVER](https://github.com/arnaldocarpi/Site-principal)
    - `Mantenedores:` [Github Arnaldo Carpi](https://github.com/arnaldocarpi)
    - `Fixtures:` Site atualizado automaticamente via Github Actions quando houver alguma alteração na branche main;
        
    - `Implantar:` 
        - Construção do site (em andamento);
        -   SSL

Acesse o site BETA: [PROJETO CARPI SERVER](http://carpi.serveblog.net/)

2. `Ubuntu Server:` (SITE DE ESTUDO - PROJETO CARPI NOTES (SITE PARA CRIAÇÃO DE NOTAS))
    - `Repositório:` [Repositório PROJETO CARPI NOTES - FRONT](https://github.com/arnaldocarpi/Carpi-Notes-FRONT)
    - `Repositório:` [Repositório PROJETO CARPI NOTES - API](https://github.com/arnaldocarpi/Carpi-Notes-API)
    - `Mantenedores:` [Github Arnaldo Carpi](https://github.com/arnaldocarpi)
    - `Fixtures:` Site atualizado automaticamente via Github Actions quando houver alguma alteração na branche main;
        
    - `Implantar:` 
        -   SSL

Acesse o site: [PROJETO CARPI NOTES](http://carpinotes.ddns.net:81/)
