# Bookstore project
Made by Tokenov Bekzhan 21B030933\
We are going to do "Bookstore" where you can buy and sell books.
## REST API
```sh
POST /book
GET /book
GET /book/:id
PUT /book/:id
DELETE /book/:id
```
## DB Structure
![schema](https://github.com/nrsu/golang-midterm/assets/75430472/c9425a7f-09c0-4dfc-9c37-ea4a6ae0448b)
```sh
// Use DBML to define your database structure
// Docs: https://dbml.dbdiagram.io/docs

Table Book {
  id integer [primary key]
  created_at timestamp
  updated_at timestamp
  deleted_at timestamp
  name string
  author string
  publication string
}
```
