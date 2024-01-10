# instalação

Recursos
Gestão de cursos
Cadastro e gerenciamento de alunos
Sistema de matrículas
Painel administrativo
Pré-requisitos

Antes de iniciar, garanta que você tenha instalado:
PHP >= 7.3
Composer
Node.js
NPM
Um servidor de banco de dados (MySQL, PostgreSQL, etc.)

Instalação
Siga os passos abaixo para instalar e configurar o projeto:

Clone o Repositório

git clone https://github.com/JoaoPCoutinho
cd JoaoPCoutinho
Instale as Dependências do PHP

composer install
Configure o Ambiente

Copie o arquivo .env.jpbank para um novo arquivo chamado .env e preencha as informações necessárias, como detalhes do banco de dados.

cp .env.example .env
Gere a Chave da Aplicação

php artisan key:generate
Migrações e Seeders

Execute as migrações para criar as tabelas no banco de dados. Se houver seeders, execute-os também.

php artisan migrate
php artisan db:seed # se necessário
Instale as Dependências do Node

npm install
npm run dev
Inicie o Servidor

php artisan serve
A aplicação estará rodando em http://localhost:8000

    #olámundoPHP
