Create a set of Rest APIs for small E-Commerce Application
	Consider an entity Product that a user want to buy.
	1. Product: Title, description, price, available quantity, category, other-properties (can have different properties for different products)
	2. Admin: Admin user can add/update/delete Products, update stock
	3. Cart: User should be able to search of products and add to cart (quantity can be more than one)
	4. Checkout: User should be able to place order, send an email to user that order has been placed successfully.
	5. Update: Product stock after successfully order placed.(Order will placed for items in Carts).
	5. User: There should be two types of users 1. Admin, 2. End User
	All actions can only be performed by authenticated and authorised user. 

Assignment (Hints)
1. Create a Model for Products
2. Create a Model for categories having up to three levels of categories.
3. Every product must be added in some category.
4. Create a Model for cart so user can add products to cart in order to Proceed checkout
5. Write Following APIs (but not limited to)
	User Login/signup
	Product CRUD
 	Category CRUD
	Search Product
	Cart CRUD
	Checkout / placeOrder