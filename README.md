# Alreo

## Descrição
O Alreo é ferramenta voltada para o auxílio no aprendizado da álgebra relacional. O Alreo é gratuito, completamente em português, e foi desenvolvido 
para operar na web, proporcionando uma interface intuitiva que permite a construção e execução de consultas em álgebra relacional utilizando notações semelhantes às dos livros-texto de bancos de dados.

A arquitetura do sistema conta com três módulos principais: Interface de usuário(Front-end) elaborado em HTML com página única, Servidor (Back-end) elaborado com o framework Flask em Python e o radb (Back-end) que é o pacote utilizado para interpretar e traduzir a consulta em álgebra relacional para o SQL. O servidor implementa nativamente o SGBD SQLite3 em Pyhton.

Atualmente, existem ferramentas que interpretam a álgebra relacional, auxiliam na correção sintática e permitem a visualização dos resultados das consultas. No entanto, muitas dessas ferramentas não estão disponíveis em formato web e requerem a instalação prévia de um SGBD, o que exige a instalação desses programas em um computador local. A criação de um sistema que ofereça um ambiente virtual na web, que retorne os resultados das consultas e que disponibilize uma interface simples para a criação e manipulação em um SGBD real é elaborado com esse projeto para superar esses desafios.

## Instrução de instalação

### Pré requisitos
 Python 3.11.4

### Etapas

Intalando o pacote radb
