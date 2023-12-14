# Lightweight ADR

# Title
Use Relational Databases such as MySQL for storing data.

## Status
Accepted

## Context
We needed to choose a database that would be suitable for storing the data in a consistent and easily recoverable format. 

## Decision
Use a Relational Database

## Consequences
The data is kept in terms of tuples and attributes --- tuples and attributes create a relation that may be changed using SQL. It is both open source and commercial products are available.
