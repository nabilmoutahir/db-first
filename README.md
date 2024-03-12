# TRACCIA

nome repo: db-first
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## "cars" TABLE STRUCTURE

| FIELD      | TYPE        | ATTRIBUTES                | INDEX       |
| ---------- | ----------- | ------------------------- | ----------- |
| id         | INT         | NOT NULL , AUTO_INCREMENT | PRIMARY KEY |
| brand      | VARCHAR(20) | NOT NULL                  |             |
| model      | VARCHAR(20) | NOT NULL                  |             |
| year       | YEAR        | NOT NULL                  |             |
| VIN        | CHAR(17)    | NOT NULL UNSIGNED         | INDEX       |
| kilometers | MEDIUMINT   | NOT NULL, FLOAT(I, D)     |             |
| horsepower | TINYINT     | NOT NULL                  |             |
| stock      | TINYINT     | NOT NULL, UNSIGNED        |             |
| cost       | MEDIUMINT   | NOT NULL, FLOAT(I, D)     |             |
| price      | MEDIUMINT   | NOT NULL, FLOAT(I, D)     |             |
| abstract   | TEXT        | NULL                      |             |
