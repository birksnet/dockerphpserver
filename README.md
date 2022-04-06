# Sevidor Nginx e PHP
### Servidor para conteudo statico e dinamico em docker
Um servidor simples facil e pratico para disponibilizar conteudos staticos e dinamicos, com configuração simplificada em docker-compose e nginx.

## Requesitos
### UNICO REQUESITO E TER DOCKER INSTALADO!

### Iniciando servidor 
Para iniciar o servidor basta clonar o repositorio para um local desejado e iniciar o compose `docker-compose up -d`!
```
cd /var/www/html
git clone https://github.com/birksnet/dockerphpserver.git .
docker-compose up -d
```
Pronto! seu servidor já esta rodando !
Nessa demostração o servidor estara com os arquivos localizado em /var/www/html/app/php/public
> A pagina index estará sempre em `LOCAL/app/php/public/index.php`

> O conteudo statico estará sempre em `LOCAL/app/php/public/static`
