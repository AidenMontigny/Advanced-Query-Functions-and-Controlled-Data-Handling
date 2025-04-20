<h1> Advanced Query Functions and Controlled Data Handling </h1>

<h2>Description</h2>
This project focuses on enhancing SQL query functionality and implementing controlled data handling to support targeted marketing and business application development. Several advanced SQL tasks were completed to manage and manipulate data within a relational database. It began with a conditional query using `IF...THEN` logic to determine whether more than ten styles of the Road-650 bicycle were available in inventory. A `DECLARE` and `SET` statement was then used to create a dynamic variable for color filtering, initially set to “Black,” allowing flexible adjustments for future promotions. The query was expanded to include `Quantity` and `ListPrice` fields and filtered to show only items in the “Finished Goods Storage” location. A `CASE` statement was later introduced to calculate a `SalesPrice` field, applying a 10% discount to products with over 100 units in stock and 5% to all others. Finally, a stored procedure named `GetRegion` was created using the `Address`, `StateProvince`, and `SalesTerritory` tables to return the corresponding region based on city input, tested via an `EXECUTE` statement. This project demonstrates the use of intelligent SQL query development and procedural logic to optimize data flow and support business insights.
<br />

<h2>Languages and Utilities Used</h2>

- <b> SQL </b> 

<h2>Environments Used </h2>

- <b> SQL Server Management Studio </b>

<h2>Project walk-through:</h2>
<p align="left">
<p> The marketing department requested an analysis to determine if the Road-650 bicycle <br/> currently has more than 10 available styles. </p>
Below is the query used to meet their request:  <br/><br/>
  <img src="Screenshot 2025-04-19 144313.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
<p> The marketing department decided to feature only black-colored Road-650 bicycles in <br/> the sales promotion, with the possibility of modifying the sale in the future. </p>
Below is the query used to meet their request:  <br/><br/>
  <img src="Screenshot 2025-04-19 144313.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
<p> Building on the previous activity, the marketing department requested to include the <br/> "Quantity" and "ListPrice" for each product. Additionally, they wanted the results to be filtered to only show items in "Finished Goods Storage." </p> 
Below is the query used to meet their request:  <br/><br/>
  <img src="Screenshot 2025-04-19 144313.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
<p> Building on the previous activity, the marketing department decided to apply a discount <br/>based on stock levels. Products with more than 100 units in stock would receive a 10% discount, while all other products would receive a 5% discount. A CASE statement was created to modify the "ListPrice" and generate a new field called "SalesPrice," which reflects the applicable discount based on the product's stock quantity. </p>
Below is the query used to meet their request: <br/><br/>
  <img src="Screenshot 2025-04-19 144313.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
<p> For the business application under development, management requested the creation of <br/> a stored procedure that returns the corresponding region when a specific city is selected. This functionality enables faster and more efficient data retrieval for users. </p>
Below is the query used to meet their request: <br/><br/>
  <img src="Screenshot 2025-04-19 144313.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>

  
