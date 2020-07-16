# Framework CodeIgniter 4

## O que é CodeIgniter?

O CodeIgniter é uma estrutura da Web de pilha completa PHP, leve, rápida, flexível e segura.
Mais informações podem ser encontradas no [site oficial] (http://codeigniter.com).

Este repositório contém a versão distribuível da estrutura,
incluindo o guia do usuário. Foi construído a partir do
[repositório de desenvolvimento] (https://github.com/codeigniter4/CodeIgniter4).

Mais informações sobre os planos para a versão 4 podem ser encontradas em [o anúncio] (http://forum.codeigniter.com/thread-62615.html) nos fóruns.

O guia do usuário correspondente a esta versão da estrutura pode ser encontrado
[aqui] (https://codeigniter4.github.io/userguide/).

## Mudança importante com o index.php

O `index.php` não está mais na raiz do projeto! Foi movido para dentro da pasta * public *,
para melhor segurança e separação de componentes.

Isso significa que você deve configurar seu servidor da Web para "apontar" para a pasta * public * do seu projeto e
não para a raiz do projeto. Uma prática melhor seria configurar um host virtual para apontar para lá. Uma prática ruim seria apontar o servidor da Web para a raiz do projeto e esperar inserir * public /...*, como o restante de sua lógica e
estrutura são expostos.

** Por favor ** leia o guia do usuário para uma melhor explicação de como o CI4 funciona!
A atualização e implantação do guia do usuário é um pouco estranha no momento, mas estamos trabalhando nisso!

## Gerenciamento de repositório

Utilizamos os problemas do Github, em nosso repositório principal, para rastrear ** BUGS ** e rastrear pacotes de trabalho aprovados ** DEVELOPMENT **.
Usamos nosso [fórum] (http://forum.codeigniter.com) para fornecer SUPORTE e discutir
SOLICITAÇÕES DE RECURSOS.

Este repositório é de "distribuição", criado pelo nosso script de preparação de lançamentos.
Problemas com ele podem ser levantados em nosso fórum ou problemas no repositório principal.

## Contribuindo

Congratulamo-nos com as contribuições da comunidade.

Leia a seção [* Contribuindo para o CodeIgniter *] (https://github.com/codeigniter4/CodeIgniter4/blob/develop/contributing.md) no repositório de desenvolvimento.

## Requisitos do servidor

É necessário o PHP versão 7.2 ou superior, com as seguintes extensões instaladas:

- [intl] (http://php.net/manual/en/intl.requirements.php)
- [libcurl] (http://php.net/manual/en/curl.requirements.php) se você planeja usar a biblioteca HTTP \ CURLRequest

Além disso, verifique se as seguintes extensões estão ativadas no seu PHP:

- json (ativado por padrão - não desligue)
- [mbstring] (http://php.net/manual/en/mbstring.installation.php)
- [mysqlnd] (http://php.net/manual/en/mysqlnd.install.php)
- xml (ativado por padrão - não o desative)