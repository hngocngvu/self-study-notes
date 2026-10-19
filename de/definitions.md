- schemaless= no predefined schema the data must conform

|periodic snapshots|change data capture events|
|---|---|
|current state of a dataset|individual changes made to the db|

||master data|transactional data|golden record|
|---|---|---|---|
|definition|describe transactions (what was involved)| records of business events|the single, trusted version of a business record|
|example|   |   |   |


|data lineage|data governance|
|---|---|
|the process of tracking the flow of data over time| data management discipline (quality, security, availability)|

|schema-agnostic|flexible schema|enforced schema|
|---|---|---|
|systems, databases, or processes not requiring a rigid data schema| data varying in shapes without restrictions| data matching a rigit, predefined blueprint|
||schema-on-read|schema-on-write|
