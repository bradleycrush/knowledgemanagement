# knowledgemanagement

## This product will be used to store data from multiple sources and create links between that data. Those likes will be searchable so a user can pull various data based on the established links.

## The initial use case that this is handling employee/contract data at Kontana. For handlign this, we will have concrete concepts (employees, customers, contracts, positions, etc). Each of those concepts will have attributes to describe it (Contract's have names, descriptions, recompete dates, open reqs, etc). Between those concepts we will have linkings (Contracts -> Positions, Positions -> Employees) 

### Concepts:
    - Contract
    - Employee
    - Position
    - Company

### Concept-Attributes
- Contract-Name
- Contract-Description
- Contract-Start
- Contract-End
- Employee-Name
- Employee-Hire-Date
- Employee-Medical-Plan
- Position-Hire-Date

### Concept-Links
- Employee - Position
- Position - Company

## Technologies used:
 - Graph database: Neo4j to start
 - Web frontend: Vue.js
 - Will run in docker containers
