# Lab_05_AnguitaV_2
Repositorio nuevo creado, debido a problemas de merging de mi Y app, con el repositorio creado de manera automática.

# Lab 05

In this lab, you have to create the basic tables and models of the 'Y' program's database, using Migrations and ActiveRecord. Additionally, you should be able to perform simple queries to the database.

## Instructions

### Create Tables

1. Create a migration for the `users` table with the following fields:

- `name` (string)
- `email` (string)
- `password` (string)
- `created_at` (datetime)
- `updated_at` (datetime)

2. Create a migration for the `posts` table with the following fields:

- `title` (string)
- `content` (text)
- `user_id` (integer)
- `published_at` (datetime)
- `answers_count` (integer)
- `likes_count` (integer)
- `created_at` (datetime)
- `updated_at` (datetime)

All this table should have a model associated with them.

### Seed Population

1. Create a `seeds.rb` file in the `db` directory and populate the database with 5 users and 10 posts. All information should be random.

### Queries

Write the code for the following queries:

1 - Get all users

```ruby
### Code here
```

2 - Get the user with id 3

```ruby
### Code here
```

3 -  Get the posts with more than 100 likes

```ruby
### Code here
```

4 - Get the posts with more than 10 answers and less than 20 likes

```ruby
### Code here
```

5 - Get the users created in the month of January

```ruby
### Code here
```

6 - Change the name of the user with id 3 to "Juan"

```ruby
### Code here
```

7 - Delete the post with id 5

```ruby
### Code here
```
