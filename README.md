# Database Insights

Este repositório contém uma visão geral sobre Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL), focando no papel de um Engenheiro de Dados.

## Índice
1. [Bancos de Dados Relacionais (SQL)](#bancos-de-dados-relacionais-sql)
2. [Bancos de Dados Não Relacionais (NoSQL)](#bancos-de-dados-não-relacionais-nosql)
3. [Comparação SQL vs NoSQL](#comparação-sql-vs-nosql)
4. [Conclusão](#conclusão)

## Bancos de Dados Relacionais (SQL)

### Definição
Bancos de Dados Relacionais utilizam uma estrutura de tabela para organizar dados em linhas e colunas. Exemplos incluem MySQL, PostgreSQL, Oracle, e Microsoft SQL Server.

### Características
- **Schema Rígido:** Estrutura de dados pré-definida.
- **SQL (Structured Query Language):** Linguagem padrão para manipulação e consulta de dados.
- **ACID:** Atomicidade, Consistência, Isolamento e Durabilidade garantem transações seguras.

### Vantagens
- **Consistência de Dados:** Ideal para aplicações onde a integridade dos dados é crucial.
- **Relacionalidade:** Facilita a criação de relações complexas entre dados.

### Exemplos de Uso
- Sistemas Bancários
- Sistemas de Gestão Empresarial (ERP)
- Aplicações de e-commerce

## Bancos de Dados Não Relacionais (NoSQL)

### Definição
Bancos de Dados Não Relacionais armazenam dados de forma não estruturada, podendo ser em documentos, chave-valor, grafos, ou colunas. Exemplos incluem MongoDB, Cassandra, Redis, e Neo4j.

### Características
- **Schema Flexível:** Estrutura de dados dinâmica e flexível.
- **Modelos Diversos:** Documentos, Chave-Valor, Grafos, Colunas.
- **BASE:** Basicamente Disponível, Estado Suave, Eventualmente Consistente.

### Vantagens
- **Escalabilidade Horizontal:** Facilita o aumento de capacidade adicionando mais servidores.
- **Performance:** Otimizado para grandes volumes de dados e alta velocidade de leitura/escrita.

### Exemplos de Uso
- Aplicações Web de Alta Escala
- Análise de Dados em Tempo Real
- Redes Sociais

## Comparação SQL vs NoSQL

| Aspecto          | SQL                                           | NoSQL                                             |
|------------------|-----------------------------------------------|---------------------------------------------------|
| Estrutura        | Tabelas com linhas e colunas                  | Documentos, Chave-Valor, Grafos, Colunas          |
| Flexibilidade    | Menos flexível (schema rígido)                | Mais flexível (schema dinâmico)                   |
| Escalabilidade   | Vertical                                      | Horizontal                                        |
| Consistência     | ACID                                          | BASE                                              |
| Exemplos         | MySQL, PostgreSQL, Oracle, SQL Server         | MongoDB, Cassandra, Redis, Neo4j                  |

## Conclusão

Os Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) têm seus prós e contras. A escolha entre eles depende dos requisitos específicos do projeto, como a necessidade de consistência dos dados, flexibilidade do schema, e escalabilidade.

---

Espero que essas informações sejam úteis no seu aprendizado e desenvolvimento como Engenheiro de Dados!
