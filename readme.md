Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

Table name: Cars

Table Colums:

- id | BIGINT PK AI NOTNULL UNIQUE
- brand | VARCHAR(30) | NOTNULL (porsche etc.)
- model | VARCHAR(30) | NULL (991)
- fuel | VARCHAR(15) | NULL (benzina)
- dors | TINYINT | NOTNULL (3)
- package | VARCHAR(30) | NULL (gt3)
- price | FLOAT (9,2) | NULL (234789)
- color | VARCHAR(30) | NULL (blu)
- image | VARCHAR(255) | NULL (https://mysite.test/image.png)
- description | TEXT | NULL (descrizione della macchina)
- year | YEAR | NULL (anno di uscita)
- status | VARCHAR(30) | NULL (nuova, usata, km0)
- km | MEDIUMINT | NULL (km correnti)
- emission | VARCHAR(20) | NULL (classe emissioni (euro6))
- traction | VARCHAR(15) | NULL (posteriore, integrale ecc)
- gear | VARCHAR(15) | NULL (automatico, manuale)
- consumption - VARCHAR(15) | NULL (consumi medi, specifici ecc)
