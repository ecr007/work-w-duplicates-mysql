# Cacar-duplicados-MySql
Sacar todos los contenidos duplicados en la base de datos


#Codigo
SELECT name, COUNT(*) c FROM table GROUP BY name HAVING c > 1
