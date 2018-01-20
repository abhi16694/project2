# Project 2

## AWS public DNS

[ec2-54-255-247-29.ap-southeast-1.compute.amazonaws.com](http://ec2-54-255-247-29.ap-southeast-1.compute.amazonaws.com "E-Commerce REST API") 

## E-Commerce REST API.(Single Page Application)

### Basic information about the coding done.

- This E-Commerce application is based on basic instructions given.( MVC structuring.)

- It has all the API's that were instructed.

	1) Seperate API for signup, login, forgot password etc.(seperately defined for User and Admin)

	2) Seperate API for listing products, creating a product, viewing information of a particular product,deleting a product, editing a product etc.(Accessable by Admin only)

	3) Seperate API to add products to cart and remove products from cart.(Accessable by both Admin and User)

	4) API for placing order ​from​ ​cart.

- It has an Route level middleware that checks for authenticity of the user (i.e Admin or general User).

- All the Api's have their own error handling blocks, which is implemented with the help of response generator function that is defined in the libs file.

- All the information about scopes and which module is for what; these type of informations are explained by comments before and after the Api blocks.

- Use of Third Party vendors like Bootstrap, jQuery and font-awesome in the presentation part.

- Handling of all the routes for different API's are done with Angular Routing.

- Link of the hosted code on the github (https://github.com/abhi16694/project2.git).
