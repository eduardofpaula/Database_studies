# Sintaxe de comandos Oracle Database ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)

- Mostrar usuario
```sql
SHOW USER;
```

- Diferentes Selects
```sql
SELECT * FROM table_name;
SELECT column_name FROM table_name;
SELECT column_name FROM table_name WHERE condition;
SELECT column_name FROM table_name WHERE condition ORDER BY column_name;
```

- Criar tabela
```sql
CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    column3 datatype,
    ...
);
```

- Alterar tabela
```sql
ALTER TABLE table_name ADD column_name datatype;
ALTER TABLE table_name DROP COLUMN column_name;
ALTER TABLE table_name MODIFY column_name datatype;
```

- Deletar tabela
```sql
DROP TABLE table_name;
```

- Inserir dados
```sql
INSERT INTO table_name (column1, column2, column3, ...)
VALUES (value1, value2, value3, ...);
```

- Atualizar dados
```sql
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition;
```

- Deletar dados
```sql
DELETE FROM table_name WHERE condition;
```



