# proj_univesp_001
* Projeto de back-end do projeto integrador unives
* Tecnologias utilizadas 
     * Linguagem de programação: Python 3.9.1
     * Framework: Django 3.2.7
     * Ambiente virtual: Venv
     * Editor de Código: Visual Code Studio

## AGENDA 
* 02-10-2021
     * Criação do diretório do projeto 
     * Criação do Ambiente virtual 
     * Criação do projeto django
* 09-10-2021
     * Criação do App de alocação das páginas do projeto
     * Criação da template geral do site 
     * Criação do repositório git e git/github do projeto back-end
* 16-10-2021
     * Criação de documentação parcial do projeto back-end

## COMANDOS UTILIZADOS
* Comandos de construção do projeto
     * Criação do ambiente virtual
          ~~~python
          python -m venv venv
          ~~~
     * Instalação do framework Django
          ~~~python
          pip install django==3.2.7
          ~~~
     * Criação do Projeto Django
          ~~~python 
          django-admin startproject UNIVESP .
          ~~
     * Criação do aplicativo de armazenamento das páginas 
          ~~~python
          python manage.py startapp paginas
          ~~~
     * Execução do ambiente de debug Django
          ~~~python 
          python manage.py runserver
          ~~~
* Comandos Git utilizados 
     ~~~
     git init
     ~~~

     ~~~
     git status
     ~~~

     ~~~
     git add .
     ~~~

     ~~~
     git commit -m "comentarios"
     ~~~

     ~~~
     git push 
     ~~~
## OBSERVAÇÕES 
* O Framework django é uma ferramenta que tem por objetivo a simplificação do trabalho do desenvolvedor (desenvolvimento e gerenciamento de projetos back-end). Uma de suas principais dificuldades para o desenvolvedor iniciante é a quantidade de passos na configuração de projetos, o que pode torna-lo complexo a primeira vista.  

## REFERÊNCIAS BIBLIOGRAFICAS
* CHACON, Scott; STRAUB, Ben. Pro Git. 2. ed. EUA: Apress Open, 2020. 419 p. v. 1. ISBN 1484200772. E-book.
* MACIEL, Francisco. Python e Django: Desenvolvimento web Moderno e ágil. 1. ed. Brasil: Alta Books, 2020. 448 p. ISBN 9786555200973.
* HOLOVATY , Adrian; KAPLAN-MOSS, Jacob. The Definitive Guide to Django: Web Development Done Right. Second Edition. ed. EUA: Apress, 2009. 536 p. v. 1. ISBN 143021936X.
* RAMALHO, Luciano. Python Fluente: Programação Clara, Concisa e Eficaz. 1. ed. BRASIL: NOVATEC, 2015. 800 p. v. 1. ISBN 857522462X.

