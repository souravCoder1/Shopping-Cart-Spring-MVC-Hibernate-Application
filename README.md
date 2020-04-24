# Shopping-Cart-Spring-MVC-Hibernate-Application
A shopping cart spring-MVC application with hibernate. The application sends user email confirmation on registration and it also gives the user to generate their final bill as a PDF with PDF-View.

1. The home page of the project is as follows:


2. If the user has not signed up before he gets an option to register himself. While the user registers, he gets the chance to either register as a customer or seller. The registration page looks as follows.


The registration page is embedded with validators, which checks the inputs for any unwanted scripts the user has entered.
3. The seller can then add the products into the product list from the product add page. The product details that can be added are the product title, a category that it belongs to, product description, its image, and price.


4. The product can be added to the user cart after the user logs in as a customer and selects the item from the list.


5. After checking out the item a PDF of the final bill is generated using the PDF View in Spring MVC. This PDF can be downloaded as per the user wish
