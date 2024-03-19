> [!IMPORTANT]
> INTRO
####CODIGO SQL
SELECT CategoryName, Description FROM Categories;

> [!IMPORTANT]
> SYNTAX
####CODIGO SQL
SELECT City, Country FROM Customers;

> [!IMPORTANT]
> SELECT
####CODIGO SQL
SELECT CustomerName, City, Country FROM Customers;

> [!IMPORTANT]
> SELECT DISTINCT
####CODIGO SQL
SELECT DISTINCT Country FROM Customers;

> [!IMPORTANT]
> WHERE
####CODIGO SQL
SELECT CustomerName FROM Customers
WHERE Country='Mexico';

> [!IMPORTANT]
> ORDER BY
####CODIGO SQL
SELECT ProductName FROM Products
ORDER BY Price DESC;

> [!IMPORTANT]
> AND
####CODIGO SQL
SELECT CustomerName FROM Customers
WHERE Country = 'Germany'
AND City = 'Berlin'
AND PostalCode > 1200;

> [!IMPORTANT]
> OR
####CODIGO SQL
SELECT City, ContactName FROM Customers
WHERE Country = 'Germany' OR Country = 'Spain';

> [!IMPORTANT]
> NOT
####CODIGO SQL
SELECT CustomerName FROM Customers
WHERE NOT Country = 'Spain';

> [!IMPORTANT]
> INSERT INTO
####CODIGO SQL
INSERT INTO Customers (CustomerName, City, Country)
VALUES ('Luiza', 'Cristino Castro', 'Brasil');

> [!IMPORTANT]
> NULL VALUES
####CODIGO SQL
SELECT CustomerName, ContactName, Address
FROM Customers
WHERE Address IS NULL;

> [!IMPORTANT]
> UPDATE
####CODIGO SQL
UPDATE Customers
SET ContactName='Juan'
WHERE Country='Mexico';

> [!IMPORTANT]
> DELETE
####CODIGO SQL
DELETE FROM Customers WHERE CustomerName='Antonio Moreno Taquería';
