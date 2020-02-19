# Web services project with Spring Boot and JPA / Hibernate

## Objetives

- Create Spring Boot Java project
- Implement domain model
- Structure logical layers: resource, service, repository
- Configure test database (H2)
- Populate the database
- CRUD - Create, Retrieve, Update, Delete
- Exception handling

## Project Checklist:

- [x] Local project created
- [x] User entity and resource
- [x] H2 database, test profile, JPA
- [x] JPA repository, dependency injection, database seeding
- [x] Order, Instant, ISO 8601
- [x] OrderStatus enum
- [x] Many-to-many association with JoinTable
- [x] OrderItem, many-to-many association with extra attributes
- [x] Product-OrderItem one-to-many association
- [x] Payment, one-to-one association
- [x] Subtotal & Total methods
- [x] User insert
- [x] User delete
- [x] User update
- [x] Exception handling - findById
- [x] Exception handling - delete
- [x] Exception handling - update
- [x] Create Heroku app & provision PostgreSQL
- [x] Install local PostgreSQL
- [x] Dev profile
- [x] Get SQL script from local PostgreSQL
- [x] Run SQL Script
- [x] Deploy app to Heroku

## Domain model
![](https://i.imgur.com/jqJ8z0f.png)

## domain instance
![](https://i.imgur.com/ReeHTr0.png)

## Logical Layers
![](https://i.imgur.com/IOgpxCm.png)
