# 🗄️ Disciplina Banco de Dados

Este repositório reúne as atividades desenvolvidas ao longo da disciplina **Banco de Dados**, parte do curso de **Pós-Graduação em Tecnologia Java**.  

A disciplina tem como objetivo capacitar o aluno na **modelagem, implementação e manipulação de bancos de dados relacionais**, além de introduzir o uso de **JPA (Java Persistence API)** para integração entre aplicações Java e o banco.

---

## 🧠 Conceitos-chave

- **Modelagem de Dados (DER/BDML):** definição de entidades, atributos e relacionamentos.  
- **Normalização:** aplicação das formas normais para evitar redundâncias e anomalias de atualização.  
- **Linguagem SQL:** criação, manipulação e consulta de dados utilizando DDL, DML e DQL.  
- **Chaves Primárias e Estrangeiras:** integridade referencial entre tabelas.  
- **Consultas avançadas:** uso de `JOIN`, `GROUP BY`, `HAVING`, subconsultas e funções agregadas.  
- **Persistência com JPA:** mapeamento objeto-relacional e uso de anotações (`@Entity`, `@Id`, `@GeneratedValue`).  
- **Consultas com JPQL:** filtragem e manipulação de dados via linguagem orientada a objetos.  
- **Relacionamentos JPA:** mapeamentos `@OneToOne`, `@OneToMany`, `@ManyToOne`, `@ManyToMany`.  
- **Boas práticas de modelagem e performance:** uso adequado de índices, tipos de dados e transações.

---

## 🛠️ Tecnologias utilizadas

| Ferramenta | Descrição |
|-------------|------------|
| 🐬 **MariaDB / MySQL** | Banco de dados relacional utilizado nas atividades |
| ☕ **Java SE + JPA (Hibernate)** | Framework de persistência para integração com o banco |
| 🧱 **JDBC** | API nativa para conexão e manipulação de dados |
| 🧰 **IDE** | NetBeans / IntelliJ IDEA / Eclipse |
| 💾 **Ferramentas de modelagem** | DBML, Workbench ou Draw.io para diagramas |

---

## 📚 Atividades da Disciplina Banco de Dados

### 1️⃣ Modelagem Conceitual — Entidades e Relacionamentos
**Resumo:**  
Criação do **Diagrama Entidade-Relacionamento (DER)** e identificação das **chaves primárias e estrangeiras**.  
- Definição das entidades principais e seus atributos.  
- Identificação dos relacionamentos (`1:1`, `1:N`, `N:M`).  
- Aplicação das **formas normais** para evitar redundância.  

**Exemplo prático:**  
Modelagem de um sistema de vendas com tabelas de `Cliente`, `Produto`, `Pedido` e `ItemPedido`.

---

### 2️⃣ Criação do Banco de Dados (DDL)
**Resumo:**  
Implementação da modelagem no banco com comandos **SQL DDL**.  
- `CREATE DATABASE`, `CREATE TABLE`, `ALTER TABLE`.  
- Criação de chaves primárias e estrangeiras (`PRIMARY KEY`, `FOREIGN KEY`).  
- Definição de tipos de dados e restrições (`NOT NULL`, `UNIQUE`).  

**Exemplo prático:**  
Criação física do banco modelado na atividade anterior.

---

### 3️⃣ Manipulação de Dados (DML)
**Resumo:**  
Trabalha os comandos de inserção e atualização.  
- `INSERT INTO`, `UPDATE`, `DELETE`.  
- Controle de integridade referencial.  
- Transações simples (`COMMIT`, `ROLLBACK`).  

**Exemplo prático:**  
População do banco com dados de exemplo e atualização de registros.

---

### 4️⃣ Consultas SQL (DQL)
**Resumo:**  
Uso de consultas simples e avançadas.  
- `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`, `HAVING`.  
- Funções agregadas (`SUM`, `AVG`, `COUNT`, `MIN`, `MAX`).  
- `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`.  
- Subconsultas (`SELECT` dentro de `SELECT`).  

**Exemplo prático:**  
Consulta de total de vendas por cliente e listagem de produtos mais vendidos.

---

### 5️⃣ Atividade JPA — Criação de Entidades e Mapeamentos
**Resumo:**  
Introdução à **Java Persistence API (JPA)**.  
- Criação das entidades Java com anotações `@Entity`, `@Id`, `@Column`.  
- Mapeamento das chaves primárias e relacionamentos.  
- Uso do `persistence.xml` para configuração da unidade de persistência.  

**Exemplo prático:**  
Classe `Cliente` e `Pedido` com relacionamento `@OneToMany`.

---

### 6️⃣ Atividade JPA — Consultas com JPQL
**Resumo:**  
Execução de consultas usando **JPQL** (Java Persistence Query Language).  
- Uso de `EntityManager` e `TypedQuery`.  
- Consultas com `WHERE`, `ORDER BY` e `JOIN FETCH`.  
- Diferença entre SQL tradicional e JPQL.  

**Exemplo prático:**  
Busca de pedidos por cliente e listagem de produtos com filtro de preço.

---

### 7️⃣ Integração Java + Banco via JPA (CRUD completo)
**Resumo:**  
Criação de um pequeno sistema Java que realiza operações **CRUD (Create, Read, Update, Delete)**.  
- Uso de DAO ou Repository para persistência.  
- Métodos genéricos de inserção, atualização e exclusão.  
- Tratamento de exceções de persistência.  

**Exemplo prático:**  
Sistema console ou desktop que permite cadastrar clientes, produtos e pedidos.

---

### 8️⃣ Atividade Final — Sistema com Regras de Negócio e Consultas
**Resumo:**  
Síntese da disciplina, integrando modelagem, SQL e JPA.  
- Implementação completa de um sistema de gestão (ex.: vendas, biblioteca, academia).  
- Regras de negócio aplicadas em consultas.  
- Relacionamentos complexos e uso de `JOIN FETCH`.  

**Exemplo prático:**  
Sistema que permite listar clientes com pedidos em aberto e calcular valores totais por período.

---

## 🧾 Resumo Final

> A disciplina de **Banco de Dados** consolidou o entendimento dos conceitos relacionais, modelagem, consultas e integração com aplicações Java.  
> O aluno finaliza o módulo apto a projetar, criar e manipular bancos de dados reais, aplicando **boas práticas de modelagem e persistência com JPA**, base essencial para o uso de frameworks como **Spring Data JPA** e **Hibernate** em aplicações enterprise.

---
