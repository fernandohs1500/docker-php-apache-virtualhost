## Instructions

1 - Instalar docker
2 - Instalar docker-compose (https://dl.bintray.com/docker-compose/master/)
	2.1 - mv docker-compose-Linux-x86_64 docker-compose
	2.2 - cp docker-compose /usr/local/bin/docker-compose
	2.3 - sudo chmod +x /usr/local/bin/docker-compose
	2.4 - Fechar terminal e abrir de novo
	2.5 - Verificar a versao -> docker-compose --version
3 - Parar apache da maquina local (Se tiver iniciado)

3.1 - Entrar na pasta do projeto do docker clonado

4 - sudo docker-compose build

5 - docker-compose up -d

6 - Clonar projetos licitanet_v2 e licitaweb_v2 para dentro da pasta web. 

7 - Entrar dentro da pasta web dentro do projeto licitanet_v2 e licitaweb_v2 e rodar o composer install.
7.1 - licitanet_v2 rodar -> chmod 777 var/logs/ 

