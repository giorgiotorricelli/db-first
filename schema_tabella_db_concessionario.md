# esercizio db-first

## schema tabella `vehicles` 

| Nome Colonna | Tipo | Attributi | Indici |
|---|---|---|---|
| `id` | `INT` | `AUTO_INCREMENT` | `PK` |
| `model` | `VARCHAR(30)` | `NOT NULL` | `IX` |
| `new` | `BOOLEAN` | `DEFAULT TRUE, NOT NULL` |  |
| `used` | `BOOLEAN` | `DEFAULT FALSE, NOT NULL` |  |
| `km` | `MEDIUMINT UNSIGNED` | `DEFAULT 0, NOT NULL` |  |
| `four-by-four` | `BOOLEAN` | `DEFAULT FALSE, NOT NULL` |  |
| `class` | `VARCHAR(2)` | `DEFAULT 0, NOT NULL` |  |
| `cc_displacement` | `SMALLINT UNSIGNED` | `NOT NULL` |  |
| `cv_displacement` | `SMALLINT UNSIGNED` | `NOT NULL` |  |
