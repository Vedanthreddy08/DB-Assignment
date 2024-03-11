1) The Relationship between the product and the product_category table is One to Many relationship,where we can also access and manipulate the category_id from the product_category tables directly without making any changes in the product table.The category_id acts as Primary key for product_category table.


2)The products which we are adding to the product table will be categorized by using the category_id where we will be assigning each different categories with different category_id 's.We will be using Foreign Key Constraint before adding the products to the product table we have to know which category the product is belonging to and whether that category is present or not.To effieciently categorize the products we use some Error Handling and UI validations.
