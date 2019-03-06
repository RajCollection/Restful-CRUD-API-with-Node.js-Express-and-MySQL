# Restful-CRUD-API-with-Node.js-Express-and-MySQL

npm install
npm start

--------------------------------------------------
start mysql
mysql> source path_of_schema.sql_file/schema.sql

-------------------------------------------

APIs

 - Get All (GET): http://localhost:6001/products                                                   
 
 - Get one (GET): http://localhost:6001/products/1                                                 
 
 - Add product (POST): http://localhost:6001/products/add           
         {"prd_name":"product 3", "prd_price":"100.50"}                                        
        
 - Delete Product (POST): http://localhost:6001/products/delete      
         {"productId": "3"}                                                                   
