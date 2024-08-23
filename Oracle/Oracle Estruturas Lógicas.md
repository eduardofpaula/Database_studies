# Oracle DataBase Logic Structures ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)

## ESTRUTURAS LÓGICAS = Tabelas, Indices, Views, Procedures ->

### Segmentos: Segmentos são OBJETOS do banco de dados Oracle (Tabelas, Indices, Views, Procedures, etc)

### Datablocks = Unidade de armazenamento de dados no Oracle Database

### Extents = Conjunto de Datablocks (8 a 128 datablocks) -> Extents são alocados automaticamente pelo Oracle Database

### Tabelas -> Segmentos de Dados -> Extents -> Datablocks

![alt text](image.png)

### OQUE SIGNIFICA CRUD E COMANDOS DDL DML DCL?

- CRUD: Create, Read, Update, Delete
São operações básicas de um sistema de banco de dados Oracle
- DDL: Data Definition Language (CREATE, ALTER, DROP, TRUNCATE)
São comandos SQL para definição de dados no banco de dados Oracle
- DML: Data Manipulation Language (SELECT, INSERT, UPDATE, DELETE)
- DCL: Data Control Language (GRANT, REVOKE)
São comandos SQL para manipulação de dados no banco de dados Oracle

## ESTRTURAS FISICAS = Datafiles, Controlfiles, Redo Log FileS, Archive Log Files, ASM, Trace Files e PSWD

### Datafiles: Estruturas fisicas de armazenamento de dados do banco de dados Oracle. Os datafiles compoem as tablespaces e a soma dos seus tamanhos é o total de tamanho da tablespace

### Controlfiles: Arquivos de controle do banco de dados Oracle. Os controlfiles contem informações sobre a estrutura do banco de dados Oracle

### Redo Log Files: Arquivos de log de transações do banco de dados Oracle. Os redo log files são responsáveis por garantir a consistência dos dados no banco de dados Oracle

### Archive Log Files: Arquivos de log de transações arquivados do banco de dados Oracle. Os archive log files são responsáveis por garantir a recuperação de dados no banco de dados Oracle

### ASM: Automatic Storage Management. O ASM é uma tecnologia do banco de dados Oracle que gerencia o armazenamento de dados no banco de dados Oracle

### Trace Files: Arquivos de rastreamento do banco de dados Oracle. Os trace files contem informações sobre erros e problemas no banco de dados Oracle

### PSWD: Password Files. Os password files são arquivos de senha do banco de dados Oracle. Os password files são utilizados para autenticação de usuários no banco de dados Oracle

### Arquivos de Backup: Arquivos de backup do banco de dados Oracle. Os arquivos de backup são utilizados para recuperação de dados no banco de dados Oracle

