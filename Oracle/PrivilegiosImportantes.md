# Privilegios Importantes Oracle Database DCL    ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)

### Selec_catalog_role

- Esta role é usada principalmente para permitir que <strong>administradores</strong> ou <strong>usuários avançados</strong> acessem informações sobre o esquema do banco de dados, configurações, objetos, e outros metadados, sem dar acesso completo a todas as operações de administração.
- O SELECT_CATALOG_ROLE é um privilégio de sistema que concede ao usuário a capacidade de consultar tabelas e visualizações no esquema de catálogo de banco de dados.
- O SELECT_CATALOG_ROLE é um privilégio de sistema que acesso a algumas tabelas do dicionário de dados, como DBA_TABLES, DBA_VIEWS, DBA_USERS, DBA_OBJECTS, DBA_TAB_COLUMNS...etc.

```sql
GRANT SELECT_CATALOG_ROLE TO <nome_do_usuario>;
```
### Resource

- O recurso é um privilégio de sistema que concede ao usuário a capacidade de criar tabelas, procedimentos armazenados, funções, pacotes, sinônimos, sequências, gatilhos e visualizações.
- O RESOURCE fornece os seguintes privilégios:
  - CREATE CLUSTER
  - CREATE INDEX
  - CREATE OPERATOR
  - CREATE PROCEDURE
  - CREATE SEQUENCE
  - CREATE TABLE
  - CREATE TRIGGER
  - CREATE TYPE
  - CREATE VIEW

```sql
GRANT RESOURCE TO <nome_do_usuario>;
```
### Connect

- O CONNECT é um privilégio de sistema que concede ao usuário a capacidade de se conectar ao banco de dados.

```sql
GRANT CONNECT TO <nome_do_usuario>;
```