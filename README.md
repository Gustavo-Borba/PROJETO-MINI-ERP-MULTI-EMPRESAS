# Mini ERP Multiempresas

Projeto de banco de dados desenvolvido em Oracle Database, utilizando SQL e PL/SQL.

O sistema simula um ERP multiempresas, com processos de cadastro, estoque, produção, compras, vendas, financeiro, fiscal e recursos humanos.

## Tecnologias

* Oracle Database
* SQL
* PL/SQL
* Oracle SQL Developer

## Estrutura do projeto

```text
mini-erp-multiempresas/
├── 01_tablespace/
├── 02_tables/
├── 03_sequences/
├── 04_constraints_indexes/
├── 05_load/
├── 06_triggers/
├── 07_functions/
├── 08_procedures/
├── 09_views/
└── 10_queries/
```

## Modelagem

O banco utiliza:

* Modelagem relacional
* Chaves primárias e estrangeiras
* Chaves compostas
* Constraints de integridade
* Índices
* Estrutura multiempresa

## Procedures

Implementação de processos e regras de negócio utilizando PL/SQL.

Exemplos:

* Procedure de apontamento de produção
* Procedure de geração de notas fiscais
* Validação de dados
* Tratamento de exceções
* Controle de transações

## Triggers

Automação de regras diretamente no banco de dados.

Exemplos:

* Geração de identificadores com sequences
* Geração de matrículas
* Numeração de pedidos
* Numeração de notas fiscais
* Controle de numeração por empresa

## Functions

Functions desenvolvidas para processamento de dados no banco.

* Function MD5 utilizada no carregamento de dados para fins didáticos

## Views

Views utilizadas para facilitar consultas e consolidar informações de diferentes tabelas.

* V_FUNCIONARIO
* V_FATURAMENTO

## Queries

Consultas SQL demonstrando diferentes recursos da linguagem, incluindo:

* SELECT e filtros
* INNER JOIN
* LEFT JOIN
* GROUP BY
* HAVING
* Funções de agregação
* Subqueries
* CASE
* Consultas envolvendo múltiplas tabelas
* Consultas voltadas para processos de negócio

As queries foram organizadas por tipo para facilitar a consulta do projeto.

## Módulos

O banco contempla os seguintes módulos:

* Cadastros
* Estoque
* Produção
* Compras
* Vendas
* Financeiro
* Fiscal
* Recursos Humanos
* Segurança
* Auditoria

## Dados

O projeto possui dados fictícios para demonstração dos processos e consultas.

## Objetivo

Projeto desenvolvido para prática e demonstração de conhecimentos em Oracle Database, SQL, PL/SQL, modelagem relacional, consultas SQL e implementação de regras de negócio diretamente no banco de dados.
