
## Rodar o projeto
Clone Repositório
```sh
git clone https://github.dev/especializati/laravel-10-rest-api.git app-laravel
```
```sh
cd app-laravel/
```


Crie o Arquivo .env
```sh
cp .env.example .env
```
Delete o Arquivo .git
```sh
rm -f .git
```

Suba os containers do projeto
```sh
docker-compose up -d
```


Acessar o container
```sh
docker-compose exec app bash
```


Instalar as dependências do projeto
```sh
composer install
```


Gerar a key do projeto Laravel
```sh
php artisan key:generate
```


Acessar o projeto
[http://localhost:8989](http://localhost:8989)
