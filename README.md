# Restful-CRUD-API-with-Node.js-Express-and-MySQL

npm install
npm start

--------------------------------------------------
start mysql
mysql> source path_of_schema.sql_file/schema.sql

-------------------------------------------

APIs

 - Get All: http://localhost:6001/products                                                    // GET 
 
 - Get one: http://localhost:6001/products/1                                                  // GET
 
 - Add product : http://localhost:6001/products/add           
        {"prd_name":"product 3", "prd_price":"100.50"}                                        // POST
        
 - Delete Product: http://localhost:6001/products/delete      
         {"productId": "3"}                                                                   // POST
