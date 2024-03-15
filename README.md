<h2>Description</h2>
Thanks for checking my page, this repository contains examples all written by myself. 

<!DOCTYPE html> 
<html>
<body>
<!-- CONTENTS -->
<details>
  <summary>Content</summary>
  <ol>
  <ul>
    <li>Customer Data Exbtract</li> 
    <li>Using SELECT * FROM to:</li>
      <li>Select customers order by Country and City</li>
      <li>Select customers who are from Non-Germany countries</li>
      <li>Select customers from a city that starts with the letter 'b' and ends with the letter 's'</li>
      <li>Select customers from a city that starts with the letter 'a'</li>
      <li>Select customers whose names start with 'b', 'p' or 's'</li>
      <li>Select customers whose names start with 'b', 'p' or 's'</li>
      <li>Select all products with ProductNames between 'Côte de Blaye' and 'Geitost'
  
    <body>--data: w3school.com --import customerdata
CREATE TABLE CustomerData (CustomerID, CustomerName, ProductName, ContactName, Address, City, PostalCode, Country);

INSERT INTO CustomerData VALUES
('1', 'Alfreds Futterkiste', 'Côte de Blaye', 'Maria Anders', 'Obere Str. 57', 'Berlin', '12209', 'Germany'), 
('2', 'Ana Trujillo Emparedados y helados', 'Escargots de Bourgogne', 'Ana Trujillo', 'Avda. de la Constitución 2222', 'México D.F.', '05021', 'Mexico'), 
('3', 'Antonio Moreno Taquería', 'Filo Mix', 'Antonio Moreno', 'Mataderos 2312', 'México D.F.', '05023', 'Mexico'), 
('4', 'Around the Horn', 'Thomas Hardy', '120 Hanover Sq.', 'London', 'WA1 1DP', 'UK'), 
('5', 'Berglunds snabbköp', 'Fløtemysost', 'Christina Berglund', 'Berguvsvägen 8', 'Luleå', 'S-958 22', 'Sweden'), 
('6', 'Blauer See Delikatessen', 'Geitost', 'Hanna Moos', 'Forsterstr. 57', 'Mannheim', '68306', 'Germany'), 
('7', 'Blondel père et fils', 'Genen Shouyu','Frédérique Citeaux', '24, place Kléber', 'Strasbourg', '67000', 'France'), 
('8', 'Bólido Comidas preparadas', 'Gnocchi di nonna Alice', 'Martín Sommer', 'C/ Araquil, 67', 'Madrid', '28023', 'Spain'), 
('9', 'Bon app', 'Gorgonzola Telino', 'Laurence Lebihans', '12, rue des Bouchers', 'Marseille', '13008', 'France'), 
('10', 'Bottom-Dollar Marketse', 'Grandma's Boysenberry Spread', 'Elizabeth Lincoln', '23 Tsawassen Blvd.', 'Tsawassen', 'T2F 8M4', 'Canada'), 
('11', 'B\'s Beverages', 'Gravad lax', 'Victoria Ashworth', 'Fauntleroy Circus', 'London', 'EC2 5NT', 'UK'), 
('12', 'Lehmanns Marktstand', 'Guaraná Fantástica', 'Renate Messner', 'Magazinweg 7', 'Frankfurt a.M.', '60528', 'Germany');

SELECT * FROM CustomerData ORDER BY Country, City;

SELECT * FROM CustomerData WHERE NOT Country = 'Germany';

SELECT * FROM CustomerData WHERE CustomerName LIKE 'b%' AND CustomerName LIKE '%s';

SELECT * FROM CustomerData WHERE City NOT LIKE 'a%';

SELECT * FROM CustomerData WHERE CustomerName LIKE '%a';

SELECT * FROM CustomerData WHERE CustomerName LIKE 'b%' OR CustomerName LIKE 's%' OR CustomerName LIKE 'p%';

SELECT * FROM CustomerData WHERE City NOT LIKE '[acf]%';

SELECT * FROM CustomerData WHERE ProductName BETWEEN 'Côte de Blaye' AND 'Geitost';
  <html>

### Complete a survey form to help me better understand the rising popularity of online audio contents
[Link to the Form](https://docs.google.com/forms/d/e/1FAIpQLScSIJ7uNP060LRKCU9JwEeJ6w6G0a_JtTkOR9tLeRG_Tfn8QA/viewform)
