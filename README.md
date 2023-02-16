# Module 13 Challenge - Object-Relational Mapping (ORM): E-Commerce Back End

>**Application Video:** [E-Commerce Back End](https://drive.google.com/file/d/15B7pzX4bBsVOQAwEAcHQQRmwDwZ9Svu5/view)
>
>**View:** [Description](#description) / [Application Details](#application-details) / [Application Sample Runs](#application-sample-runs)
>
>**Application Preview:**
>
>![E-Commerce Back End](./assets/ "E-Commerce Back End")
> 
## **DESCRIPTION**
> Topic Assessed: **sequelize** - **sequelize get, post, put, delete API Requests, sequelize Models, dotenv connection, etc.**
### **My Task**
*E-Commerce Back End* allows a user to add, pull, update, and delete information from the database using sequelize.
> Modify starter code.
> 
> Complete the database models with the defined requirements listed for each model.
>
> Execute association methods on the models to create relationships .
>
> Complete the API routes to Perform RESTful CRUD Operations.
>
> Sync Sequelize to the Database on Server Start.
> 
## User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
## Acceptance Criteria
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
## **APPLICATION DETAILS**

### server.js Information

### models Information
* **Category.js**: 
* **Product.js**: 
* **Tag.js**: 
* **ProductTag.js**: 
* **index.js**: 

### routes api Information
* **category-routes.js**: 
* **product-routes.js**: 
* **tag-routes.js**: 

### package.json Information
* **package**: Define the dependencies/packages used in the application.
  * Dependencies: 
    * `dotenv`, version ^8.2.0
    * `express`, version ^4.17.1
    * `mysql2`, version ^2.1.0
    * `sequelize`, version ^5.21.7
  * devDependencies: `nodemon`, version ^2.0.3

## **APPLICATION SAMPLE RUNS**
### Sample Runs
>![GET Request](./assets/ "GET Request")
>![POST Request](./assets/ "POST Request")
>![PUT Request](./assets/ "PUT Request")
>![DELETE Request](./assets/ "DELETE Request")