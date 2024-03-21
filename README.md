<h1>Meu Site</h1>

> Status: Developing

<h3>Intuito</h3>
Projeto de site pessoal para apresentar os projetos e aprendizado de estudos como desenvolvedor

<h3>Sobre o projeto</h3>Este repositorio esta hospedado em uma maquina AWS, configurado com docker e nginx

> Configuração Docker

comando para iniciar o container docker com volume direcionado para a pasta MeuSite, e outro volume de configuração nginx
docker run --name docker-nginx -p 80:80 -v ~/Portifolio/MeuSite:/usr/share/nginx/html -v ~/docker-nginx/default.conf:/etc/nginx/conf.d/default.conf -d ngi
docker restart docker-nginx
