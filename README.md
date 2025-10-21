# DIO - Trilha .NET - Banco de Dados

## Visão Geral
Este projeto é a implementação prática dos conhecimentos adquiridos no módulo de Banco de Dados da **Formação .NET Developer** da DIO. O objetivo central foi atuar como responsável pelo banco de dados de um sistema de filmes e desenvolver um conjunto de consultas SQL para fins de análise e recuperação de dados.

O foco foi na utilização de comandos SQL para extrair informações específicas, manipular dados e trabalhar com relacionamentos complexos entre tabelas.

## Contexto do Banco de Dados (Schema)

O banco de dados, denominado `Filmes`, armazena informações sobre filmes, atores e seus gêneros. As tabelas foram modeladas para suportar relacionamentos de *muitos para muitos* (N:N), replicando um cenário comum em sistemas de gerenciamento de conteúdo.

![Diagrama banco de dados](Imagens/diagrama.png)

O banco de dados foi preparado através da execução do script `Script Filmes.sql`.

## Consultas Desenvolvidas

Para atender às necessidades de análise de dados, foram desenvolvidas **12 consultas SQL** que demonstram proficiência em: filtros (`WHERE`), ordenação (`ORDER BY`), agregação (`GROUP BY`) e a união de dados de múltiplas tabelas (`JOIN`).

Abaixo estão as 12 consultas implementadas para extrair as seguintes informações:

1.  **Listagem Básica:** Nome e ano de todos os filmes.
2.  **Ordenação:** Nome e ano dos filmes, ordenados por ano (crescente).
3.  **Filtro Simples:** Nome, ano e duração do filme "De Volta Para o Futuro".
4.  **Filtro por Ano:** Filmes lançados no ano de 1997.
5.  **Filtro por Faixa:** Filmes lançados após o ano 2000.
6.  **Filtro Composto e Ordenação:** Filmes com duração entre 100 e 150 minutos, ordenados pela duração (crescente).
7.  **Agregação e Agrupamento:** Quantidade de filmes lançados por ano, agrupando e ordenando por ano (decrescente).
8.  **Filtro por Atributo:** PrimeiroNome e UltimoNome de Atores do gênero masculino.
9.  **Filtro e Ordenação:** PrimeiroNome e UltimoNome de Atores do gênero feminino, ordenados pelo PrimeiroNome (crescente).
10. **Relacionamento JOIN (N:N):** Nome do filme e seu gênero.
11. **Relacionamento e Filtro:** Nome do filme cujo gênero é "Mistério".
12. **Relacionamento Detalhado:** Nome do filme, PrimeiroNome, UltimoNome e o Papel (personagem) dos atores.

## Habilidades Demonstradas

* **SQL Server:** Utilização da linguagem T-SQL.
* **Modelagem Relacional:** Entendimento e manipulação de relacionamentos N:N.
* **Consultas Avançadas:** Uso de `INNER JOIN`, `LEFT JOIN`, `WHERE`, `ORDER BY` e funções de agregação (`COUNT`) com `GROUP BY`.
* **Análise de Dados:** Criação de *queries* para atender requisitos de *Business Intelligence* e extração de dados analíticos.