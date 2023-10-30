# Commerce Control System
**Welcome to the my application✨**

![structure](https://github.com/xadidja03/trade-control-system/assets/116426512/a1fdee58-742e-4659-9328-68b5cd87cfb6)


**Description:**
Welcome to the Commerce Control System README. This document provides an overview of the Commerce control application, its features, installation instructions, and usage guidelines.
This project encompasses a Spring Boot application designed to manage product, category, and supplier-related operations in a PostgreSQL database. 
The application provides a comprehensive set of features to facilitate effective management of various aspects of your business:

**Key Features:**
- Product: Empowers users to control every aspect of their products. Easily list, update, and delete products, aiding businesses in organizing inventory.
- Category: Users can add, modify, and delete product categories. Each product can belong to one or multiple categories, simplifying filtering and searching.
- Supplier: Organize supplier relationships. Add, update, or remove suppliers as needed. Associate products with suppliers for quick access to supplier details.
- Data Integrity and Validation: Ensures data integrity with custom validation rules. Prevents errors, like negative prices, and enforces category-specific rules, enhancing data quality.
- Database Relationship Management: Effectively manages relationships between database objects. Easily specify product-category or product-supplier associations for improved data organization.

**Technologies Used:**
- IDE - Intellij Idea;
- JDK - 1.8 or later;
- Spring Web - 2.7;
- Spring Data Jpa;
- PostgreSql
- Lombok
- Validation
- JUnit5
- Swagger

 **Endpoints and description**
 
![category controller](https://github.com/xadidja03/trade-control-system/assets/116426512/e6a30609-16b5-4bdc-acf8-ecaa40f0a5b6)

- POST /commerce/categories/registration
- GET /commerce/categories/showing
- Description: 1st endpoint allows you to create a new category. 2nd endpoint allows you to retrieve a list of all available categories. 

![supplier controller](https://github.com/xadidja03/trade-control-system/assets/116426512/97cd3833-f9c1-4384-9950-74eaaf8cd617)

- POST /commerce/suppliers/registration
- GET /commerce/suppliers/showing
- Description: 1st endpoint allows you to create a new suppliers. 2nd endpoint allows you to retrieve a list of all available suppliers.

![product-controller](https://github.com/xadidja03/trade-control-system/assets/116426512/eab569ad-f743-4032-875f-9ed1e6bb1a9f)


- POST /commerce/products/registration <br>**allows you to create a new products.**
- GET /commerce/products/showing       <br>**allows you to retrieve a list of all available products.**
- PUT/commerce/products/{id}           <br>**allows you to update an existing product by specifying its ID in the URL.**
- DELETE/commerce/products/{id}        <br>**allows you to delete a product by specifying its ID in the URL.**
- GET/commerce/products/{id}           <br>**allows you to retrieve details about a specific product by specifying its ID in the URL.**


# **The run of the building jar file**

![jar build](https://github.com/xadidja03/trade-control-system/assets/116426512/daeaf99a-8d10-43db-b0a7-2fe9a37933fb)

Feel free to explore the codebase, contribute, or fork the project if you find it beneficial. If you have any inquiries, suggestions, or collaboration opportunities, please don't hesitate to get in touch. Thank you for exploring the Commerce Platform repository!


  
