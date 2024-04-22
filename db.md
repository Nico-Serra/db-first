# Instruction

Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

DB_NAME: Car dealership

Table name: Cars


- ID | BIGINT | PK | NOTNULL | AI | UNIQUE
- Car license plate | VARCHAR(15) | PK | NOTNULL | UNIQUE
- Brand | NOTNULL | VARCHAR (20)
- Model | NOTNULL | VARCHAR (20)
- Car body | NULL | VARCHAR (20)
- Car type | NOTNULL | VARCHAR (20) | DEFAULT('used')
- Km | NOTNULL | MEDIUMINT
- Price | NOTNULL | MEDIUMINT
- Description | NULL | TEXT
- Year | NOTNULL | YEAR
- Type of gearbox | NOTNULL | VARCHAR (20)
- Fuel | NOTNULL | VARCHAR (20)
- Power | NOTNULL | VARCHAR (20)
- Condition of car | NULL | VARCHAR (50)
- Doors | NOTNULL | TINYINT
- Test Drive | NULL | TINYINT
- Owners | NULL | TINYINT
- Color | NULL | VARCHAR (20)
- pic of car  | NOTNULL | VARCHAR (255)
