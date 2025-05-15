# Cacar-duplicados-MySql
Sacar todos los contenidos duplicados en la base de datos


#Codigo
SELECT name, COUNT(*) c FROM table GROUP BY name HAVING c > 1


# Delete Duplicates

```sql
DELETE FROM gp_classes as t1 
INNER JOIN gp_classes AS t2 
ON t1.name = t2.name AND t1.id > t2.id
```
