# Sistema de Gestão para Instituição de Cursos "Saber Mais"

Este repositório contém o modelo lógico e os scripts SQL para a criação, manipulação e teste do banco de dados do nosso minimundo (Instituição de Cursos).

## 🚀 Como Usar

Para recriar e testar o banco de dados localmente:

1. **Criação da Estrutura:** Execute o script `01_estrutura.sql` no seu ambiente MySQL (via Workbench, DBeaver, etc.) para criar o esquema e as tabelas.
2. **Carga de Dados:** Execute o script `02_dados_teste.sql` para popular as tabelas com a massa de dados (20 alunos, 5 cursos, 5 professores, etc.).
3. **Manipulação e Teste:** Execute os scripts `script_dml_select.sql` e `script_dml_update_delete.sql` para testar as funcionalidades DML.

## 📝 Documentação e Modelo

* **Modelo Lógico (DER):** O modelo é composto por 5 entidades principais (Alunos, Professores, Cursos, Turmas e Matrículas).
* **Normalização:** O modelo está totalmente normalizado até a Terceira Forma Normal (3FN), garantindo integridade e mínima redundância de dados.

## 🗃️ Scripts SQL Incluídos

* `01_estrutura.sql`: Comandos DDL (CREATE TABLE)
* `02_dados_teste.sql`: Comandos DML (INSERT INTO) para carga de dados iniciais.
* `script_dml_select.sql`: Consultas e JOINs de teste.
* `script_dml_update_delete.sql`: Comandos UPDATE e DELETE para manipulação.
