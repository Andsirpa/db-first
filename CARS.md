<!-- # CONSEGNA
 Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario -->

# "cars" TABLE STRUCTURE

| FIELD           | TYPE        | ATTRIBUTES                                   | INDEXES     |
| --------------- | ----------- | -------------------------------------------- | ----------- |
| id              | INT         | AUTO INCREMENT, (NOT NULL, UNSIGNED, UNIQUE) | PRIMARY KEY |
| brand           | VARCHAR(20) | NOT NULL, DEFAULT("unknown")                 |             |
| model           | VARCHAR(50) | NOT NULL, DEFAULT("unknown")                 |             |
| KM              | INT         | NOT NULL                                     |             |
| production year | YEAR        | NOT NULL                                     |             |
| number plate    | CHAR(8)     | NOT NULL, UNIQUE                             |             |
| fuel type       | VARCHAR(20) | NOT NULL                                     |             |



