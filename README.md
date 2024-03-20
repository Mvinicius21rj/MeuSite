<h1>Meu Site</h1>

> Status:Developing

comando para construir o container docker com volume direcionado para a pasta meu site, e outro volume de configuração nginx

docker run --name docker-nginx -p 80:80 -v ~/Portifolio/MeuSite:/usr/share/nginx/html -v ~/docker-nginx/default.conf:/etc/nginx/conf.d/default.conf -d nginx
