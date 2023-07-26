| COLONNA             | TIPO              | ATTRIBUTI                  |
| ------------------- | ----------------- | -------------------------- |
| ID                  | BIGINT            | PRIMARY KEY AUTO_INCREMENT |
| NOME AZIENDA        | VARCHAR(50)       | NOT NULL                   |
| NOME AUTO           | VARCHAR(50)       | NOT NULL                   |
| MARCA AUTO          | VARCHAR(50)       | NOT NULL                   |
| TARGA               | VARCHAR(10)       | NOT NULL , UNIQUE          |
| TELAIO              | VARCHAR(20)       | NOT NULL , UNIQUE          |
| IMMATRICOLAZIONE    | YEAR              | NOT NULL                   |
| KILOMETRI FATTI     | INT               | NOT NULL                   |
| PREZZO              | DECIMAL(10,2)     | NOT NULL                   |
| MOTORE              | VARCHAR (50)      | NULL                       |
| FOTO                | TEXT              | NULL                       |
| NUMERO PORTE        | TINYINT(1)        | NULL                       |
| NUMERO POSTI        | TINYINT(1)        | NULL                       |
| TIPO BENZINA        | BOOL / TINYINT(1) | NULL                       |
| PRIMO ACQUIESTO     | DATE              | NULL                       |
| ULTIMO PROPRIETARIO | VARCHAR(50)       | NULL                       |
| DESCRIZIONE AUTO    | TEXT              | NULL                       |
| NAZIONALITA         | CHAR(3)           | NULL                       |
| DATA DI ARRIVO      | DATE              | NULL                       |
| COLORE              | VARCHAR(30)       | NULL                       |
