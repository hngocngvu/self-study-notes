# DE 
- development, implementation & maintenance of systems & processes
- take in raw data -> produce high-quality & consistent info 
- support downstream tasks (analysis & ML)

![alt text](img/de_cycle.png)

#### DE skills & activities
- optimize along costs, agility, scalability, simplicity, reusability, interoperability

## Generation: Source Systems
- changes -> break pipeline & analytics

#### Key considerations

|||
|---|---|
|WHAT?| source characteristics|
| | data persistence: long-term, temporary, quicky deleted|
| | generation rate (time, speed) |
| | data consistency (unexpected nulls, formatting)|
| | schema design |
| | data duplication|
| | error occurence frequency|
|HOW? | pulling frequency|
| | latency|
| | stateful systems: data= periodic snapshots (current state of a dataset) or change data capture events (individual change made to the db)?|
| | impact of data reading on its performance|
|DEPENDENCIES| data provider for downstream consumption|
| | characteristics of upstream data dependencies|
|RELIABILITY| data-quality check-in for late/missing data|
| SCHEMA EVOLUTION | schema change management |




