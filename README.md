# EcommerceSystem
An amazon like store selling various products to registered customers
The systems basic goal was to keep track of all its products, registered customers and all current orders and shipped orders(kept tracked in the eccomercesystem.java file
Implemented knowledge of array lists, objects, classes, inheritance and interfaces

-Succesfully implemented the comparable interface in customer file to compare each customer in order to see if customer exists in the system. Then keep track of all   components of the customer such as their id, name, address.

-Productorder class and java file stored the order of a product by a customer, containing an order number and furthermore product options provided (Paperback or hardcover for books) 

-Book was an additional subclass of product, which had more information such as title , author , came in different formats such as hardcover, paperback, and Ebook
Also kept a stockcount for each different category, and each time one was ordered, a reduce stock count function was implemented (*Ebook had infinite stock so no need for reducing)

-Had another subclass of products which was shoes that I just considered as a category for clothing, with different shoe sizes from 6-10, and possible options for colors black and brown.
