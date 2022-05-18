# Presto

<style>
  h1 {
    counter-reset: h2
  }
  h2 {
    counter-reset: h3
  }
  h2:before {
    counter-increment: h2;
    content: counter(h2) ". "
  }
  h3:before {
    counter-increment: h3;
    content: counter(h2) "." counter(h3) ". "
  }
</style>

[TOC]

</br>

## SQL

+ Catalog

```sql
show catalogs;
```

+ Schema

```sql
show schemas from <catalog>;
```

+ Table

```sql
show tables from <catalog>.<schema>;
show create table <catalog>.<schema>.<table>;
```
