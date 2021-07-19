<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Sobre o Projeto
Este projeto tem como objetivo fornecer alguns comandos adicionais à interface de linha de comando do Laravel para manipular a estrutura das camadas de Serviço e Reopositório: Service Layer / Repository Pattern.

## Sobre o Laravel
<i>Laravel é um framework de aplicação web com sintaxe expressiva e elegante. Uma estrutura da web fornece uma estrutura e um ponto de partida para a criação de seu aplicativo, permitindo que você se concentre na criação de algo incrível enquanto suamos nos detalhes.</i> <a href="https://laravel.com/docs/8.x#meet-laravel">Documentação do Laravel</a>

## Sobre o Artisan
<i>"Artisan é a interface de linha de comando incluída no Laravel. O Artisan existe na raiz do seu aplicativo como o artisanscript e fornece uma série de comandos úteis que podem ajudá-lo enquanto você constrói seu aplicativo."</i> <a href="https://laravel.com/docs/8.x/artisan#introduction">Documentação do Laravel</a>

Para ver uma lista de todos os comandos Artisan disponíveis, você pode usar o listcomando:


    php artisan list

## Sobre o Reposittory Pattern
<a href="https://asperbrothers.com/blog/implement-repository-pattern-in-laravel/">Reposittory Pattern</a> é um padrão de projeto que visa adicionar uma camada de abstração entre a camada dos modelos (Models) e os controladores (Controllers) ou ainda da camada de serviço (Services). Dessa forma, cada Model possui uma classe Repository correspondente. Ademais, numa abordagem padrão essas classes ficam na pasta app/Repositories/Eloquent e são injetadas por meio de Interfaces, que se encontram em app/Repositories/Contracts.

## Sobre a Service Layer
A Camada de Serviço ou <a href="https://luis-barros-nobrega.medium.com/laravel-service-layer-with-dtos-and-validators-2c6303899a57">Service Layer</a> é um padrão de projeto que visa abstrair a lógica ou regra de nogócio da aplicação, que normalmente se encontra na camado dos controladores, para uma nova camada: a Camada de Serviço. Nesse contexto, em uma abordagem padrão cada controlador possui sua classe de serviço para quem delega as funções que normalmente deveria exercer. Dessa forma, os controladores se limitam a gerenciar o que entra por meio das rotas (requests) e o que será retornado a partir de então (responses). Assim, além de o projeto ficar mais estruturado é garantido também um desacoplamento da regra de negócio e o framework em uso, pois a regra de negócio estará em uma camada criada exclusivamente pelo desenvolvedor.  
