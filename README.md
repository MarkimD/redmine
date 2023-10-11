# redmine

CÓDIGO PARA ACESSAR PASTAS DO REDMINE O DOCKER
docker exec <container> ls

CÓDIGO PARA ACESSAR AS PASTAS
docker exec -it <container> /bin/bash
redmine# ls -la

CÓDIGO PARA CRIAR PASTA DE TEMAS PERSONALIZADO NO AMBIENTE REDMINE
mkdir public/themes/cti_tema

CÓDIGO PARA INSTALAR O VIM NO AMBIENTE
1 - apt-get update
2 - apt-get install vim

CÓDIGO ENVIAR ARQUIVO PARA PASTA REDMINE
docker cp .\ <ARUIVO> IMAGE_REDMINE:/<PASTA A SER ENVIADA>










