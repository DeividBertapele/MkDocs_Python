# Documentando os projetos com MKDocs


## MkDocs -  https://www.markdownguide.org/getting-started/

- É um projeto para criação de documentações para projetos. Seja feita em python, pode ser usada para qualquer projeto de documentação e até sites estáticos.

- O formato usado para documentações do MkDocs é o MarkDown(MD)

## Comandos básicos: CLI

- Para criar o projeto:
    - mkdocs new <nome do projeto> ou
    - mkdocs new .  (colocando o ponto para criar automático)

- Colocar um servidor no ar para vermos a documentação no browser:
    - mkdocs serve

- Criar as páginas estáticas usando md como referência:
    - mkdocs build

- Faz deploy no github pages:
    - mkdocs gh-deploy

------------------------------------------------------------

- Pequeno problema:
    - Embora todas as bibliotecas sigam as especificação básica, não são todas as funcionalidades estendidas que funcionan em todos os lugares e para isso temos:
        - pip install pymdown-extensions

------------------------------------------------------------

## MkDocs Themes :
    - https://github.com/mkdocs/mkdocs/wiki/MkDocs-Themes


## Material-theme:
    - https://squidfunk.github.io/mkdocs-material/getting-started/


## Mermais.js
    - https://mermaid.js.org/#/


---------------------------------------------------------

## MkDocstrings

- https://github.com/mkdocstrings/mkdocstrings

--------------------------------------------------------

![Captura de tela 2023-01-13 143313](https://user-images.githubusercontent.com/43301551/212398925-f535bc09-6db7-4ffc-bb00-0208a5e5f311.png)
