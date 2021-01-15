# upLexisTest

## [Linkedin](http://www.linkedin.com/in/nicolas-yomaha)

## Tecnologias utilizadas

* Xampp
* Laravel 8
* PHP 7.4
* HTML5
* CSS3 
* SCSS (Sass)
* Bootstrap 4
* Regex
* MySQL
* SQL

## Instalação do projeto

1. Instale [Xampp](https://www.apachefriends.org/es/index.html)
1. Instale globalmente [Composer](https://getcomposer.org)
1. Instale globalmente [Laravel](https://laravel.com/docs/8.x#initial-configuration) 
1. Baixe o .rar com o projeto e coloque-o na pasta htdocs do xampp. Descompacte-o
1. Mude a configuração do apache na pasta raiz, passe de htdocs para a pasta public/ que está dentro do projeto que descompactou
1. Abra o xampp e inicie o apache e o mysql
1. Creie na DDBB MySql uma tabela de nome uplexis utf8-general-ci
1. Instale [Nodejs](https://nodejs.org) Assim você tem acesso ao npm que ya bem junto com ele
1. Entre no cmd na pasta raiz do projeto. Execute os comandos: 
    1. php artisan migrate
    1. php artisan db:seed
    1. composer require laravel/ui
    1. php artisan ui bootstrap
    1. npm install && npm run dev
1. Caso você tenha algum problema de configuração, você pode verificar o archivo .env do projeto

## Utilização

Para utilizá-lo, basta abrir um navegador, digitar localhost como url, registrar-se como usuário ou utilizar o usuário criado por padrão, que é o usuário admin, senha admin, Vá para a busca de produtos, digite a marca do carro. Você será redirecionado para a tela com o resultado de sua pesquisa. Caso tenha feito mais pesquisas, a lista terá o acúmulo dos resultados.
