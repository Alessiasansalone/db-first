# DB Used Car Dealer

table: cars

- id 
    - BIGINT
    - PK
    - AI
    - NULL
- Marca
    - VARCHAR(80)
    - NOTNULL
- Modello
    - VARCHAR(80)
    - NOTNULL
- Tipologia
    - VARCHAR(80)
    - NULL
- Immatricolazione
    - YEAR
    - NOTNULL
- Prezzo
    - DECIMAL(8,2)
    - NOTNULL
- Chilometri
    - MEDIUMINT
    - NOTNULL
- Potenza
    - SMALLINT
    - NULL
- Cilindrata
    - SMALLINT
    - NOTNULL
- Alimentazione
    - VARCHAR(80)
    - NOTNULL
- Cambio
    - VARCHAR(80)
    - NOTNULL
- Colore
    - VARCHAR(80)
    - NULL
- Città
    - VARCHAR(80)
    - NULL

# Correzione

table: cars

- id 
    - BIGINT
    - AI
    - NOTNULL
    - UNIQUE
- marca
    - VARCHAR(30)
    - NOTNULL
- modello
    - VARCHAR(20)
    - NOTNULL
- immatricolazione
    - YEAR
    - NOTNULL
- prezzo
    - DECIMAL(8,2)
    - NULL
- chilometri
    - MEDIUMINT
    - NOTNULL
- cilindrata
    - VARCHAR(20)
    - NULL
- alimentazione
    - VARCHAR(20)
    - NOTNULL
- cambio
    - VARCHAR(30)
    - NOTNULL
- colore
    - VARCHAR(30)
    - NULL
- optionals <!-- (R)DBMS -->
    - VARCHAR
    - NULL
- note
    - TEXT
    - NULL