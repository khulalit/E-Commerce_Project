# E-Commerce_Project
### 

## M. Sc. Computer Science Semester III 
### E-Commerce Project 
### Lalit (22) 


URL of the Github : github.com/khulalit/Ecommerce_project

E-commerce Project proposal 
	 ___ A design ,theme and template selling website for developer.___

Features :
 (i) Must have
	- Register as a seller
	- Add Theme , Template and Design (Figma , XD, Sketch etc. ) 
	- Validation of Product
	- Register Customer
	- Explore Products
	- Add to Cart
	- Profile Status
	- Billing(cod/Credit Card-Visa or Mastercard/Debit Card)
	- Print or Share transaction
	- Record of previous transactions
	
(ii) Good to have
	- Personalized recommendations
	- Support from the seller
	


	
#  For Data Base I am using MongoDB 
		 
### Collections : 
one thing to note here is that Below collection will be implemented in MongoDB, that is a NoSql based implementation will be different.
*** for user auth using Auth0 for google and github signing ***  

## Users Collection
- User id(email)
- Name
- Auth0 ID
- Role

## Theme Provider
- Provider id(email)
- Name
- Auth0 ID
- Role

## Transaction
- Transaction id
- Ordered by(buyer id)
- Seller (seller id)
- Date bought
- Amount
- Payment id
- Date delivered
- Rating
- review

##  Store
- Product id
- seller
- price
- product images and gifs videos and demos(a web page for show the demo)
- product information
- reviews

## Review and rating
- review id
- rating
- reviewed by(user id)
- review text

## Payments
- Payment id
- Type ( Debit card upi etc paypal etc )
- Timestamp
- Amount
- Transaction id

## APIs

	Login - 
		/login 
			username and password  - post
	Register- 
		/register -  post
			if using gmail or other services then provide that otherwise 
			username email create password
		
	Product list - 
		/products/themes?page - get 
			top themes (in pages)
		/products/design?page - get 
			top design (in pages)
		/products/template?page -  get
			top template (in pages)
		/product/sellerid?productid  - get
			perticular  product from a seller
		
	Buy -
		/buy - post

	Post review 
		/postreview - post

Work done on 14th October 2022
	
	
