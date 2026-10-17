## Definition & Constraints

- relational db= collection of info, organizing data into tables
- SQL= Structured Query Language -> access & manipulate data in relational db
- constraints in relational db to identify records & link tables:

| PK | FK |
|---|---|
| uniquely identify each record | appear in multiple tables |

|   | composite PK |
|---|---|
| cons | slower query | 
| WHEN TO USE? | many-to-many relationships |
| | weak entity (cant be uniquely identified): (hotel, room_num) |
|   | versioning data |

## Characteristics

1. tabular structure
2. schema-based: pre-defined 
    + names (relation & attributes)
    + domains (possible values)
    + PK, FK
    + rules (NOT NULL, UNIQUE, DEFAULT, CHECK)

3. ACID

|   |   |   |
|---|---|---|
| A | Atomicity | any step fails, entire rolls back, no saved changes |
| C | Consistency | transaction moves db from valid to valid obeying all rules, constraints, triggers |
| I | Isolation | concurrent transactions execute independently without revealing uncommitted data |
| D | Durability | committed transaction -> changes permanently saved & survive system crashes/power failures |

