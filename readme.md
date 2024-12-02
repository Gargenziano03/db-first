# DB STRUCTURE 
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario
# Table structure
- ID | BIGINT - AUTO_INCREMENT - PK (UNIQUE, NOTNULL)
- marca | VARCHAR(20) - NOTNULL
- modello | VARCHAR(10) - NOTNULL
- targa | VARCHAR(7) - NOTNULL
- anno | YEAR - NULL
- km percorsi | CHAR(13) - NULL
- prezzo | CHAR(13) DEFAULT


