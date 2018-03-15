---
title: The Very Basics of SQL
description: >-
  


---
## The Very Basics of SQL

```yaml
type: NormalExercise
lang: sql
xp: 100
skills: 1
key: 996049c965
```

At its core, SQL is an expressive programming language, allowing you to issue commands that make sense in plain English. Or, at least that's how I like to think about SQL.

`@instructions`
Say you have a table `movies`. The table contains columns for `id`, `title`, `release_year`, `director`, and `country`. 

Write a query to fetch all the information for each movie in the database.

`@hint`




`@solution`
```{sql}
select * from movies;
```





