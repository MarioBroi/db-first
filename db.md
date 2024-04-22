# Instructions
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

DB_name: Car_dealer

Table name: cars

- id | INDEX | INT or BIGINT | PK | NOTNULL | UNIQUE | AI
- image | VARCHAR(255) | NULL | DEFAULT ('<https://lorempicsum.com/myimge.jpg>')
- brand | VARCHAR(20) | NOTNULL
- model | INDEX | VARCHAR(50) | NOTNULL | UNIQUE 
- price | MEDINT | NOT NULL
- description | TEXT | NULL
- status | TINYINT | NOT NULL | DEFAULT (0)
- variant | VARCHAR(50) | NULL
- color | VARCHAR(15) | NULL
- warranty | TINYINT | NOTNULL
- km | MEDIUMINT | NOTNULL
- year | YEAR | NOTNULL
- production_year | YEAR | NULL
- engine | VARCHAR(50) | NOTNULL
- power | VARCHAR(10) | NOTNULL
- transmission | VARCHAR(10) | NOTNULL
- body_type | VARCHAR(10) | NOTNULL
- seats | TINYINT | NOTNULL
- doors| TINYINT | NOTNULL
- owners | VARCHAR(10) | NULL
- number-of-owners | TINYINT | NULL
- location | VARCHAR(30) | NOT NULL
- emissions | VARCHAR(10) | NULL
- registration | YEAR | NULL