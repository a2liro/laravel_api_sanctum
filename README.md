# Projeto base para APIs em Laravel usando Sanctum

## 🛠️ Abrir e rodar o projeto.
Clone o repositório
`git clone https://github.com/a2liro/laravel_api_sanctum.git`

Navegando até a pasta clonada 
`cd laravel_api_sanctum`

Instalando as dependencias
`composer install`

Rodando as migrations
`php artisan migrate`

Iniciando o servidor
`php artisan serve`

Criando novo usuário
```
// http://localhost:8000/api/create-account
{
    "name":"Andre Liro",
    "email":"meu@email.com",
    "password":"Sup3rSecreto"
}
```

Fazendo login
```
// http://localhost:8000/api/signin
{
    "email":"meu@email.com",
    "password":"Sup3rSecreto"
}
```
