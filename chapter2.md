---
title: Something a little more in-depth
description: >-
  Learning things about SQL


---
## WHERE clauses

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

Write a query to fetch all the information for each movie in the database that was released after 1950.




`@solution`
```{sql}
select * from movies WHERE release_year > 1950;
```






---
## A Video Exercise on SQL

```yaml
type: VideoExercise
lang: sql
xp: 50
skills: 1
key: 142894c0a8
```

`@projector_key`
undefined

---
## Insert exercise title here

```yaml
type: TabExercise

xp: undefined

key: 6262ceec52
```













