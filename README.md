# Schemas and relationships

## what is Schema

A database schema is the skeleton structure that represents the logical view of the entire database. It defines how the data is organized and how the relations among them are associated. It formulates all the constraints that are to be applied on the data.

A database schema defines its entities and the relationship among them. It contains a descriptive detail of the database, which can be depicted by means of schema diagrams. It’s the database designers who design the schema to help programmers understand the database and make it useful.

## Why / When we use Schema

Databases that are inefficiently organized suck up tons of energy and resources, tend to be confusing, and are hard to maintain and administer. That’s where database schema design comes into play.

Relational database systems heavily depend on having a solid database schema in place. The goals of good database schema design include:

- Reducing or eliminating data redundancy.
- Preventing data inconsistencies and inaccuracies.
- Ensuring the correctness and integrity of your data.
- Facilitating rapid data lookup, retrieval, and analysis.
- Keeping sensitive and confidential data secure, yet accessible to those who need it.


## Primary Key

A primary key is a field in a table which uniquely identifies each row/record in a database table. Primary keys must contain unique values. A primary key column cannot have NULL values.

The main purpose of primary key is to identify the uniqueness of a row

## Relationship Examples

- one to one
- one to many 
- many to many

![](https://i.imgur.com/aTVONYj.png)
