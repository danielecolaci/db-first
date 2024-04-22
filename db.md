DB_NAME: auto_dealer

Table name: auto

- id | INDEX | INT | UNIQUE | AUTO_INCREMENT
- avaible | TINYINT | NOTNULL
- brand | VARCHAR(50) | NOTNULL
- model | VARCHAR(30) | NOTNULL
- version | VARCHAR(20) | NOTNULL
- year | YEAR | NOTNULL
- price | MEDIUMINT | NOTNULL
- description | TEXT | NULL
- doors | TINYINT | NOTNULL
- fuel | VARCHAR(20) | NOTNULL
- km | FLOAT(7,2) | NOTNULL
- kw | MEDIUMINT | NULL
- lengh | FLOAT(4,2) | NOTNULL
- width | FLOAT(4,2) | NOTNULL
- color | VARCHAR(50) | NOTNULL
- optionals | TEXT | NULL
- image | VARCHAR(255) | NULL
- note | MEDIUMTEXT | NULL