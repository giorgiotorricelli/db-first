# esercizio db-first

## schema tabella `vehicles` 

| Nome Colonna | Tipo | Attributi | Indici |
|---|---|---|---|
| `id` | `INT` | `AUTO_INCREMENT` | `PK` |
| `model` | `VARCHAR(25)` | `NOT NULL` | `IX` |
| `is_used` | `BOOLEAN` | `DEFAULT FALSE, NOT NULL` |  |
| `km` | `MEDIUMINT UNSIGNED` | `DEFAULT 0, NOT NULL` | `IX` |
| `four-by-four` | `BOOLEAN` | `DEFAULT FALSE, NOT NULL` |  |
| `class` | `VARCHAR(2)` | `DEFAULT 0, NOT NULL` |  |
| `cc_displacement` | `SMALLINT UNSIGNED` | `NOT NULL` |  |
| `cv_displacement` | `SMALLINT UNSIGNED` | `NOT NULL` |  |
| `year` | `YEAR` | `NOT NULL` | `IX` |
| `base_price` | `MEDIUMINT UNSIGNED` | `NOT NULL` | `IX` |
| `is_hybrid` | `BOOLEAN` | `DEFAULT FALSE, NOT NULL` |  |
| `is_full_electric` | `BOOLEAN` | `DEFAULT FALSE, NOT NULL` |  |
| `brand` | `VARCHAR(15)` | `NOT NULL` | `FK(brands_id)` |
| `consumption_min` | `DECIMAL(3,1) UNSIGNED` | `NOT NULL` |  |
| `consumption_max` | `DECIMAL(3,1) UNSIGNED` | `NOT NULL` |  |
| `electric_range` | `DECIMAL(3,1) UNSIGNED` | `NULL` |  |
| `in_stock` | `TINYINT UNSIGNED` | `DEFAULT 0, NOT NULL` |  |
| `colour` | `MEDIUMINT UNSIGNED` | `NOT NULL` |  |


